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
<img width="772" height="433" alt="image" src="https://github.com/user-attachments/assets/5a2333a6-1559-4f78-9387-a782cdf70d58" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="786" height="518" alt="image" src="https://github.com/user-attachments/assets/479679a9-74fe-4ec0-9bfb-e9dcc19e0fc4" />

 dsniff:

<img width="805" height="137" alt="image" src="https://github.com/user-attachments/assets/9e1308de-858c-45bc-9faf-0be0f559b4fc" />





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1475" height="613" alt="image" src="https://github.com/user-attachments/assets/83bd60a0-a0d9-4747-999e-5db275e4ab38" />




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="1483" height="732" alt="image" src="https://github.com/user-attachments/assets/da110107-8149-4b0a-ad5a-200ebb760130" />

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:
<img width="681" height="392" alt="out6" src="https://github.com/user-attachments/assets/ea85c924-13aa-48f5-af94-6003de8be3c5" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
