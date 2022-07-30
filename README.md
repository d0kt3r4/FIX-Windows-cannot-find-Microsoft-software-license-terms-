# FIX-Windows-cannot-find-Microsoft-software-license-terms-
In this repo i will show you how to fix "Windows cannot find the Microsoft software license terms" issue when you want to create VM in VMware.

Proccess to Fix the Issue:
Step 1: Open you Vmware, then click to "Create a New Virtual Machine"
Step 2: Then choose "I will install the operating system later" option and click to Next
Step 3: For "Guest operation system" choose Microsoft Windows, For version for that choose "Windows Server 2019"
Step 4: Set you VM's name and Location then click to Next
Step 5: In "Specify Disk Capacity" section, set your VM's Disk Capacity (Min:50gb) then choose "Store virtual disk as a signle file" and click to Next
Step 6: Click to "Customize Hardware...", set RAM Memory to "2048" and set CPU to "2"and click to "Close" then click to "Finish"
Step 7: In main screen of VMware click to Your VM, then click to "Edit Virtual machine settings"
Step 8: Go to "CD/DVD (SATA)" tab,  then choose "USe ISO image file" option, click to "browse" and find your iso_file then click OK
Step 9: RUN your VM and you will see issue fixed successfully
