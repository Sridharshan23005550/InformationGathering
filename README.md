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


## whois:
```python
Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
```
## output:
![Screenshot 2025-03-08 111613](https://github.com/user-attachments/assets/5cfb7004-0b91-45ea-8f18-8ce1fe9a5ea8)


## Finding Hosting Company
```
get further detail by using ip2location.com website.
```
## output:
![Screenshot 2025-03-08 111959](https://github.com/user-attachments/assets/a2b8b78c-1bf1-471e-8b29-662ba49deb52)


## History of the website:

## output:

![Screenshot 2025-03-08 112434](https://github.com/user-attachments/assets/7bfea196-dc91-44bc-8409-3fc1f5d05fcb)


# Webserver Fingerprinting:

## Netcat:
```
sudo nc ticfiber.com 80
GET / HTTP/1.1
Host: ticfiber.com
```
## output:
![WhatsApp Image 2025-03-08 at 14 21 02_50f89ac6](https://github.com/user-attachments/assets/7014ac31-8acd-4881-a40b-3cb3bd23fb74)


## nmap:

## output:
![WhatsApp Image 2025-03-08 at 14 20 44_250ae052](https://github.com/user-attachments/assets/79fed06b-63cd-4dcd-bb44-21e7eb037b00)
![WhatsApp Image 2025-03-08 at 13 21 32_635dd6ba](https://github.com/user-attachments/assets/60d40b0f-cf25-4b3c-a18b-94a869b68079)

## Whatweb:
## output:
![WhatsApp Image 2025-03-08 at 14 20 25_baef870c](https://github.com/user-attachments/assets/dbe961bc-a2ed-4a7b-a3e9-0892f53d1b31)

# Tracing the Location:
```
TCP Traceroute:
sudo traceroute -T ticfiber.com
```
## output:
![WhatsApp Image 2025-03-08 at 14 20 02_5d3f4cd8](https://github.com/user-attachments/assets/4a7e49d0-96af-4621-a73b-9a2444e1ede2)

## UDP Traceroute:
```
sudo traceroute -U ticfiber.com
```
## output:
![WhatsApp Image 2025-03-08 at 14 19 39_1b248fe1](https://github.com/user-attachments/assets/07c36e9d-7803-4563-94b8-4957939983fc)

## ICMP Traceroute:
```
sudo traceroute ticfiber.com
```
## output:
![WhatsApp Image 2025-03-08 at 14 19 19_4aae2083](https://github.com/user-attachments/assets/ee2d0734-eaa4-4036-998b-7b1dfd7f66d8)
```


```
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
```
