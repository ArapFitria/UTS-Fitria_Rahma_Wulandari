*UTS SAS** 

**Nama  : Fitria Rahma Wulandari**

**NIM     : 1202190045**

1. **Download ISO Installer Windows Server 2022**

   - Download at the following link : https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022 

   - Select "Download the ISO" and click "Continue"

     ![](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\1.PNG)

     

   - Fill in personal data according to the display, then check the checkbox and click "Continue"

     ![](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\2.PNG)

     

   - Select the desired language and click "Download"

     ![](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\0.PNG)

     

   - Wait until the ISO has downloaded

     

2. **a. Windows Server 2022 Installation**

   - Open VirtualBox and click "Baru"

     ![](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\3.PNG)

     

   - Enter the name of the machine and type of system to use and click "Lanjut"

     ![](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\4.PNG)

     

   - Specify the memory size and click "Lanjut"

     ![5](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\5.PNG)

   

   - Choose "Buat hard disk virtual sekarang" and click "Lanjut"

     ![6](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\6.PNG)

     

   - Choose "VDI (VirtualBox Disk Image)" and click "Lanjut"

     ![7](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\7.PNG)

     

   - Choose "Dialokasikan secara dinamik" and click "Lanjut"

     ![8](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\8.PNG)

   

   - Choose "Dialokasikan secara dinamik" and click "Buat"

     ![9](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\9.PNG)

     

   - After Windows Server 2022 is created, now go to "Pengaturan"

     ![10](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\10.PNG)

     

   - Select "Jaringan" menu, select "Adaptor Ter-bridge", and click "OK"

     ![11](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\11.PNG)

     

   - Back to the initial view and click "Mulai"

     ![10](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\10.PNG)

     

   - Select the ISO downloaded 

     ![12](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\12.PNG)

     

   - Click "Mulai"

     ![13](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\13.PNG)

     

   - Wait until it looks like this, then choose language, time and currency format, and keyboard or input method. then choose "Next"

     ![14](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\14.PNG)

     

   - Click "Install Now"

     ![15](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\15.PNG)

     

   - Click "Next"

     ![16](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\16.PNG)

     

   - Check the Checkbox and click "Next"

     ![17](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\17.PNG)

     

   - Choose "Custom : Install Microsoft Server Operating System only (advanced)"

     ![18](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\18.PNG)

     

   - Click "Next"

     ![19](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\19.PNG)

     

   - Then wait until the installation is complete

     ![20](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\20.PNG)

     ![21](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\21.PNG)

     

   - Creat new password

     ![22](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\22.PNG)

     

   - Then press Ctrl + Alt + Delete to unlock

     ![23](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\23.PNG)

     

   - Sign in with the password you created

     ![24](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\24.PNG)

     

   - Go to menu Deice, then choose Insert Guest Additions CD Image

     ![25](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\25.png)

     

   - Go to File Exploler and choose Vbox Windows Additions

     ![26](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\26.PNG)

     

   - Click "Next"

     ![27](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\27.PNG)

     

   - Click "Next"

     ![28](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\28.PNG)

     

   - Then, Install

     ![29](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\29.PNG)

     

   - Choose reboot now and click "Finish"

     ![30](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\30.PNG)

     

   - Your Windows Server 2022 will be reboot

     ![31](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\31.PNG)

     

   - Sign in again with your password

     ![32](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\32.PNG)

     

   - Run “winver” to validate the installed edition of Windows Server

     ![33](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\33.PNG)

   

   

   **b. Active Directory Domain Service Installation**

   - Before doing the installation, we change the computer name first by going to windows powershell. Then type "rename-computer -Newname Server2022"

     ![34](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\34.PNG)

     

   - Go to the "Server Manager" menu. Then select the “Manage” option, followed by clicking “Add Roles and Features”. Then click "Next".

     ![35](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\35.PNG)

     

   -  Select “Role-based or feature-based installation”. Then “Next”

     ![36](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\36.PNG)

     

   - Click “Select a server from the server pool”. Then "Next"

     ![37](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\37.PNG)

     

   - Next, put a check mark in the “Active Directory Domain Services” box.

     ![38](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\38.PNG)

     

   -  Then appears a brief description of AD DS and how it works. Then click "Add Features".

     ![39](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\39.PNG)

     

   - Then check the “Group Policy Management” box and press the “Next” button.

     ![40](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\40.PNG)

     
   
   - Click "Next"
   
     ![41](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\41.PNG)
   
     
   
   - Click "Install"
   
     ![42](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\42.PNG)
   
     
   
   - Wait until the installation process is complete then configure AD DS, and done.
   
     ![43](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\43.PNG)
   
   
   
   
   
   **c. DNS Server Installation**
   
   - Go to the "Server Manager" menu. Then select the “Manage” option, followed by clicking “Add Roles and Features”. Then click "Next" and "Add Features". 
   
     ![44](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\44.PNG)
   
     
   
   - Click "Continue"
   
     ![45](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\45.PNG)
   
   
   
   
   
   **d. Net Framework 3.5 Installation**
   
   - Check in checkbox ".NET Framework Features", then click "Next"
   
     ![46](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\46.PNG)
   
     
   
   - Click "Next"
   
     ![47](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\47.PNG)
   
     
   
   - Click "Install"
   
     ![48](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\48.PNG)
   
     
   
   -  Wait until the installation process is complete
   
     ![49](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\49.PNG)
   
     
   
   - And the installation is complete
   
     ![50](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\50.PNG)
   
   
   
   
   
   **e. Promote Server to a Domain Controller**
   
   - Go to CMD, than type sconfig
   
     ![51](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\51.PNG)
   
     
   
   - Choose number 8 by typing
   
     ![52](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\52.PNG)
   
     
   
   - Choose number 1 by typing
   
     ![53](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\53.PNG)
   
     
   
   - Choose number 8 by typing
   
     ![54](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\54.PNG)
   
     
   
   - Then type "S" to ststic IP configuration.
   
     ![55](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\55.PNG)
   
     
   
   - Then CMD will process it
   
     ![56](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\56.PNG)
   
     
   
   - Setting the IP Address Server-ADDS and pointing the DNS to the static IP address used. and click "OK"
   
     ![57](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\57.PNG)
   
     
   
   - Click “Promote this server to a domain controller for AD DS configuration
   
     ![58a](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\58a.png)
   
     
   
   - Select “Add a new forest” and enter the domain name that will be used in the Root Domain Name.
   
     ![59](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\59.PNG)
   
     
   
   - Select “Windows Server 2016” at the functional level, put a check mark on “Domain Name System (DNS) server” and “Global Catalog (GC)”. Then create password.
   
     ![60](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\60.PNG)
   
     
   
   - Click "Next"
   
     ![61](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\61.PNG)
   
     
   
   - Fill in The NetBIOS domain name according to the domain name used.
   
     ![62](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\62.PNG)
   
     
   
   - Click "Next"
   
     ![63](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\63.PNG)
   
     
   
   - Click "Next"
   
     ![64](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\64.PNG)
   
     
   
   - Click "Install"
   
     ![65](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\65.PNG)
   
     
   
   - Wait until the installation is complete, and the Windows Server 2022 will be reboot
   
     ![66](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\66.PNG)
   
     
   
   - Sign in with your password administrator
   
     ![67](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\67.PNG)
   
     
   
   - To check the configuration results, open cmd and type “netdom query fsmo”
   
     ![68](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\68.PNG)
   
     
   
   - And the process is successful
   
     ![69](D:\KULIAH\.tugas kuliah\sem 5\SAS\UTS win server 2022\dokumentasi\69.PNG)
   
     
   
     
   
     
   
     
   
     

