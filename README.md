<p align="center">


</p>
<p>

![Optional Image Description](https://i.imgur.com/2jcBIlK.jpeg)


</p>
<p>


<h1> Creating a Microsoft Azure Resource Group using Azure CLI - Prerequisites and Azure CLI  Installation</h1>
This tutorial outlines the prerequisites and installation of the Azure CLI as well as how to deploy a Microsoft Azure Resource Group using the Azure CLI. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource Groups)
- Azure CLI
- Windows Powershell

<h2>Operating Systems Used </h2>

- Windows 11</b> (22H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Subsciption
- Azure CLI 
- Windows PC (I am currently using Windows 11 version 22H2, but Windows 10 should also be compatible)
- Windows Powershell 

<h2>Installation Steps</h2>

<p>

</p>
<p>

  **Step 1: Install Azure CLI**

Ensure that the Azure CLI is installed on your Windows PC. If not, you can download and install it from the Official Azure CLI Page - (https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli). Choose 64 bit or 32 bit depending on your computer specifications.


</p>
<br />

<p>
 
![Optional Image Description](https://i.imgur.com/LmCIM39.png)

</p>
<p>

  **Step 2: Open Windows Powershell**

On your Windows PC. You can do this by searching for Windows Powershell in the Windows search bar.
</p>
<br />

<p>

 ![Optional Image Description](https://i.imgur.com/RmdfPOI.png)

</p>
<p>

**Step 3: Login to Azure**

To log in to your Azure account via the Azure CLI, run the following command:
**az login**


</p>
<br />

<p>

![Optional Image Description](https://i.imgur.com/tEQYdV2.png)


</p>
<p>

**Step 4: Set the Subscription (Optional)**

If you have multiple Azure subscriptions and want to specify which one to use, run:
az account set --subscription "<Your-Subscription-Id>"
Replace <Your-Subscription-Id> with your actual Azure subscription ID.



</p>
<br />

<p>

![Optional Image Description](https://i.imgur.com/zZUyuOF.png)

</p>
<p>

**Step 5: Create the Resource Group**

To create a new resource group, use the following command: **az group create --location westus --resource-group MyResourceGroup**,
Replace **"westus"** with your Azure region (e.g., eastus, centralus) and **"MyResourceGroup"** with the name you want for your resource group.


</p>
<br />

<p>

![Optional Image Description](https://i.imgur.com/Pig9K2a.png)

</p>
<p>

**Step 6: Verify the Creation**

To confirm that your resource group has been created, you can list all your resource groups with  following command:
**az group list --output table**
This will display a table of all your resource groups along with their details.

</p>
<br />

<p>

 ![Optional Image Description](https://i.imgur.com/lQ589qG.png)

</p>
<p>

And now you know how to deploy a Microsoft Azure Resource Group using the Azure CLI!
