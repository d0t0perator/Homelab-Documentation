Basic-Routing/
# Basic Routing Lab
Documentation for basic routing labs.

## Objective
Set up a basic network with a single router and a PC , test connectivity using static IP configuration

##Topology
## Topology
## Topology
![Topology](./Basic-Routing/Screenshot (4).png)



## Steps

1. **Configure the Router:**
   ```plaintext
   enable
   configure terminal
   interface GigabitEthernet0/0
   ip address 192.168.1.1 255.255.255.0
   no shutdown
   exit
   ## Topology
![Topology](./Basic-Routing/Screenshot (7).png)


 2. ** Configure the PC:**
## Topology
![Topology](./Basic-Routing/Screenshot (6).png)

## Topology
![Topology](./Basic-Routing/Screenshot (8).png)

IP Address: 192.168.1.2
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1

3. ** Test Connectivity **
   ping from PC to router
   ping 192.168.1.1
Successful results indicate the setup is correct.

## Topology
![Topology](./Basic-Routing/Screenshot (10).png)
![Topology](./Basic-Routing/Screenshot (11).png)


