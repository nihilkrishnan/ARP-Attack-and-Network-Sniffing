# ARP-Attack-and-Network-Sniffing
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

![exp 4 1](https://github.com/keerthanaa10/ARP-Attack-and-Network-Sniffing/assets/132996371/90e09f6b-3ce8-4e08-90f1-c1c04e600d46)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![exp 4 2](https://github.com/keerthanaa10/ARP-Attack-and-Network-Sniffing/assets/132996371/f8969e37-1241-4387-8fb2-2a53e0fe79b6)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![exp 4 3](https://github.com/keerthanaa10/ARP-Attack-and-Network-Sniffing/assets/132996371/5490dde0-a4c0-4e93-b0aa-ec82d7ea255c)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![exp 4 4](https://github.com/keerthanaa10/ARP-Attack-and-Network-Sniffing/assets/132996371/84db6105-e1e7-41c2-8fe4-928092755391)


Invoke the wireshark and examine the various menus  and controls of the tool:
![exp 4 5](https://github.com/keerthanaa10/ARP-Attack-and-Network-Sniffing/assets/132996371/e1bb9d7b-8d86-46ff-8217-4ff94819f4d4)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
