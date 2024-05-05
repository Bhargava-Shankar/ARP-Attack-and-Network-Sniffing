# EX : 4 Network Sniffing and ARP Attacks

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
### OUTPUT:
![image](https://github.com/Bhargava-Shankar/ARP-Attack-and-Network-Sniffing/assets/85554376/6a92f476-8eba-4ebf-9813-c5a197552f1b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

![image](https://github.com/Bhargava-Shankar/ARP-Attack-and-Network-Sniffing/assets/85554376/aa5f20f0-7a0e-47ad-b6d5-27177329a041)

###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![image](https://github.com/Bhargava-Shankar/ARP-Attack-and-Network-Sniffing/assets/85554376/373cccc5-ef77-4778-ad40-13a781434ab1)


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![image](https://github.com/Bhargava-Shankar/ARP-Attack-and-Network-Sniffing/assets/85554376/50f25806-82bb-446b-9f8e-3c1a4eacbf2a)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Bhargava-Shankar/ARP-Attack-and-Network-Sniffing/assets/85554376/f2c7272b-73cf-435b-a740-bc549e6a86cb)

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
