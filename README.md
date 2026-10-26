# B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
A hands-on cybersecurity lab with Kali Linux, Windows 10, and VirtualBox.

# Cybersecurity Internship Practical Task

1. Overview

This project documents a practical task assigned by my internship instructor. The task involved setting up Kali Linux and Windows 10 in Oracle VirtualBox, configuring their network settings, and testing connectivity between the two machines.

2. Objectives

- Set up Kali Linux and Windows 10 virtual machines.
- Configure network settings and IP addresses.
- Test connectivity between the two machines.
- Troubleshoot network configuration problems.
- Understand basic networking concepts used in cybersecurity.

3. Lab Setup

 Virtualisation software : Oracle VirtualBox 
 
 Security testing machine : Kali Linux 
 
 Target machine : Windows 10 
 
 Network type : NAT Network 
 
 Network name : NatNetwork 
 
 Network address : 10.0.0.0/24 
 
 Gateway : 10.0.0.1 
 
 Kali Linux IP : 10.0.0.2 
 
 Windows 10 IP : 10.0.0.10 

 4. Steps Followed

1. Created and configured the Kali Linux and Windows 10 virtual machines in VirtualBox.
2. Connected both virtual machines to the same NAT Network.
3. Configured and checked their IP addresses and network settings.
4. Used 'ip addr' and 'ip route` on Kali Linux to check the network configuration.
5. Used 'ipconfig /all` on Windows to check its network settings.
6. Used 'ping` to test connectivity between the two machines.
7. Investigated network issues and made adjustments where necessary.

5. Problems Encountered and Solutions

 Problem 1: Network Connectivity Issues

The virtual machines did not communicate as expected during the initial setup.

Solution: I checked the IP addresses, subnet mask, gateway, and network settings to identify possible configuration problems.

 Problem 2: IP Address Configuration

Configuring the correct IP addresses required attention to ensure both machines were on the same subnet.

Solution: I reviewed the network configuration and checked the assigned addresses using the available network commands.

Problem 3: Troubleshooting Network Communication

It was necessary to determine whether the connectivity issues were related to the IP configuration, virtual network, or firewall settings.

Solution: I used 'ping` and network inspection commands to help identify where the problem might be.


6. Lab Verification

I used the following checks to verify the lab configuration:

- Checked the IP addresses assigned to both virtual machines.
- Confirmed that both machines were connected to the intended VirtualBox network.
- Used 'ping` to test communication between Kali Linux and Windows 10.
- Checked the network interfaces and routing information on Kali Linux.
- Used 'ipconfig /all` to inspect the Windows network configuration.

Successful ping replies indicate that the machines can communicate using ICMP in that direction. If a ping fails, it does not automatically mean the entire network is incorrectly configured, as firewall rules can block ICMP traffic.

 7. What I Learned

Through this task, I learned how to:

- Set up virtual machines using Oracle VirtualBox.
- Configure a virtual network for communication between machines.
- Understand IP addresses, subnet masks, gateways, and MAC addresses.
- Use 'ping` to test network connectivity.
- Inspect network settings using Linux and Windows commands.
- Troubleshoot basic network configuration problems.
- Appreciate the importance of testing and verifying a lab before using it for further cybersecurity exercises.

8. Conclusion

This practical task gave me an opportunity to apply networking concepts in a virtual environment. Setting up the machines, checking their network configurations, and troubleshooting connectivity helped me gain a better understanding of how devices communicate over a network.

The exercise also provided a useful foundation for continuing to learn about cybersecurity and ethical hacking.


