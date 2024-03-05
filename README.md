# osTicket-Prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>
Step 1) Create a resource group in Azure
<p></p>
<p>

 <img width="668" alt="1" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/c2688209-0a04-4e02-bbf1-211759e08a14">

 

</p>
<p>
Step 2) Fill in the necessary information that is in the pink box after, click "review & create" which is located in the green box
</p>
<br />

<p>
<img width="799" alt="2" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/f641e297-cdaa-472a-adc2-47096212552e">

</p>
<p>
Step 3) After your resource group has been created which you can see in the pink box you will create a resource by clicking the "Create Resource".
</p>
<br />

<p>
<img width="1422" alt="3" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/ea7c19b2-21cb-46b3-9557-946c1c513d55">

</p>
<p>
Step 4) Now that your resource group is set up we will add the resource "virtual machine" to the group. Search for "virtual machine" in the pink box and click the virtual machine located in the green box
</p>
<br />

<p>
<img width="1422" alt="4" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/1afc32fc-5b36-4c03-b97e-9fd530c58ded">

</p>
<p>
Step 5) Fill in the information located in the pink boxes, check the first green box then proceed by clicking the "review and create" 
</p>
<br />
<img width="845" alt="5" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/8260b840-5476-455c-a8b8-51f14938689d">
<img width="765" alt="6" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/0a657cfd-eb8d-4417-bb75-7d58f62ac3e8">
<img width="494" alt="7" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/5014a64f-b9c2-4b69-9b94-8d8cd95993ec">
<p>
<p></p>

Step 6) Wait for your VM to set up. This process shouldn't take longer than 10 minutes

</p>

<img width="1108" alt="8" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/33c5ef31-826d-4cc1-9dce-523cf25dfc08">
<p>
 
Step 7) If you're using a MacBook you'll need to download Microsoft Remote Desktop from the app store to connect to your VM
<p>
<p>
<img width="1143" alt="Screenshot 2024-02-19 at 4 20 46 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/d345b45b-6fd4-4fbd-bc3a-1c8f1635dafb">
<p>
Step 8) Now head back to the VM you created and copy the IP address
<p>
 <img width="1312" alt="Screenshot 2024-02-19 at 5 39 57 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/161ee6a3-9d12-4d81-b61a-ef208fb35d41">

</p>
Step 9) Now insert the IP address into the slot titled "PC Name" Continue by clicking add. Your username and password will be the same as the VM you set up
<p>
 <p></p>
<img width="551" alt="Screenshot 2024-02-19 at 5 44 17 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/f621397b-a8d5-49c0-b79f-2c8ce18b97ac">
<img width="598" alt="Screenshot 2024-02-19 at 5 47 32 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/578e0b45-f90c-438c-92ad-1063227f4389">
<p>
Step 10) Now your VM should be opening when you land on a page like this check NO and move forward. Our next steps will be to install/Enable IIS with CGI
</p>
<img width="1157" alt="step 9" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/f2c42967-1893-469f-a6aa-67f76bcf065c">
<p>
Step 11) Open the control panel then go to programs and check the IIS file turn on CGI then make sure all common HTTP features are on
<p>
 <img width="1136" alt="Screenshot 2024-02-27 at 1 48 02 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/5e74a481-dbb2-480f-8b8a-ab4e5adb8f4f">
<img width="1145" alt="Screenshot 2024-02-27 at 1 52 14 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/7920a384-a015-46d0-a8af-78290426602e">
<img width="1148" alt="Screenshot 2024-02-27 at 1 53 07 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/6ad230f3-a3a5-4fa1-8136-0e145bf26bae">
<img width="1145" alt="Screenshot 2024-02-27 at 1 54 12 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/5d034c60-2d00-4e0a-b4a3-00ed9b965849">
<p>
Step 12) Download and install PHP manager for IIS and rewrite module
</p>
<img width="518" alt="Screenshot 2024-02-27 at 3 24 07 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/377a9da3-5efe-4f11-995a-f376c806f02d">
<img width="516" alt="Screenshot 2024-02-27 at 3 35 57 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/8c6fcaa8-3a35-4f87-a014-758015731483">
<p>
Step 13) Create the directory C/PHP download PHP 7.3.8 and unzip the contents into the C file you created
</p>
<img width="1146" alt="Screenshot 2024-02-27 at 4 09 18 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/1aa5b6c4-078b-49ea-af8f-0ffbfb6e62ba">
<img width="1146" alt="Screenshot 2024-02-27 at 4 10 10 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/9634b1ee-8ed3-4af8-afe2-8b32e6dca0fc">
<img width="834" alt="Screenshot 2024-02-27 at 4 42 10 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/f4c169e7-bead-4035-8c15-19081b710574">
<img width="625" alt="Screenshot 2024-02-27 at 4 44 57 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/7dcc70a6-7cab-45d6-822e-da0b80b5b3e7">
<p></p>
Step 14) Now download and install vc redist along with MySQL when setting up Mysql you'll need to click standard configuration along with creating a password
<p></p>
<img width="502" alt="Screenshot 2024-02-27 at 5 18 44 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/481a6b59-4d90-4d53-91de-c49a9225dee6">
<img width="512" alt="Screenshot 2024-02-27 at 5 24 49 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/3309c292-ba55-4077-9330-872c8a6e83c2">
<img width="521" alt="Screenshot 2024-02-27 at 5 27 45 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/583c5c27-e7af-49b0-84cf-0f5b20a779fa">
<img width="525" alt="Screenshot 2024-02-27 at 5 40 06 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/0249f54c-b245-435a-8c6d-80541bb92400">
<img width="510" alt="Screenshot 2024-02-27 at 5 43 00 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/4728eba6-0aef-42c2-9c99-807bf54d1cdc">
<p>
Step 15) From here we will open IIS as an admin and do some configuration to install osTicket. Click the PHP manager after you'll need to register a new PHP version and then restart the web server.
</p>
<img width="773" alt="Screenshot 2024-02-27 at 8 21 43 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/dd285863-ddab-4360-a37c-f1f5c409b491">
<img width="1063" alt="Screenshot 2024-02-27 at 8 25 47 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/bf04db28-09e4-46d9-9070-64237c2e7137">
<img width="1062" alt="Screenshot 2024-02-27 at 8 32 30 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/35b5f798-78ae-4a78-94bc-348be2f77842">
<p>
Step 16) Now download osTicket once downloaded you'll need to move the "upload" file into your wwwwRoot folder that is located on the C drive, then rename the "upload" folder to osTicket
</p>
<img width="698" alt="Screenshot 2024-02-27 at 8 58 03 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/8154866a-22e3-4206-92ec-7f4832a08d94">
<img width="455" alt="Screenshot 2024-02-27 at 8 57 28 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/a487fa73-5b86-40ec-9f51-469f00e3ba3f">
<img width="640" alt="Screenshot 2024-02-27 at 9 06 25 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/d8e6f37d-609c-4999-8d75-b9084f043ebf">
<p>
Step 17) Head back to IIS to continue click the site tab then click osTicket then on the far right you'll be looking for texts that read "browse 80 http" click to open osTicket
</p>
<img width="1114" alt="Screenshot 2024-02-27 at 9 11 34 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/83c9674d-5d4e-45f6-8fc2-584f0348adee">
<img width="859" alt="Screenshot 2024-02-27 at 9 13 38 PM" src="https://github.com/Zakari23/osticket-prereqs/assets/158666482/66f6cb47-1a6e-4510-84f4-1b9ebc1095f2">
