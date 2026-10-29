# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output
<img width="1705" height="567" alt="image" src="https://github.com/user-attachments/assets/be0a332a-f6e8-491b-b082-56e21677ac4c" />



## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="1912" height="803" alt="image" src="https://github.com/user-attachments/assets/7eea8fa6-adaa-4562-8c17-eb1561d700d0" />



## History of the website:
## output
https://web.archive.org/
<img width="1912" height="845" alt="image" src="https://github.com/user-attachments/assets/f5e03918-7a16-442e-be49-ce6ae784644d" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="792" height="617" alt="image" src="https://github.com/user-attachments/assets/7abc9faa-5ad9-4227-8bcb-3cf638746a9a" />



## nmap:
### output
<img width="1721" height="557" alt="image" src="https://github.com/user-attachments/assets/a769b572-c1c2-4983-ba4c-6b04ec6f4204" />


## Whatweb
### output
<img width="1410" height="403" alt="image" src="https://github.com/user-attachments/assets/023aa462-8764-40d3-8b1a-1d7c1e01f69b" />



# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1232" height="175" alt="image" src="https://github.com/user-attachments/assets/94630f3f-9abc-4dea-93bf-04feb44c20d4" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1252" height="180" alt="image" src="https://github.com/user-attachments/assets/5d35b316-ebe0-47af-8221-225419392854" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="1230" height="177" alt="image" src="https://github.com/user-attachments/assets/c5569571-a4d3-4d92-9560-97fa546580c4" />

## RESULT:
The information gathering techniques tools/procedure were identified successfully.
