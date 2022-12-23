
<h1>Getting Started with Virtual Machines</h1>
This project is a tutorial on creating and using a virtual machine in Azure. <br />


<h2>How to:</h2>


<p>
Create Azure Virtual Machines </p>
<p>
Use Remote Desktop to operate a VM </p>


<h2>Technologies Used</h2>

- Azure (VMs/Compute)
- Remote Desktop (RDP)

<h2>OS Used </h2>

- Windows 10 (21H2)

<h2>Stages</h2>

- Stage 1: Create
- Stage 2: Use

</br>

<h2>CREATE:</h2>
<p>
Step 1: Navigate to azure.microsft.com </br>
Step 2: Open a free Azure account (this is referred to as setting up your tenant and subscription). </br>
Step 3: Search ‘Resource Groups’ and create a Resource Group. When setting up, choose the region most local to you. Click “Review + Create”, then click “Create” on the next page. </br>
Step 4: Search ‘Virtual Machines’ and click Create on the option titled ‘Azure Virtual Machine’. </br>
Step 5: Choose the location of virtual machine to be in the resource group that you created previously. </br>
Step 6: Give your Virtual Machine a name and select the same region used for your resource group. Click Image and choose an operating system and for size select the desired CPU specifications. Create a username and password for the administrator account. Check the box called licensing; then click ‘Review + Create’. Last, click ‘Create’.
</p>
<br />

<h2>USE:</h2>
<p>
Step 7: Search ‘Virtual Machines’ in the Azure portal’s search bar. </br>
Step 8: Open the overview page of your VM and locate the public IP address. Copy this IP address to your clipboard. </br>
Step 9: For Windows, type in “remote desktop”; then paste the Azure VM’s public IP address. When prompted enter your username and password you created for this virtual machine. For Mac, download the Microsoft Remote Desktop app from the app store. Click ‘Add PC’ and paste the public IP address of your VM where it says ‘PC Name’. Then enter your username and password you created previously and click save. </br>
Step 10: Click on the PC to load and access your virtual machine.
</p>
<br />


