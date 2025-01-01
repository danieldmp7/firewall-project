# **Firewall Project**
## Configuring pfSense Firewall with Private Subnet
### **Objective**:
#### To set up a secure and efficient private network with a segmented WAN and LAN configuration using pfSense.

## **Key Features**:
- **Segmented Network**:   
  Established a private subnet for allowed users and a public, guest subnet for, well, guests.
    - #### Private Network
    Established a secure private network where only authorized users (primarily myself) can access data. This network includes     a server for centrealized file sharing, and WI-Fi connectivity for devices such as personal phones and computers to            access the network.
  - #### Guest Network
    Created a seperate, isolated network for misc devices such as TVs, guest phones, tablets, laptops. Devices used primarily      for streaming, browsing, and temporary access to a network (All devices are on DHCP).
-  **DHCP Configuration**:
  -  Created a DHCP pool for dynamic IP assignment.
  -  Assigned static IP addreses to critical devices for consistency.
- **Network Security**: 
  - Blocked private and bogon networks.
  - Created inbound and outbound firewall rules.

## **Tools/Technologies**:
**pfSense**: For firewall use and scalability within the network.       
**Network switch**: unmanaged switch for efficient connections.   
**Wi-Fi Access Point**: For wireless connection within a network. 

## Outcome:
Established a robust and secure network with proper segmentation, improving manageability and security for connected devices.
