# Azure-Free-Account-Setup-Guide-Create-VM-RDP-Remote-Access-from-Home-PC-
Using Outlook.com Account  |  Free Tier  |  Step-by-Step 
Architecture Diagram 
The diagram below shows the full connection path from your home PC to the Azure Virtual Machine via RDP: 
<img width="1020" height="597" alt="image" src="https://github.com/user-attachments/assets/25c1cf16-c491-42fd-bd8a-507612f6737c" />
 Step 1: Create a Free Outlook.com Account 
•	Go to outlook.com and click Create free account 
•	Choose a username (e.g. yourname@outlook.com) — do NOT use your Everestit account 
•	Set a strong password and complete phone/email verification 
•	Keep this account solely for Azure billing & access 
<img width="975" height="349" alt="image" src="https://github.com/user-attachments/assets/193b67cd-5cf5-435e-a06b-f7e022e546e1" />
<img width="975" height="264" alt="image" src="https://github.com/user-attachments/assets/6888bc4a-c493-45c2-9bdc-c0a34b478e22" />
Step 2: Sign Up for Azure Free Account 
•	Visit: azure.microsoft.com/free 
•	Click Start free and sign in with your new Outlook.com account 
•	You receive $200 credit (30 days) + 12 months of free services 
•	Enter a credit card for identity verification only — no charge during free tier 
•	Complete phone verification to activate your subscription 
<img width="703" height="235" alt="image" src="https://github.com/user-attachments/assets/c3bd5cc6-3a93-4b1b-868f-f3133107c62b" />
<img width="629" height="292" alt="image" src="https://github.com/user-attachments/assets/ad516034-7645-451c-86bf-17eecdeb1c7a" />
Step 3: Create a Virtual Machine in Azure Portal 
Navigate to portal.azure.com after signing in, then follow these settings
<img width="975" height="230" alt="image" src="https://github.com/user-attachments/assets/16e99118-88ac-4a7f-a832-4d85c2ceca24" />
<img width="975" height="183" alt="image" src="https://github.com/user-attachments/assets/e7a6ba4f-8009-4172-a4fd-b6ad4d96517d" />
Click Review + Create, then Create — deployment takes ~2–3 minutes 
<img width="664" height="366" alt="image" src="https://github.com/user-attachments/assets/60319bfc-672d-4262-8550-694ca9ce4e5d" />
After resource group create virtual network 
<img width="975" height="277" alt="image" src="https://github.com/user-attachments/assets/7f5818ed-0b75-4fb4-8d82-6da230d64787" />
<img width="938" height="246" alt="image" src="https://github.com/user-attachments/assets/797e201c-f289-4ae9-966d-ef12dd5a1ffd" />
<img width="975" height="282" alt="image" src="https://github.com/user-attachments/assets/005ca045-a654-4264-956f-202c6cad6c51" />
Create virtual Machine process and choose virtual machune 
<img width="975" height="269" alt="image" src="https://github.com/user-attachments/assets/b88363e0-b244-4954-a3c9-e6b2e6b1e334" />
<img width="901" height="418" alt="image" src="https://github.com/user-attachments/assets/0df8bbeb-b7f5-4971-8afb-fd61fe92f320" />
Deployment in Process 
<img width="921" height="248" alt="image" src="https://github.com/user-attachments/assets/62453f9a-7511-4c32-99b2-0b8ca4cd8068" />
Now ready to work with virtual machine 
<img width="947" height="211" alt="image" src="https://github.com/user-attachments/assets/3c8a9069-a908-48ac-ad25-cc760ccc89a7" />
Step 4: Get the Azure Public IP Address 
Copy the Public IP address (format: 20.x.x.x or 52.x.x.x) 
<img width="815" height="302" alt="image" src="https://github.com/user-attachments/assets/25849ee4-a6a1-4e3b-ab93-f7eda5abb842" />
Static Ip create
<img width="818" height="310" alt="image" src="https://github.com/user-attachments/assets/46e599d1-0e80-43eb-a743-082f1849e5d5" />
<img width="876" height="385" alt="image" src="https://github.com/user-attachments/assets/a0270f45-32f6-4770-b2e7-4da4b2ddae37" />
Remote Desktop (RDP) from Your Home PC  On Windows
•	Press Win + R, type mstsc, press Enter 
•	In the Computer field enter the Azure Public IP (e.g. 20.115.x.x) 
•	Click Connect, enter your VM username and password 
•	Accept the certificate warning — you are now inside Azure! 
<img width="975" height="329" alt="image" src="https://github.com/user-attachments/assets/2d68536a-afc1-4995-b5f5-87ccc453a373" />
Type Mstsc in your pc search bar 
<img width="701" height="359" alt="image" src="https://github.com/user-attachments/assets/0fa12f75-bf5c-46bb-8d96-987112d2d5e8" />
Ask Credentials 
<img width="704" height="276" alt="image" src="https://github.com/user-attachments/assets/2f2759c7-180b-46cb-849d-3493bb1f07b8" />
Now connect Myadmin 
<img width="678" height="453" alt="image" src="https://github.com/user-attachments/assets/b86a1718-c481-4548-a780-a5795e4785d3" />
Download RDP: 
•	Download Microsoft Remote Desktop from the App Store 
<img width="784" height="173" alt="image" src="https://github.com/user-attachments/assets/e1a889fd-a335-4b32-9fa1-a263c44308c0" />
Download RDP File 
<img width="786" height="345" alt="image" src="https://github.com/user-attachments/assets/45ca795b-6a28-41a3-bf84-0deacb991755" />
•	Add PC → enter the Azure Public IP → Connect 
<img width="775" height="215" alt="image" src="https://github.com/user-attachments/assets/6046d71b-3767-4776-a08a-34e47e275008" />
<img width="678" height="452" alt="image" src="https://github.com/user-attachments/assets/9e5c29a9-452f-4fcc-8eb3-7aa6689f861e" />
<img width="678" height="452" alt="image" src="https://github.com/user-attachments/assets/553cd668-209c-41e1-a3a1-53e4d4f362d8" />
Security Best Practices 
•	Restrict RDP to your home IP only in the NSG Inbound Rules (Source: My IP Address) 
•	Enable Auto-Shutdown under VM → Operations → Auto-shutdown to save free credits 
•	Use a strong password; consider enabling Azure Bastion for passwordless access 
•	Monitor costs in Cost Management + Billing — stay within free tier limits 
•	Never expose RDP (port 3389) to 0.0.0.0/0 on a production machine 
Quick Reference Checklist 
•	☐  Outlook.com account created (not Everestit) 
•	☐  Azure Free subscription activated 
•	☐  Resource Group (MyRG) created in West US 2 
•	☐  Windows Server 2022 VM (MyVM) deployed — B1s size 
•	☐  NSG Inbound Rule: TCP 3389 allowed 
•	☐  Public IP noted (20.x.x.x) 
•	☐  RDP connection tested from home PC (mstsc.exe) 
•	☐  Auto-Shutdown enabled on VM 
•	☐  NSG restricted to home IP for security 



