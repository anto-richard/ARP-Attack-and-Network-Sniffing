# <p align="center">ARP-Attack-and-Network-Sniffing...</p>

# <p align="center">Explore Network Sniffing and ARP Attacks...</p>

# AIM :

To explore network sniffing and ARP Attacks.

## PROCEDURE :

### STEP 1 :

Install kali linux either in partition or virtual box or in live mode.

### STEP 2 :

Investigate on the various categories of tools as follows:

### STEP 3 :

Open terminal and try execute some kali linux commands.

## ARP Attacks :  

ARP spoofing : 

A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 

Boot kali and Windows7 virtual machines.

In windows 7 give the command arp -a

## OUTPUT :

![out1](https://github.com/anto-richard/ARP-Attack-and-Network-Sniffing/assets/93427534/2d1b9243-164c-467c-afa8-8cad94e8a01d)

From kali linux issue the command :

sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT :

![out2](https://github.com/anto-richard/ARP-Attack-and-Network-Sniffing/assets/93427534/ce866152-50f8-4e83-851f-1bb50e8aeca8)

 ## dsniff :

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT :

![out3](https://github.com/anto-richard/ARP-Attack-and-Network-Sniffing/assets/93427534/b3ac9cf5-b918-4365-8ba2-3d56a1182b74)

In Kali issue the following commands:

sudo dsnifff

## OUTPUT :

![out4](https://github.com/anto-richard/ARP-Attack-and-Network-Sniffing/assets/93427534/abe1d15d-f422-4798-817c-f75c802f30d1)

Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT :

![out5](https://github.com/anto-richard/ARP-Attack-and-Network-Sniffing/assets/93427534/b626b664-0de6-4d9b-9748-e956c79cfb87)

## Ettercap :

Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.

Ettercap can be used as sniffing tool as illustrated below:

## OUTPUT :

![out6](https://github.com/anto-richard/ARP-Attack-and-Network-Sniffing/assets/93427534/c874e2a8-b5bf-4304-b1dc-14ba108c30b8)

## RESULT :

The kali linux tools for ARP Attack and Network Sniffing were identified successfully.

