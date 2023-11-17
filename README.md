# InformationGathering
Information Gathering Techiques

## To perform information gathering techniques

## AIM:

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

<img height=30% width=80% src="https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/93be2e15-6d5f-4a08-b388-603929d20367">

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:

<img height=30% width=80% src="https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/fcfa6599-0910-44f9-9f80-8675ae08893c">

## History of the wbsite:
## Output:
https://web.archive.org/

<img height=30% width=80% src="https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/db356479-b506-4b5c-97e2-8781af87c5de">

## Web server Fingerprint:
Netcat:
```
nc 172.17.52.118 80
```
## OUTPUT:

<img height=30% width=80% src="https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/af9060d2-7fea-4c18-a92b-60e77bbb6ac4">

## nmap
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## OUTPUT
![image](https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/2498d78f-e535-4f8b-96e0-052bd431325a)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## OUTPUT
![image](https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/465ba57f-78d4-429f-862d-059d1f56a472)

## httprint
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## OUTPUT
![239422518-e1275ae0-7aef-43d9-a8bf-99be791d0070](https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/f59f0b7e-bea2-4642-99b9-a9767847d184)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT
![239422644-67469d67-bba1-4fa1-925d-1bc35c4146ca](https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/de4f1456-1773-40f8-b1d3-388bae6aabb0)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![239422752-6f980827-c16f-4865-afff-1de0714937fd](https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/a297fa4a-e19f-4b5f-aba3-0b35819890aa)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![239423060-5b0e049e-98ee-4849-ad1c-de8d8189927e](https://github.com/Vasanthamukilan/InformationGathering/assets/119559694/e8d554f5-0b5a-4c6f-ae34-17326ad87c0a)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
