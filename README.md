# Communication-Network
Project about creating a network with packer tracer

 conditions
 1. Traffic only can go this way : R1->R2->R3->R4
 2. if there's link error, the traffic can go to opposite direction.
 3. SW1, Sw2 ...SW6 are connected to the same VLAN
 4. you have to do Ping test or trace router.
 5. you can set IP adress as you want but you have to set switches under C class
 6. VLAN 10 only can communicate with VLAN 10 and VLAN 20 only can communicate with VLAN 20. HoweverVLAN 10 and VLAN20 can NOT comunicate. 
 7. when you test ping or trace router, you have to make an error on purpose in order to see you made condition number 2.
 ![alt text](https://github.com/chaeyoonlee/Communication-Network/blob/master/condition.jpg)
