Basic-Routing/
# Basic Routing Lab
Documentation for basic routing labs.

## Objective
Set up a basic network with a single router and a PC , test connectivity using static IP configuration

![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20(4).png?raw=true)


## Steps

1. **Configure the Router:**
   ```plaintext
   enable
   configure terminal
   interface GigabitEthernet0/0
   ip address 192.168.1.1 255.255.255.0
   no shutdown
   exit

![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20(7).png?raw=true)


 2. ** Configure the PC:**

![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20(6).png?raw=true)
![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20(8).png?raw=true)




IP Address: 192.168.1.2
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1

3. ** Test Connectivity **
   ping from PC to router
   ping 192.168.1.1
Successful results indicate the setup is correct.
![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20(10).png?raw=true)
![Alt text](https://github.com/d0t0perator/Homelab-Documentation/blob/main/Basic-Routing/Basic%20Routing/Screenshot%20(11).png?raw=true)




