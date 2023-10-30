<p align="center">
  
![image](https://github.com/marklibador/Virtual_Private_Network/assets/37192566/ee998b51-461c-438f-b3d0-56adf2748c50)


</p>

<h1>Setting up a VPN and Observing the Effects of VPN on IP Addressing</h1>
In this tutorial, we will delineate the influence of Virtual Private Network (VPN) on IP Address, Location, and Web Browsing. Additionally, we will establish our own VPN for practical demonstration.

>**Note***
>_This tutorial uses material from [Let's Create Resource Groups and Deploy a Virtual Machine Together!](https://github.com/marklibador/Create-Resource-Group)_

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machines
- Remote Desktop Connection (RDP)
- Proton VPN (Free Version)

<h2>Operating Systems Used</h2>

 - Windows 10 (21H2)


---
<h2>Step By Step</h2>

>**Note***
>_A Virtual Private Network (VPN) establishes a secure and encrypted connection, safeguarding online activities from unauthorized access. It serves as a digital privacy shield, akin to a private tunnel, ensuring confidentiality and security in the digital realm._

- Go to [www.whatismyipaddress.com]](https://whatismyipaddress.com/)
- Remember your Public IP Address and City

![image](https://github.com/marklibador/Virtual_Private_Network/assets/37192566/b26f08c6-92a0-4d45-88b8-fb826165f82c)


- Go into MicroSoft Azure
- Create an Azure Virtual Machine
- Set the `Region` to **(Europe) France Central**
- Set `Image` to **Windows 10 Pro, version 22H2**
- Set everything else to your liking.

![image](https://github.com/marklibador/Virtual_Private_Network/assets/37192566/0d26f4c2-48c3-45a1-a726-e09ed4a461b0)


- Log into your Virtual Machine
- Go to [www.whatismyipaddress.com]](https://whatismyipaddress.com/) on your Virtual Machine
- Observe and Take note of your New IP Address/ Region/ City

![image](https://github.com/marklibador/Virtual_Private_Network/assets/37192566/a71b58fb-5a26-49a9-bc45-e5f384f6657a)

  
- Return to your PC
- Sign up for the Free Version of ProtonVPN
- Return to the Virtual Machine
- Log into your ProtonVPN Account using (https://account.protonvpn.com/login)
- Download the Client onto the Virtual Machine
- Complete the Installation
- Select a ProtonVPN Server located in Netherlands
- Let the Virtual Machine Restart

![image](https://github.com/marklibador/Virtual_Private_Network/assets/37192566/aedc90d5-4d3c-4786-aebf-ac8f654a6180)



- Go to [www.whatismyipaddress.com](https://whatismyipaddress.com/) on your Virtual Machine, with VPN Activated
- Observe and Take note of your New IP Address/ Region/ City

![image](https://github.com/marklibador/Virtual_Private_Network/assets/37192566/153dd382-c9ea-413b-8421-ba7c594245c5)



---
<h2>Results Explanation</h2>
This tutorial provides a comprehensive, step-by-step guide on installing a VPN. It specifically details the process of setting up a VPN within a Virtual Machine and configuring it effectively.


- Accessing your Main PC, you'll see your original IP Address/ Region/ City
- Within your Virtual Machine, you'll see your new IP Address/ Region/ City are displayed
- Once you activate your VPN within the Virtual Machine, you'll see the IP Address/ Region/ City are once again encrypted and replaced with the one in Netherlands
