<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

ga('create', 'UA-XXXXX-Y', 'auto');
ga('send', 'pageview');
</script>
# Starting-with-Windows-11
Installation guide on how to use and get started with Windows 11
# Installation
- We will be using a VM (VMware Workstation Player 16)  and to start hosting Windows 11 on our system
- We will be using ISO files from Microsoft to run Windows 10 on our Virtual Machine

> **_Warning! Many sites claim to have the ISO of Windows 11 ! There is no official ISO of Windows 11 from Microsoft_**
## Hardware requirements (Host)
- Processor:
1 gigahertz (GHz) or faster processor or System on a Chip (SoC)
- RAM: 
1 gigabyte (GB) for 32-bit or 2 GB for 64-bit 
- Hard drive space:
16 GB for 32-bit OS 32 GB for 64-bit OS
- Graphics card:
DirectX 9 or later with WDDM 1.0 driver
- Display:
800x600
- Internet Connection:
Internet connectivity is necessary to perform updates and to download and take advantage of some features. Windows 10 Pro in S mode, Windows 10 Pro Education in S mode, Windows 10 Education in S mode and Windows 10 Enterprise in S mode require an internet connection during the initial device setup (Out of Box Experience or OOBE), as well as either a Microsoft account (MSA) or Azure Activity Directory (AAD) account. Switching a device out of Windows 10 in S mode also requires internet connectivity. Learn more about S mode here.
## Setting up your Host
- Click 'Settings' in your Host Computer
- Go to Privacy>Diagnostics and Feedback and select Optional Diagnostic Data
- Go back and click on 'Update and Security'
- Register yourself for the 'Windows Insider Programme' using your Microsoft E-mail
- You will see a screen as shown below and Click on 'Dev Channel'
![image](https://user-images.githubusercontent.com/86183161/125780318-e479c5de-2fab-4687-ad93-640d9eeee46c.png)
> **_Warning! You will be asked to restart your system! DO NOT click on Restart Now,click on 'Restart Later'_**
- Confirm and you are now a Windows Insider!
## Installing the ISO file
- Visit the link 'https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewiso?wa=wsignin1.0'
- ![image](https://user-images.githubusercontent.com/86183161/125782239-be217531-22bc-4a7c-bc39-5d9f5b466e53.png)
- On drop down select 'Windows 10 Insider Preview Enterprise (Dev Channel)-Build 21354
- Select English as your product language
- Click on 64 bit and start downloading the ISO file
## Installing your VM-
- Open Chrome and visit the link 'https://www.vmware.com/products/workstation-player.html' and click on Download Now
- Select Version 16 and click on 'Go to Downloads' of VMware Workstation Player 16
- Download the VM for either Linux or Windows depending on your preference (64-bit is only allowed)
- Once Downloaded, you shall open the Software and will see a screen as shown below-
 ![image](https://user-images.githubusercontent.com/86183161/125778944-b683ac9c-af2f-4142-8905-977c2932f48c.png)
- Click on 'Create a New Virtual Machine' 
- Click on ISO and point the URL to the location of your ISO
- VMware will detect the OS you have selected as Windows 10 Enterprise(64bit)
- Click next 
- You will see a page which asks for a product key which you can leave blank
- Select the version of Windows as 'Windows 10 Pro'
- Type the name of your Windows
- A popup will ask whether you want to install Windows without a product key, click 'Yes'
- Type the name of your Virtual Machine and select the place in your drive and click next
- You will be asked to enter the maximum disk size-100GB should be enough
- 'Split Virtual Disk into Multiple Files' should be selected
- On next you will be shown the hardware of your VM click on 'Customise Hardware'
- Select 6GB of memory and 6 processors should be enough
- Click 'Finish' to finish set up your VM
## Installing Windows 11 on your VM-
- Sign in with the Microsoft Account of your host desktop on your VM
- Click 'Settings' in your VM
- Go to Privacy>Diagnostics and Feedback and select Optional Diagnostic Data
- Go back and click on 'Update and Security'
- Register yourself for the 'Windows Insider Programme' using your Microsoft E-mail
- Go to Updates and Security
- Scan for updates and you should see the Windows 11 Update
