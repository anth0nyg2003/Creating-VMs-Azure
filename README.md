<p align="center">

![image](https://github.com/user-attachments/assets/9222473a-edde-4c63-adb2-ddcfc89c9771)

</p>

<h1>Creating a Windows and Linux Virtual Machine with Microsoft Azure</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure and Virtual Machines

<h2>Operating Systems Used </h2>

- Windows 10 Pro
- Linux Ubuntu

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM) and select the previously created Resource Group. Allow VM to create a new Virtual Network (Vnet) and Subnet
- Create a Linux (Ubuntu) VM and select the previously created Resource Group and Virtual Network. The Windows and Linux Virtual Networks MUST BE THE SAME
- Specify Credentials, check Licensing Agreement and click "Review + Create" 

<h2>Deployment and Configuration Steps</h2>

<p>
    
 ![Screenshot 2025-06-24 100735](https://github.com/user-attachments/assets/de4c5463-31d5-44c7-b95d-f3e1b4a3439e)
 ![Screenshot 2025-06-24 101222](https://github.com/user-attachments/assets/821e81f3-4fdb-4cdd-98c9-aa309f4bd678)

</p>
<p>
From the Azure home page, click on "Resource Groups" and select "create new" Resource Group. Specify your Subscription, Resource Group Name, and Region. Click "Review + Create" 
</p>
<br />

<p>

 ![Screenshot 2025-06-24 103202](https://github.com/user-attachments/assets/0869a86d-ec7f-421b-84e9-cefca25c023f) 

</p>
<p>
From the Azure home page, click on Virtual Machines and select "Create New", Virtual Machine. Select the previously created Resource Group, Virtual Machine Name, Region, and Zone. Select "Windows 10 Pro" Image and at least 2 Virtual CPU's (vcpus) with 8 or 16 gigabyte ram. 
</p>
<br />

<p>

 ![Screenshot 2025-06-24 103746](https://github.com/user-attachments/assets/eca250d0-143f-4099-a600-5aa3da3aada7)

</p>
<p>
From the Networding tab, we'll need to specify a name for our Virtual Network. This is important because the Linux Virtual Machine must have the same Virtual Network as the Windows Virtual Machine. The rest is set by default, click "Review + Create"  
</p>
<br />

<p>

![Screenshot 2025-06-24 104839](https://github.com/user-attachments/assets/72308dfa-a8ac-4d83-82f4-5ec4e332536b)
![image](https://github.com/user-attachments/assets/3125ee5d-480f-4539-ab76-66a3e9c8fa5a)

</p>
<p>
After the Windows Virtual Machine is successfully deployed, you can click on it to view the network information. You will notice the Operating System, Ram Size, Public/Private IP Address, Virtual Network/Subnet, and Disk. This information will also be created with the Linux Virtual Machine   
</p>
<br />

<p>

![Screenshot 2025-06-24 112658](https://github.com/user-attachments/assets/c320faf4-e778-4a1d-b5d0-ec4ee9764fce)

</p>
<p>
We will follow the same process to create the Linux Virtual Machine by clicking on "Virtual Machines" and selecting "Create New".  Select the previously created Resource Group, Virtual Network, Region, and Zone. Select "Ubuntu Server 22.44 LTS - x64 Gen2"  for the Image and at least 2 Virtual CPU's (vcpus)  
</p>
<br />

<p>

![Screenshot 2025-06-24 112754](https://github.com/user-attachments/assets/cbbf048e-388c-4bca-9b71-99856e416288)

</p>
<p>
From the Networking Tab, make sure the Virtual Network Name of the Linux Virtual Machine is the same as the Windows Virtual Machine. Click "Review + Create"
</p>
<br />

<p>

![Screenshot 2025-06-24 115904](https://github.com/user-attachments/assets/b8576b4f-9241-4764-9b65-4e58d68b0c57)

</p>
<p>
After both Virtual Machines (VMs) have been successfully deployed, both VMs will appear after clicking on Virtual Machines. We have successfully deployed a Windows and Linux Virtual Machine from within the cloud using Microsoft Azure! 
</p>
<br />
