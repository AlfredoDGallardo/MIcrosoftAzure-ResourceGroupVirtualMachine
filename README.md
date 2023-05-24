<p align="center">
<img src="https://i.imgur.com/7AUG74j.png" height="40%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Create a Resource Group and Deploy a Virtual Machine</h1>
Microsoft Azure is a cloud computing platform with numerous products and services. This guide will demonstrate how to utilize the portal to create a resource group and create a virtual machine, as well as access that virtual machine.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop Connection

<h2>Steps</h2>


1. Select Resource Groups within the Azure Portal

<p align="center">
<img src=https://i.ibb.co/09rqGBs/1.jpg
</p>
<br />
<br />

                 
1b. Select "Create Resource Group"

<p align="center">
<img src=https://i.ibb.co/27ScxY4/2.jpg
</p>
<br />
<br />
  
  
1c. Fill out information required as shown on image below and Click "Review + Create" when done.
   <br />(In this example, I used "Azure Subscription 1", named the resource group "RGLab1", and for region I selected "(US) East US" 

<p align="center">
<img src=https://i.ibb.co/DM6FLJW/3.jpg
</p>
<br />
<br />
  
  
1d. Resource Group has been created

<p align="center">
<img src=https://i.ibb.co/tpghftb/4.jpg
</p>
<br />
<br />  
  
  
2. Go to search bar and search for "Virtual Machines" and select it

<p align="center">
<img src=https://i.ibb.co/WFD8BZw/5.jpg
</p>
<br />
<br />  
  
  
2b. Click on "Create" and then select "Azure Virtual Machine"

<p align="center">
<img src=https://i.ibb.co/Mch1YMK/6.jpg
</p>
<br />
<br />  
  
  
2c. Fill out information required as shown on image below. Make sure you select the same subscription, region, and use the resource group you recently created. 
<br /> (In this example, I named the virtual machine "VM1" and selected image "Windows 10 Pro, Version 21H2 - 64x Gen2")
<p align="center">
<img src=https://i.ibb.co/n7dVptn/7.jpg
</p>
<br />
<br /> 
  
  
2d. Select virtual machine size and create a username and password for your virtual machine, then hit "Review + Create".
<br /> (In this example, I used size "Standard_B1s- 1 vcpu - 1 GiB memory" and created the username "labuser") 
<p align="center">
<img src=https://i.ibb.co/4W4MNwc/8.jpg
</p>
<br />
<br /> 
  
  
2e. If you get "Validation Passed" you are good to go then click "Create".

<p align="center">
<img src=https://i.ibb.co/GCV8yrW/9.jpg
</p>
<br />
<br />  
  
  
2f. Success! Virtual Machine has been created.

<p align="center">
<img src=https://i.ibb.co/0KhJKGN/10.jpg
</p>
<br />
<br />  
  
  
3. Go to Virtual Machines in the Azure portal and Select the Virtual Machine recently created.

<p align="center">
<img src=https://i.ibb.co/GQKLJPS/11.jpg
</p>
<br />
<br />  
  
  
3b. Open up "Windows" and select the application "Remote Desktop Connection"

<p align="center">
<img src=https://i.ibb.co/rGws5ZJ/12.jpg
</p>
<br />
<br />  
  
  
3c. Copy the Virtual Machines public IP address into the "computer" bar on the Remote Desktop Connection app. After that click "connect"
   <br /> (In this example, 20.172.224.222)
<p align="center">
<img src=https://i.ibb.co/pKr1fgp/13.jpg
</p>
<br />
<br />  
  
  
3d. Enter the username and password used when you created the Virtual Machine then select "OK"

<p align="center">
<img src=https://i.ibb.co/zP1FdWd/14.jpg
</p>
<br />
<br />  
  
  
3e. Select "Yes" on this pop up message you get

<p align="center">
<img src=https://i.ibb.co/BcBq2Qv/15.jpg
</p>
<br />
<br />  
  
  
3f. Congratulations! You are now connected to your virtual machine you created.

<p align="center">
<img src=https://i.ibb.co/BB0DRWx/16.jpg
</p>
<br />
<br />
<img src=https://i.ibb.co/m6ZPLqW/17.jpg

     
     
Congratulations! You have created your first resource group and a virtual machine within Azure.

