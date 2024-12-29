# firewall-project
Configuring pfSense Firewall with Private Subnet
Objective:
To set up a secure and efficient private network with a segmented WAN and LAN configuration using pfSense.

Key Steps:
Installed and configured pfSense on a dedicated hardware device.
Established a WAN (Internet-facing) and LAN (internal network) with distinct subnets.
Configured DHCP:
Customized the DHCP pool.
Assigned static IPs to critical devices for consistency.
Implemented network security:
Blocked private and bogon networks.
Created inbound and outbound firewall rules.
Connected the LAN to a managed switch:
Devices connected via Ethernet and an access point for Wi-Fi communication.
Configured a guest Wi-Fi on the WAN side for untrusted and IoT devices.
Tools/Technologies:
pfSense
Network switch
Wi-Fi access point
Outcome:
Established a robust and secure network with proper segmentation, improving manageability and security for connected devices.
