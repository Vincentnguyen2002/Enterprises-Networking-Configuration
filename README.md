# Enterprises Networking Configuration

- This is an personal network project which has a purpose to establish the connectiviy between end-hosts and internet, protect the system
- Moreover, it also includes most of the CCNA technique to apply in enterprise network system 

## Description
+ Components

  3 Switches (1 Layer-3 switch , 2 layer-1 switches)
  
  Ethernet Cables
  
  Console Cable
  
  USB to Serial Converter

+ Softwares
  
  Putty

  Cisco Packet Tracer (link to download: https://www.netacad.com/cisco-packet-tracer).

+ How i did the connectivity system
  
  Configure 4 VLANs on 2 layer-1 switches to seperate network into different small LANs to easily control, and with layer-3 switch also was configured with 4 vlans and set up with ip addresses
  
  Set up ethernet channel between layer-1 switch with layer-3 switch to prevent the failure if any ports goes down and boost up by accelerating bandwith
  
  Secure the system with port-security to allow only 2 MAC-address to plug in the switches, and create an extended access-control list in router to prevent any suspicious packet that is sent from inbound to outbound
  
  Build up the connectivity by constructing the OSPF routing protocol between LAN to the Internet
  
  Additionally, with spanning-tree portfast and bpduguard , they are two techniques that interact with each other.BPDU Guard is a security mechanism in STP, used to prevent PortFast ports from receiving BPDUs, and portfast is to make the time shorter down   to around 15 seconds to forward the packet

## How to experience the project
+ Firstly with downloading Cisco Packet Tracer and clicking to the topology.pkt file in Topology directory
+ Waiting for 1 to 2 minutes for the system can boost up and connectivity can be stable
+ if users want to try building the system , it is possible to go to Commands directory to see how to configure with each devices
