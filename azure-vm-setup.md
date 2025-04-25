# Quickstart: Create a Windows virtual machine in the Azure portal #
  1.   Sign in to the Azure portal

Enter virtual machines in the search.Under Services, select Virtual machines. In the Virtual machines page, select Create and then Azure virtual machine.Then Create a virtual machine page opens.
![Screenshot 2025-04-25 191922](https://github.com/user-attachments/assets/528e1483-b206-4eb0-96cd-c2c089f8de0e)

2. In the Virtual machines page, select Create and then Azure virtual machine. Then Create a virtual machine page opens.
![Screenshot 2025-04-22 110822](https://github.com/user-attachments/assets/71b73f29-9087-4f3a-bb41-52f16e1db2ce) 

3. Under project details select the subscription and resource group, and in project details enter vm name as chandraVM, and select the region as west US Leave the other defaults.
![Screenshot 2025-04-25 184648](https://github.com/user-attachments/assets/61a8dffd-b8d2-4bf8-9359-02bf424fb94e)

4. Choose Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 and under Administrator account, and select the size, provide a username, such as azureuser and a password. The password must be at least 12 characters long and meet the defined complexity requirements.
![Screenshot 2025-04-25 185635](https://github.com/user-attachments/assets/de1423a5-8309-439c-87dc-ad00f7762775)

5. Under Inbound port rules, choose Allow selected ports and then select RDP (3389) and click on the next Disk part.
![Screenshot 2025-04-25 190006](https://github.com/user-attachments/assets/23fa1555-9ecb-45ce-a8f5-acf6ff11864c)

6. Select the OS Disk type and choose the disk of standard ssd and go for the networking part.
![Screenshot 2025-04-25 190323](https://github.com/user-attachments/assets/c1205e44-9349-44db-a25d-861c595844dd)

7.Click on the networking part and leave it as default it will take the default name 
![Screenshot 2025-04-25 190528](https://github.com/user-attachments/assets/67e61164-7623-4b69-81e6-0bebd01643e8)


8.Enable the autoshutdown mode to automatically shutdown the VM and click on review + create. Leave the remaining defaults and then select the Review + create button at the bottom of the page
![Screenshot 2025-04-25 190732](https://github.com/user-attachments/assets/b155a2ac-217d-439a-9aef-7109207a157e)

9. After validation runs, select the Create button at the bottom of the page.
![Screenshot 2025-04-22 124053](https://github.com/user-attachments/assets/9c6d292d-0ac7-444d-9838-f6da4c6b042b)

10.Wait for the deployment to complete After deployment is complete, select Go to resource.
 ![Screenshot 2025-04-22 124613](https://github.com/user-attachments/assets/e1e6da8e-299a-48bb-b13d-3279ce90064b)
 ![Screenshot 2025-04-22 124730](https://github.com/user-attachments/assets/adf75961-1eca-467e-bc42-e4e6ac9b84d7)

# Connect to virtual machine #
 11. On the overview page for your virtual machine, select the Connect > RDP.

![Screenshot 2025-04-22 124952](https://github.com/user-attachments/assets/81775f3f-0bfd-45a0-9784-acc9364be77d)

12. In the Connect with RDP tab, keep the default options to connect by IP address, over port 3389, and click Download RDP file.
![Screenshot 2025-04-22 125044](https://github.com/user-attachments/assets/71f87b86-6808-42ca-ab79-cf9f09493b40)

13. Open the downloaded RDP file and click Connect when prompted.
In the Windows Security window, select More choices and then Use a different account. Type the username as localhost\username, enter the password you created for the virtual machine, and then click OK.
![Screenshot 2025-04-22 125708](https://github.com/user-attachments/assets/5fd7522a-291c-4aa4-9967-1ee39faf706c)
![Screenshot 2025-04-22 125759](https://github.com/user-attachments/assets/cb624dd6-bcbd-4df1-973d-df5443d5ba01)

14. You may receive a certificate warning during the sign-in process. Click Yes or Continue to create the connection.
![Screenshot 2025-04-22 125839](https://github.com/user-attachments/assets/8c091524-e314-4e68-8a31-a1ba9e8eb99e)

15.  # View the welcome page #
Access Your Windows VM
You are now connected to your Azure Windows VM via Remote Desktop!You can now install software, configure settings, or run applications.
