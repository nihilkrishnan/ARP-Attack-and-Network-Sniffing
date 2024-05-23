# EX-4.ARP-Attack-and-Network-Sniffing
## Date:19/03/2024
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/Darkwebnew/ARP-Attack-and-Network-Sniffing/assets/143114486/73a8779a-4686-4f0f-88f2-fc8a1d311b6e)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/Darkwebnew/ARP-Attack-and-Network-Sniffing/assets/143114486/28f8309a-892a-42c9-b9d7-21a827c89438)

dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Darkwebnew/ARP-Attack-and-Network-Sniffing/assets/143114486/7ed2b359-5946-4877-a6d1-fc929c69deb2)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Darkwebnew/ARP-Attack-and-Network-Sniffing/assets/143114486/af9d1b0f-2bfc-4068-a84d-2e2ad5d229ab)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Darkwebnew/ARP-Attack-and-Network-Sniffing/assets/143114486/68b0f74b-1241-4353-8bb9-0a60f67536bf)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
