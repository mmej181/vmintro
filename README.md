
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

- Create
- Use

</br>

<h2>Stage 1: Create</h2>
<p>
Step 1: Navigate to azure.microsft.com

Step 2: Open a free Azure account (this is referred to as setting up your tenant and subscription).

Step 3: Search ‘Resource Groups’ and create a Resource Group. When setting up, choose the region most local to you. Click “Review + Create”, then click “Create” on the next page. 
 
  ![](media/STEP%203%20-%20RESOURCE%20GROUP.png)

Step 4: Create a Storage Account which will hold your Virtual Machine. Ensure it is also in the same region as your resource group.

![](media/STEP%204%20-%20STORAGE%20ACCOUNT.png)

Step 5: Search ‘Virtual Machines’ and click Create to select the option titled ‘Azure Virtual Machine’. Choose the location of the virtual machine to be in the resource group and storage account that you created previously.

![](media/STEP%205%20-%20AZURE%20VIRTUAL%20MACHINE.png)

Step 6: Give your Virtual Machine a name and select the same region used for your resource group. Click Image and choose an operating system and for size select the desired CPU specifications. Create a username and password for the administrator account. Check the box called licensing; then click ‘Review + Create’. Last, click ‘Create’.

![](media/STEP%206%20-%20VM%20SPECS.png)

</p>
<br />

<h2>Stage 2: Use</h2>
<p>
Step 7: Search ‘Virtual Machines’ in the Azure portal’s search bar.

Step 8: Open the overview page of your VM and locate the public IP address. Copy this IP address to your clipboard.
  
 ![](media/STEP%208%20-%20PUBLIC%20IP%20ADDRESS.png)

Step 9: For Windows, type in “remote desktop”; then paste the Azure VM’s public IP address. When prompted enter your username and password you created for this virtual machine. For Mac, download the Microsoft Remote Desktop app from the app store. Click ‘Add PC’ and paste the public IP address of your VM where it says ‘PC Name’. Then enter your username and password you created previously and click save.

![](media/STEP%209%20-%20ADD%20PC.png)

Step 10: Click on the PC to load and access your virtual machine.
</p>
<br />


