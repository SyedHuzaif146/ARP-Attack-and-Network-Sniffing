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
![image](https://github.com/user-attachments/assets/2005d358-425e-4813-9fb9-8026a7f08279)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![image](https://github.com/user-attachments/assets/6df3fc38-856c-4d5c-aabd-590e0cc57199)


 dsniff:
 
 ![image](https://github.com/user-attachments/assets/55f49d9f-f41c-4953-a2af-c52ec2142a4c)







In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/5d0ad8c3-5284-4d33-8185-2afb56672162)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/user-attachments/assets/d2d0084b-ae1d-4936-804e-b3e2153ca7a6)




Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
