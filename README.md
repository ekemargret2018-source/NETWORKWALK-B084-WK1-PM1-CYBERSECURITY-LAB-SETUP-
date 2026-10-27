# NETWORKWALK-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP-
Cybersecurity Lab Setup
# Week 1: Kali Linux Networking Lab Setup

## Project Overview
This project is part of my Networkwalks Cybersecurity Internship, Batch B084. The aim was to set up a Kali Linux virtual machine using Oracle VirtualBox, configure its network connection, and test internet connectivity.

## Objectives
- Set up Kali Linux in Oracle VirtualBox.
- Configure the virtual machine to use a NAT Network.
- Check the assigned IP address.
- Test network connectivity using the ping command.

## Tools Used
- Oracle VirtualBox
- Kali Linux
- Terminal
- NAT Network

## Practical Steps

### 1. Network Configuration
I configured the Kali Linux virtual machine to use a NAT Network in Oracle VirtualBox.

### 2. IP Address Verification
I used the `ip a` command to inspect the network interfaces and identify the IP address assigned to the virtual machine.

### 3. Connectivity Test
I used the `ping -c 4 google.com` command to test internet connectivity and confirm that DNS resolution was working.

## Results
The Kali Linux virtual machine received an IP address of `10.0.0.3/24` on the `eth0` interface. The connectivity test to `google.com` completed successfully, with 4 packets received and 0% packet loss.

## What I Learned
- The purpose of virtual machines in cybersecurity labs.
- How NAT Network mode provides network connectivity to a virtual machine.
- How to inspect IP addresses using Linux commands.
- How to test connectivity using ping.

## Evidence
Screenshots of the VirtualBox NAT Network settings, the Kali Linux IP address, and the successful connectivity test will be included with this project.

## Conclusion
This practical helped me develop foundational skills in Linux networking and virtual machine configuration as part of my cybersecurity learning journey.

Program: Networkwalks Cybersecurity Internship  
Batch: B084  
Project: Week 1 Practical
