# Sign in to Azure #
1. Sign in to the Azure portal
Create virtual machine
Enter virtual machines in the search.Under Services, select Virtual machines

![1st  ss](https://github.com/user-attachments/assets/930dad70-bdcb-419b-980f-42b5c530b65b)

2.In the Virtual machines page, select Create and then Azure virtual machine. The Create a virtual machine page opens.
![Screenshot 2025-04-22 110822](https://github.com/user-attachments/assets/71b73f29-9087-4f3a-bb41-52f16e1db2ce) 

3. Under Instance details, enter chandraVM for the Virtual machine name and choose Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 for the Image and choose the resource group. Leave the other defaults.
![Screenshot 2025-04-22 111446](https://github.com/user-attachments/assets/441a9521-76be-4b94-8a69-5e56fa39704d)

4. Choose Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 and under Administrator account, provide a username, such as azureuser and a password. The password must be at least 12 characters long and meet the defined complexity requirements.
![Screenshot 2025-04-22 111927](https://github.com/user-attachments/assets/519cb54d-6148-4864-a6eb-c37720e3f9e5)

5. Under Inbound port rules, choose Allow selected ports and then select RDP (3389) and HTTP (80) and SSH(22) from the drop-down.
![Screenshot 2025-04-22 112217](https://github.com/user-attachments/assets/38c8838a-27a9-48e9-bde9-972b29fafdf7)

6. Select the OS Disk type and choose the disk of standard ssd
![Screenshot 2025-04-22 112418](https://github.com/user-attachments/assets/1406fdd3-852d-4908-8959-0e66c2bb1de0)

7.Click on the networking part and leave it as default it will take the default name 
![Screenshot 2025-04-22 122009](https://github.com/user-attachments/assets/f3d37278-410b-411a-98ea-a650d50cff95)

8.Enable the autoshutdown mode to automatically shutdown the VM
![Screenshot 2025-04-22 122459](https://github.com/user-attachments/assets/cd542115-1629-45b1-8ec5-850c56eb67e0)
 
 
 9. Leave the remaining defaults and then select the Review + create button at the bottom of the page.
![Screenshot 2025-04-22 122813](https://github.com/user-attachments/assets/245a15d2-804a-4b66-9c69-9b9e6d25f331)
