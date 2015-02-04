POX Load Balancing 

A very useful modification of the pox to add Equal-Cost capability for all topologies.

Instructions:
pox/forwarding/test.py is the modified file of pox/forwarding/l2_multi.py to add the round-robin(RR) function.

Breafly Explanation: 
test.py is equal cost version of the l2_multi.py component. In l2_multi.py it is used an scheme based on STP. As in this protocol, just one path is choosen for forwarding all packets, when there is a loop topology. Nevertheless, test.py allows forwarding through all paths avaliable, such as ECMP or TRILL.


