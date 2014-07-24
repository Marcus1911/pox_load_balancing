POX_load_balancing is just modification of the pox to add loading balancing function.

pox/forwarding/test.py is the modified file of pox/forwarding/l2_multi.py to add the load balancing function.

The test topology is 4 hosts h1,h2,h3,h4 which mac addresses end up with 01,02,03,04, 4 switches with switch id a,b,c,d. And h1,h2 attached to the switch a, and h3,h4 attached to the switch c. The links between switches are a-b-c-d-a, 4 switches diamond topology.
