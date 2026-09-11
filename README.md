# NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
Cybersecurity Lab Environment Setup

Week 1 project — setting up a basic virtual lab for future cybersecurity practice using VirtualBox and Kali Linux.

What this covers
Installing VirtualBox
Importing Kali Linux as a VM
Creating a NAT Network so future VMs can be added and talk to each other
Checking that networking and internet access work


Setup

1. Install VirtualBox Used as the hypervisor for the lab.

2. Create a NAT Network Name: NatNetwork

Used a NAT Network instead of a regular NAT adapter so that multiple VMs on it can reach each other and still get internet access — needed for future attacker setups.

3. Import Kali Linux Downloaded from the official site and imported into VirtualBox.


4. Took a snapshot Named Clean Kali - Network Setup, so I have a baseline to restore to later.

Tools
VirtualBox
Kali Linux
Author

Triza Njenga LinkedIn

Networkwalks Cybersecurity Program — Week 1
