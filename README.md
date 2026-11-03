# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install Parrot Security OS either in a partition, VirtualBox or in live mode.



### Step 2:

Investigate the various categories of network security tools available in Parrot OS, such as:

arpspoof
dsniff
Metasploit Framework
Wireshark
Ettercap
tcpdump


### Step 3:
Open the terminal and execute some Parrot OS commands.
```
cat /etc/os-release
ip addr
ip route
ip neigh
ifconfig
```

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
```
ipconfig
arp -a
```
## OUTPUT:
<img width="852" height="601" alt="image" src="https://github.com/user-attachments/assets/cff0fb92-61be-490d-bca5-ac861bbe7183" />


From Parrot OS, identify the active network interface using:
```
ifconfig

```
<img width="1025" height="493" alt="image" src="https://github.com/user-attachments/assets/674034b7-c526-4ae1-8cb3-a16e07992bf0" />


Examine the ARP neighbor table using:
```
ip neigh
```
<img width="895" height="108" alt="image" src="https://github.com/user-attachments/assets/b33be575-8134-4972-85d6-63053b682d92" />

Check the routing information using:
```
ip route
```
<img width="1291" height="120" alt="image" src="https://github.com/user-attachments/assets/e6091849-e77c-4df4-921d-945c99558f58" />

ARP spoofing concepts and their effects on IP-to-MAC address mappings were studied in an isolated virtual network.


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
