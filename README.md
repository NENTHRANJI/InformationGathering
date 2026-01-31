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

##output

<img width="1919" height="1199" alt="Screenshot 2026-01-30 092336" src="https://github.com/user-attachments/assets/d4e0df6a-12e9-4bc8-bce7-c7e4c79f98a7" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1919" height="1199" alt="Screenshot 2026-01-30 092858" src="https://github.com/user-attachments/assets/59d6b582-693a-4913-9688-557e052d9e2f" />


## History of the website:
## output
https://web.archive.org/
<img width="1919" height="1199" alt="Screenshot 2026-01-31 101927" src="https://github.com/user-attachments/assets/924166e6-eeb7-4685-98fe-d870f4e27024" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="1920" height="478" alt="image" src="https://github.com/user-attachments/assets/85fdf17b-370c-4559-b9cb-2007342cc6bb" />


## nmap:
###output

<img width="1866" height="204" alt="image" src="https://github.com/user-attachments/assets/d08d716e-62c2-4922-b28f-4501d48fd1ea" />

## Whatweb
### output
<img width="1920" height="209" alt="image" src="https://github.com/user-attachments/assets/28ff4b94-4565-4c74-a265-00209b4455b7" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1920" height="165" alt="image" src="https://github.com/user-attachments/assets/9d48aed1-a6a3-4b87-9ff8-cab82520152b" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output

<img width="1920" height="165" alt="image" src="https://github.com/user-attachments/assets/474e241f-4b42-468d-8da0-035615334a9a" />


## ICMP Traceroute:
sudo traceroute  www.google.com
## output



<img width="1920" height="224" alt="image" src="https://github.com/user-attachments/assets/70a4eeae-a093-4988-b75c-8b814b7cc6e2" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
