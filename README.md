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
## OUTPUT:

<img width="1025" height="493" alt="image" src="https://github.com/user-attachments/assets/674034b7-c526-4ae1-8cb3-a16e07992bf0" />


Examine the ARP neighbor table using:
```
ip neigh
```

## OUTPUT:

<img width="895" height="108" alt="image" src="https://github.com/user-attachments/assets/b33be575-8134-4972-85d6-63053b682d92" />

Check the routing information using:
```
ip route
```
## OUTPUT:

<img width="1291" height="120" alt="image" src="https://github.com/user-attachments/assets/e6091849-e77c-4df4-921d-945c99558f58" />

ARP spoofing concepts and their effects on IP-to-MAC address mappings were studied in an isolated virtual network.


 dsniff:
 
dsniff is a collection of network auditing and traffic analysis tools used to examine network traffic.

Install dsniff using:
```
sudo apt update
sudo apt install dsniff -y
```
Check the available utilities using:
```
dsniff -h
dpkg -L dsniff
```
## OUTPUT:

<img width="1088" height="852" alt="image" src="https://github.com/user-attachments/assets/b1907a23-ebd7-462b-8002-c4a54d09c3cf" />

Metasploit Framework:
Metasploit is a penetration-testing framework used for security testing and vulnerability assessment.

Open Metasploit using:
```
msfconsole
```
## OUTPUT:

<img width="1157" height="547" alt="image" src="https://github.com/user-attachments/assets/91d2a67e-79da-4d55-9671-27d8e8d11269" />

Search for FTP-related auxiliary modules using:
```
search type:auxiliary ftp
```
## OUTPUT:
<img width="1816" height="845" alt="image" src="https://github.com/user-attachments/assets/ad375a78-5690-428a-a7bd-c83f0410078d" />

Examine FTP service identification modules.

Wireshark:
Wireshark is a network protocol analyzer used to capture and examine network packets.

Invoke Wireshark using:
```
sudo wireshark
```
## OUTPUT:

<img width="1917" height="810" alt="image" src="https://github.com/user-attachments/assets/c26bc159-cdfd-4032-94bf-b0ca8b881c0b" />

Examine the various menus, controls, packet details and protocol information available in Wireshark.

## OUTPUT:
<img width="1917" height="922" alt="image" src="https://github.com/user-attachments/assets/5f5eb529-ba06-4262-b35e-b367dd83a114" />

ARP packet:
<img width="977" height="813" alt="image" src="https://github.com/user-attachments/assets/dc39e2cb-4ff6-463b-a7f5-3d3dfeb34466" />

Ettercap:
Ettercap is a network security tool that supports active and passive network analysis and host discovery.

Open Ettercap using:
```
sudo ettercap -G
```
Explore the following menus:

Sniff
Hosts
Targets
View
Plugins
Examine the graphical interface and network analysis features.

## OUTPUT:
<img width="952" height="811" alt="image" src="https://github.com/user-attachments/assets/564ec7c5-2a8c-40a1-9bd5-14443aace59d" />

tcpdump:
tcpdump is a command-line network packet analyzer used to capture and examine network traffic.

Check the installed version using:
```
tcpdump --version
```
Examine the available network interfaces using:
```
sudo tcpdump -D
```
## OUTPUT:

<img width="1090" height="382" alt="image" src="https://github.com/user-attachments/assets/2f198e77-a068-47f0-a01c-2794a0fab795" />


Capture ARP packets on the active interface using:
```
sudo tcpdump -i enp0s3 arp
```
Stop packet capturing using Ctrl + C.

## OUTPUT:
<img width="1002" height="335" alt="image" src="https://github.com/user-attachments/assets/30a6bf56-93d9-40a7-8bfa-839b324e4388" />



## RESULT:
Thus, the network security and network sniffing tools available in Parrot OS, including arpspoof, dsniff, Metasploit, Wireshark, Ettercap and tcpdump, were explored successfully. The concepts of ARP attacks, ARP tables, network interfaces and packet analysis were studied.
