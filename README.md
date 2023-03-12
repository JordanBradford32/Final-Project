<p align="center">
<img src="https://i.imgur.com/owSwbug.jpg alt="Traffic Examination"/>
</p>

<h1>Virtual Private Network (VPN) setup and usage on ProtonVPN</h1>
In this tutorial, I will observe the change in the IPv4 adresssing with my PC and an Azure virtual machine, with and without VPN. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>VPN Steps</h2>

- Step 1 - Create virtual machine inside Azure  
- Step 2 - obtain Public IPv4 address from both my pc and Azure virtual machine 
- Step 3 - install VPN inside Azure virtual machine
- Step 4 - connect to new VPN server and find new IPv4 address


<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/gZFScoZ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First I created both a resource group and a Virtual machine inside the resource group. I then went back into the virtual machine and found the public IPv4 address.
</p>
<br />

<p>
<img src="https://i.imgur.com/i85tRBj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then connected to microsoft remote desktop, using the public IP address i got from the Azure virtual machine. After I logged in, I went to whatismyipaddress.com. From there I seen the IPv4 address was the same from the virtual machine, but the location Was not the location I'm currently in. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hPXBrXi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that I went to check the IPv4 address of my PC. I again used whatismyipaddress.com. I was able to get the IP address of my pc and see that the loaction of my IP address was infact where I am. 
</p>
<br />
 
<p>
<img src="https://i.imgur.com/i5BnWQU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
While back inside the microsoft desktop, I logged in and installed ProtonVPN. I decided to connect to a IP address in the Netherlands.
</p>
<br />   

<p>
<img src="https://i.imgur.com/hdVedy3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, I searched for the new IPv4 address inside microsoft desktop, this time with the VPN connected. I discovered that the IPv4 address did infact change and the location was in the Netherlands 
</p>
<br />                                                                                                    
