<p align="center">
  
![image](https://github.com/CarlosAlvarado0718/VPN-NETWORK/assets/140138198/07ac1b82-c83d-4984-be1b-87d0b8afa619)

</p>

<h1>Setting up a VPN and Observing the Effects of VPN on IP Addressing</h1>
In this tutorial, we'll outline the effects and impact that Virtual Private Network (VPN) has on IP Address, Location, and Web Browsing.
We'll set up our own Virtual Private Network (VPN)

>**Note***
>_This tutorial uses material from [Let's Create Resource Groups and Deploy a Virtual Machine Together!](https://github.com/marklibador/Create-Resource-Group)_

<h2>Environments and Technologies Used</h2>

- MicroSoft Azure Virtual Machines
- Remote Desktop Connection (RDP)
- Proton VPN (Free Version)

<h2>Operating Systems Used</h2>

 - Windows 10 (21H2)


---
<h2>Step By Step</h2>

>**Note***
>_A virtual private network is a mechanism for creating a secure connection between a computing device and a computer network or between two networks, using an insecure communication medium such as the public Internet._

- Go to [www.whatismyipaddress.com]](https://whatismyipaddress.com/)
- Remember your Public IP Address and City

![image](https://github.com/CarlosAlvarado0718/VPN-NETWORK/assets/140138198/3f18088c-9478-4f5d-b8cc-6a04be2d88ed)

- Go into MicroSoft Azure
- Create an Azure Virtual Machine
- Set the `Region` to **(Europe) France Central**
- Set `Image` to **Windows 10 Pro, version 22H2**
- Set everything else to your liking.

![image](https://github.com/CarlosAlvarado0718/VPN-NETWORK/assets/140138198/5b3a2e50-afb3-40a6-ab25-5f172483fbcf)

- Log into your Virtual Machine
- Go to [www.whatismyipaddress.com]](https://whatismyipaddress.com/) on your Virtual Machine
- Observe and Take note of your New IP Address/ Region/ City

![image](https://github.com/CarlosAlvarado0718/VPN-NETWORK/assets/140138198/d783648c-115b-4841-b4c3-ab9a8c46e3d6)
  
- Return to your PC
- Sign up for the Free Version of ProtonVPN
- Return to the Virtual Machine
- Log into your ProtonVPN Account using (https://account.protonvpn.com/login)
- Download the Client onto the Virtual Machine
- Complete the Installation
- Select a ProtonVPN Server located in Japan
- Let the Virtual Machine Restart

![image](https://github.com/CarlosAlvarado0718/VPN-NETWORK/assets/140138198/d119b5a5-556d-4b01-b061-e922b87241f4)


- Go to [www.whatismyipaddress.com](https://whatismyipaddress.com/) on your Virtual Machine, with VPN Activated
- Observe and Take note of your New IP Address/ Region/ City

![image](https://github.com/CarlosAlvarado0718/VPN-NETWORK/assets/140138198/a20b0e94-1cd7-47e5-a7d2-81b4106a0378)


---
<h2>Results Explanation</h2>
This tutorial has taught step-by-step how to install a VPN, using a Virtual Machine, and configure a VPN inside of it.

- Accessing your Main PC, you'll see your original IP Address/ Region/ City
- Within your Virtual Machine, you'll see your new IP Address/ Region/ City are displayed
- Once you activate your VPN within the Virtual Machine, you'll see the IP Address/ Region/ City are once again encrypted and replaced with the one in Japan
