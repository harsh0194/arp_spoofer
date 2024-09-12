ARP Spoofing Script
This repository contains a Python script for performing ARP spoofing attacks using the Scapy library. The script is designed for educational purposes and should be used responsibly within authorized environments.

Prerequisites
Ensure you have the following installed:

Python 3.x

Scapy library. 

Description
The script performs ARP spoofing (also known as ARP poisoning) to intercept or manipulate network traffic between devices. It continuously sends spoofed ARP responses to target devices, pretending to be another device on the network.

Functions
get_mac(ip): Retrieves the MAC address of a device with the specified IP.
spoof(target_ip, spoof_ip): Sends a forged ARP response to the target IP, claiming to be the source IP (spoof_ip).
restore(destination_ip, source_ip): Restores the original ARP table entries by sending correct ARP responses.

Important Notes
Legal Usage: This script should only be used in a controlled environment or with explicit permission. Unauthorized use of ARP spoofing can be illegal and unethical.
Network Disruption: ARP spoofing can cause network disruptions and should be used with caution.
