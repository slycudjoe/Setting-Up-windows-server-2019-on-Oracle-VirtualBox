<h1>Setting Up windows server 2019 on Oracle VirtualBox</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Microsoft Windows Server is a popular operating system running in almost every company. Windows Server 2019 is a powerful server operating system, and VirtualBox is a popular virtualization platform. In this Home Lab, I will walk you through a step by step process on how to experiment with Windows Server configurations on Oracle VirtualBox.
<br />

<h2>Software & Environment Used</h2>

- <b>A PC or laptop with hardware virtualization support</b>
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Windows Server 2019 ISO file](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019)


- <h2>Program walk-through:</h2>

- <h2>Step 1: Create a New Virtual Machine:</h2>
<p align="left">
1. Open VirtualBox and click on “New” to create a new virtual machine. <br/>
2. Name your VM e.g., Windows Server VM, and select “Microsoft Windows” as the Type, and “Windows(64-bit)” as the version.<br/>
<img src="https://imgur.com/A5DJqEj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Allocate memory (RAM) to your virtual machine. At least 2GB is recommended for Windows Server 2019.  <br/>
<img src="https://imgur.com/fbnwC4t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
4. Create a new virtual hard disk. Ensure it’s large enough to accommodate your server needs. A 50gb disk is a good starting point. <br/>
<img src="https://imgur.com/JJatAhL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
5. Click on finish  <br/>
<img src="https://imgur.com/aAdqdtS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 - <h2>Step 2: Configure Virtual Machine Settings:</h2>
1. Select your newly created virtual machine and click on “Settings”.  <br/>
<img src="https://imgur.com/KQ4d8ti.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Under the “General” tab, go to the “Advanced” tab and change the "shared clipboard" & "Drag n Drop" to bidirectional <br/>
<img src="https://imgur.com/oA1scCJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Under the "Network" tab, go to the "Adapter 2" to enable it, Attached to, select "Internal Network", since Adapter 1 will be connected to our home internet <br/>
<img src="https://imgur.com/UiQjaEa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

