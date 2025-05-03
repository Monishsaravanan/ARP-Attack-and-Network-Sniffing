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

```
NAME: ATCHAYA.K
REGISTER NO: 212223220011
```

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a

## OUTPUT:
![image](https://github.com/user-attachments/assets/0bab39ae-94ee-4281-8fa1-9fc1111ede92)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![image](https://github.com/user-attachments/assets/e29aa8ef-2396-4987-ad2b-f2ff7f7b8c23)




 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![image](https://github.com/user-attachments/assets/11a5b427-d408-42f9-b14b-16cf701b8b12)



In Kali issue the following commands:
sudo dsnifff

## OUTPUT:

![image](https://github.com/user-attachments/assets/69f14fd1-bdae-4f0f-98bc-6e9e2ef80fb1)

Invoke the wireshark and examine the various menus and controls of the tool. Also following shows how wireshark can be used as sniffing tool. 


##Ettercap Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:

![image](https://github.com/user-attachments/assets/2f23a140-20d0-4a9c-972c-f20e7a070105)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully







