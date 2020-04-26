# Installing Docker on Windows Pro

#### **Installing Docker on Windows Pro**

**Step 0.**

Make sure you have [Windows10 Pro](https://support.microsoft.com/en-us/help/13443/windows-which-version-am-i-running)**.**

**Step 1.**

[Download Docker](https://download.docker.com/win/stable/Docker%20Desktop%20Installer.exe). Installing is different for everyone depending on the motherboard manufacturer. Entering BIOS may be required to change "virtualization" to "enabled".   
****\(What is [Docker](https://docs.docker.com/docker-for-windows/install/)?\)

You will need "[Virtualization](https://docs.docker.com/docker-for-windows/troubleshoot/#virtualization-must-be-enabled)" enabled, which you can check in the Taskmanager.

![virtualization](https://user-images.githubusercontent.com/26490734/79853838-dba5de80-83c8-11ea-9fbf-d640c4bb1980.png)

**Step 2.**

Change Docker File sharing settings and manually create a folder called **"prysm"** in that specific directory.   
In this case the folder "prysm" is created in C:\prysm.  
  
Picture below for clarification.

![dockerWindows](https://user-images.githubusercontent.com/26490734/79551080-7c2e9280-8099-11ea-8886-0b739b7d12c1.png)

**Step.4**

Change Docker's default memory to 4GB

![dockerMemory](https://user-images.githubusercontent.com/26490734/80192514-9aefd480-8617-11ea-93b4-e709a988a5c0.png)
