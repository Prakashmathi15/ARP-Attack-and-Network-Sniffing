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
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/ARP-Attack-and-Network-Sniffing/assets/119644432/b4829b8b-196f-44cc-bfd2-538b31bcc677)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/ARP-Attack-and-Network-Sniffing/assets/119644432/71319f80-96b4-4188-b449-90408dfbea62)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/ARP-Attack-and-Network-Sniffing/assets/119644432/ccf20b1e-fd33-4ee5-ba1f-16620b3de8b8)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/ARP-Attack-and-Network-Sniffing/assets/119644432/84e9be0a-f11a-43f2-8205-a068757355e8)




Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/ARP-Attack-and-Network-Sniffing/assets/119644432/9c726608-5d93-4ce0-bae0-a7e153512d47)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
