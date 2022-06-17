# Network-Topology
# Network Simulation Using Cisco Packet Tracer

## Network Logical Design
<p align="middle">
  <img src="../master/Logical.png"/>
</p>

## Network Physical Design
<p align="middle">
  Company x
  <img src="../master/cmp x.png"/>
</p>
<p align="middle">
  Company y
  <img src="../master/cmp y.png"/>
</p>

## Problem Statement
Suppose that you are the CEO of a startup deals with network configuration for various companies. You received your first assignment to configure the network for two companies in such a way that all the PCs in each company must be able to communicate with each other as well as with all the PCs of any other company.
The companies are named as CMP X and CMP Y.
•	CMP X has 5 Rooms with 1 PC in each room.
•	CMP Y has 3 Rooms with 3 PCs in each room.
The IP regulating company has assigned the following IP network addresses to each of the company:
•	CMP X: 140.170.60.0/19
•	CMP Y: 40.130.0.0/15
As part of the agreement, the two companies have asked you to bear the expense of all the switches and routers used to interconnect all the computers in a merged network for two companies and further instructed you that all the PCs in a single room must be on the same sub network and all the rooms of a single company must be on a different sub-network which will be assigned after sub-netting the assigned network address only for the relevant company (no outside network or the network of other company will be accepted) e.g, each room for CMP X will be assigned a different sub-network after sub-netting the address of 140.170.60.0/19 only and not any other network address. The companies have further informed you that companies plan to extend the number of their PCs in each room in the future.
You, being cleverly economical, decide to install old switches (Generic Switches in Cisco Packet Tracer) with only three Ethernet ports working out of four and routers (Generic Routers in Cisco Packet Tracer) to configure the network for two companies in such a way that you use as much less routers and switches as possible.
You have also bought the following IP network address for the serial communication between different routers that will be connecting different Inter-Company and Intra-Company subnets. You plan to form the subnets of the following address in order to cater the serial communication between all the routers: Routers Serial Communication: 199.210.121.160/28

## Constraints
Simulate the topology on Cisco Packet Tracer in order to optimally design the network considering the number of devices (switches, routers etc.) used to maximize the profit margins of your company. However, you must simulate the topology strictly following rules and regulations described below:
1- Use Straight Through wires, Cross Over cables or Serial DCE wires where necessary and applicable.
2- Use Generic Router and Generic PCs for your design
3- Use Generic Switches such that you attach only 3 of the 4 available Ethernet Interfaces for a single switch, however, you can attach as many switches considering optimal design.
4- You have to assign IPs to the PCs using Static IP allocation.
5- design the physical network in each room
## How to run
Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) and then simply open the [network.pkt](../master/Project.pkt). The whole network is in working condition. 

