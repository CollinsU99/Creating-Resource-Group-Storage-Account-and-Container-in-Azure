![265864955-76848602-0ddb-4e2d-8ad3-cc987b43c172](https://github.com/CollinsU99/Creating-Resource-Group-Storage-Account-and-Container-in-Azure/assets/124742607/4fb147f8-f2cb-4b30-b8fe-9b65024c48eb)


<h1>Creating Resource Group, Storage Account, and Container in Azure</h1>
In this lab, we will create a Resource Group in Microsoft Azure. Within the Resource Group, we will create a Storage Account, followed by a Container. We will then finish the tutorial by uploading a text file inside the container and then delete the text file.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Resource groups
- Storage accounts
- Containers
- Notepad

<h2>Operating Systems Used </h2>

Windows 10 (21H2) 

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Resource Group in Microsoft Azure.
- Create a Storage Account inside the Resource Group.
- Create a Container within the Storage Account.
- Upload text file inside the Container.
- Edit the the text file.

<h2>Deployment and Configuration Steps</h2>

To create a free Microsoft Azure subscription, you will need to use a valid email address and credit card. You will not be charged on your credit card and you will receive a free $200 worth of credit that will expire in 30 days if not used. After your account is created, you will have access to the Azure portal.

The Azure portal is a central hub for managing all of your Azure resources. It provides a graphical user interface (GUI) that makes it easy to create, manage, and deploy your Azure services. 

<p align="center">
<img src="https://i.imgur.com/s94Cisp.png" height="80%" width="80%" alt="img"/>
</p>

Your Azure portal will look like this. We will go ahead and create our resource group by clicking on "Resource groups" (1). You can also click on the search bar (2) and search for "resource group".

<p align="center">
<img src="https://i.imgur.com/PcSGyJ1.png" height="80%" width="80%" alt="img"/>
</p>

Click the "create" tab as shown above.

<p align="center">
<img src="https://i.imgur.com/tTsR6s7.png" height="80%" width="80%" alt="img"/>
</p>

Select the box to choose which subscription you want your Resource Group to go into. Select box (2) and name your Resource Group "RG-LAB-01. Box (3) let's you select the region you want your Resource Group to be created. We will go ahead and select "(US) West US 3"

NOTE: The region selection specifies where the metadata about the resources is stored.

<p align="center">
<img src="https://i.imgur.com/fDR5llT.png" height="80%" width="80%" alt="img"/>
</p>

Click the "Next: Tags >" tab

<p align="center">
<img src="https://i.imgur.com/HD0lipX.png" height="80%" width="80%" alt="img"/>
</p>

The "Tags" section helps us organize and manage our Azure resources. We will assign three individuals (Brian, James, and Michael) to the values (Finance, Accounting, and HR), respectively. Click "Next : Review + Create >".

<p align="center">
<img src="https://i.imgur.com/Kkrg0FZ.png" height="80%" width="80%" alt="img"/>
</p>

Our Resource Group has been validated, as shown in the image above. We will now create our Resource Group by clicking the tab "Create".

<p align="center">
<img src="https://i.imgur.com/mu2WXEv.png" height="80%" width="80%" alt="img"/>
</p>

You will get a notification confirming your Resource Group has been created

<p align="center">
<img src="https://i.imgur.com/dXaXQP5.png" height="80%" width="80%" alt="img"/>
</p>

Click the Search bar and search for "Storage accounts". Click "Storage accounts" as shown in box (2).

<p align="center">
<img src="https://i.imgur.com/BZRM0tT.png" height="80%" width="80%" alt="img"/>
</p>

We will now create our Storage Account by clicking "Create storage account".

<p align="center">
<img src="https://i.imgur.com/8pqzlM3.png" height="80%" width="80%" alt="img"/>
</p>

Select your Microsoft Azure Subscription as shown above, select the Resource Group "RG-LAB-01" we created earlier. Go ahead and name your Storage Account.

NOTE: Your Storage Account must be unique and contain only lower-case and numbers.

Box (4) is where we will select our region; select "(US) West US 3"

NOTE: Your region must be consistent with your Resource Group region.

Leave "Redundancy" as default. Click the "Review" tab.

<p align="center">
<img src="https://i.imgur.com/BzFzoKG.png" height="80%" width="80%" alt="img"/>
</p>

"Deployment is in progress" indicates that our Storage Account is being created.

<p align="center">
<img src="https://i.imgur.com/38TEIwm.png" height="80%" width="80%" alt="img"/>
</p>

"Your deployment is complete" indicates that our Storage Account has been created. Click "Go to resource" tab

<p align="center">
<img src="https://i.imgur.com/ohwuRdF.png" height="80%" width="80%" alt="img"/>
</p>

To create the Container, click the "Container" tab.

NOTE: Container is a virtual folder that can be used to store objects, such as images, videos, and documents

Now, click "Container", choose a name for your container, and leave box (4) as default. Click the "Create".

<p align="center">
<img src="https://i.imgur.com/zrjcuCn.png" height="80%" width="80%" alt="img"/>
</p>

You will get a notification as shown the image above, that your Storage Container has been created. You will also see the container we just created in the list of containers available.

<p align="center">
<img src="https://i.imgur.com/xMxS1WS.png" height="80%" width="80%" alt="img"/>
</p>

On your local computer, search for "Notepad" on the search bar. Open the Notepad application.

<p align="center">
<img src="https://i.imgur.com/b7w37c2.png" height="80%" width="80%" alt="img"/>
</p>

Type "Hello World" as the content of the text file, and click on "File".

<p align="center">
<img src="https://i.imgur.com/MMr3ls7.png" height="80%" width="80%" alt="img"/>
</p>

Click "Save" to save your text file

<p align="center">
<img src="https://i.imgur.com/No4nMXN.png" height="80%" width="80%" alt="img"/>
</p>

Click the Container we created to open it

<p align="center">
<img src="https://i.imgur.com/B0CVPu3.png" height="80%" width="80%" alt="img"/>
</p>

Click "Upload", and click box (2) to select the text file we just created "Hello World.txt". Click "Upload" to upload the text file

<p align="center">
<img src="https://i.imgur.com/xVSG2n1.png" height="80%" width="80%" alt="img"/>
</p>

The "Successfully uploaded blob(s)" notification indicates that the text file was uploaded successfully. You can see the uploaded text file in the image above.

<p align="center">
<img src="https://i.imgur.com/n03oVww.png" height="80%" width="80%" alt="img"/>
</p>

Select the text file, and click the three dots (...) at the far right of the text file

<p align="center">
<img src="https://i.imgur.com/TUq9FSX.png" height="80%" width="80%" alt="img"/>
</p>

After clicking the three dots (...), a small window will appear. click "View/edit"

<p align="center">
<img src="https://i.imgur.com/91FZmno.png" height="80%" width="80%" alt="img"/>
</p>

Let's edit the text file inside the "Container" by typing "My edit", as shown above. Click the "Save" tab to save the text file. To verify if the edits we made were successful, we will click the "Download" tab to download the edited text file to our local computer.

<p align="center">
<img src="https://i.imgur.com/dWUL90d.png" height="80%" width="80%" alt="img"/>
</p>

As shown above, the edits we made to the text file were successful.

<p align="center">
<img src="https://i.imgur.com/HZYswsq.png" height="80%" width="80%" alt="img"/>
</p>

Let's go ahead and delete the Resource Group we created to avoid getting charged. Click the search bar and search for "Resource group". From the list of options shown, click "Resource groups".

<p align="center">
<img src="https://i.imgur.com/8WTxgtU.png" height="80%" width="80%" alt="img"/>
</p>

Click the Resource Group we created "RG-LAB-01". Click the "Delete resource group" tab, enter your Resource Group name "RG-LAB-01" to confirm deletion. Then, click the "Delete" tab to delete the Resource group.

<p align="center">
<img src="https://i.imgur.com/dRw8YI5.png" height="80%" width="80%" alt="img"/>
</p>

You will get a notification confirming your Resource group deletion was successful, as shown in the image above.










