# NetworkWalks-B084-Week1-Setup
Network Walks Internship Week 1 Assignment: Cybersecurity Lab Setup

This repository is a documentation of my attempt at the week 1 laboratory work as presented by NetworkWalks for the batch B084 Cybersecurity internship. In this project, I managed to complete a successful setup of a virtual cybersecurity lab environment using Oracle VirtualBox.

Presented are the screenshots of my process and a description of the steps taken:

First, I created a NAT Network in Oracle VirtualBox named NatNetwork with the subnet 10.0.0.0/24, this is to ensure an isolated communication channel. Then, I imported Kali Linux into VirtualBox. Kali Linux will take the role of the attacking machine, and as such will be assigned a static IP address of 10.0.0.2/24. Once the setup is done, I verified full internet access from the VM by pinging Google's DNS (8.8.8.8). After that, I enabled a shared folder between my host machine and the Kali Linux for easier file transfers. The screenshots presented below are taken and transported through the shared folder. Finally, after all steps are completed, I took a VM snapshot to preserver the working state of the machine for future tasks.
