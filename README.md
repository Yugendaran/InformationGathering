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


## OUTPUT:
## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
### OUTPUT:

![Screenshot_2024-03-05_02-53-41](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/ea19a3f0-e9f4-4ae8-877c-d214a54765e3)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
### OUTPUT:

![Screenshot_2024-03-05_02-59-50](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/5408f712-db17-465b-b4b2-eb09466355b1)

## History of the website:
### OUTPUT:

![Screenshot_2024-03-05_03-04-45](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/380f85f6-528e-4898-8dc2-78c034b93884)

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

### OUTPUT:

![Screenshot_2024-03-05_03-11-56](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/8d14b60f-231e-4f79-b3e9-e7cc8deeb928)

## nmap:
### OUTPUT:

![Screenshot_2024-03-05_03-15-01](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/3d072b67-cc79-4449-a920-bbd271fcd483)

## Tracing the Location
## UDP Traceroute:
sudo traceroute -U www.google.com
### OUTPUT:

![Screenshot_2024-03-06_03-16-52](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/f9a0cc25-55a4-4781-a505-970cfb80695f)

## ICMP Traceroute:
sudo traceroute  www.google.com
### OUTPUT:

![Screenshot_2024-03-06_03-18-07](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/4b7c467d-16f0-4b47-a990-a7b8cfb52a55)


## TCP Traceroute:
sudo traceroute -T www.google.com
### OUTPUT:

![Screenshot_2024-03-06_03-19-44](https://github.com/Aishwarya-TM/EH-EX02-InformationGathering/assets/127846109/2be2fed2-991a-4c17-99e2-015611b76f99)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
