Basic-Routing/
# Basic Routing Lab
Documentation for basic routing labs.

## Objective
Set up a basic network with a single router and a PC , test connectivity using static IP configuration

![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20().png?raw=true)


## Steps

1. **Configure the Router:**
   ```plaintext
   enable
   configure terminal
   interface GigabitEthernet0/0
   ip address 192.168.1.1 255.255.255.0
   no shutdown
   exit




 2. ** Configure the PC:**






IP Address: 192.168.1.2
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1

3. ** Test Connectivity **
   ping from PC to router
   ping 192.168.1.1
Successful results indicate the setup is correct.




