<p align="center">
<img src="https://i.imgur.com/zpBa6HB.png" alt="osTicket logo"/>
</p>

<h1>VirtualBox - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of Oracle VirtualBox.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install Oracle VirtualBox](https://youtu.be/9lCYtj7ceIE)

<h2>Environments and Technologies Used</h2>

- Oracle VirtualBox Type II Hypervisor

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>List of Prerequisites</h2>

- Laptop/PC
  - Operating Systems:
    - Windows hosts (64-bit):
      - Windows 8.1, 10, 11 21H2
      - Windows Server 2012, 2012 R2, 2016, 2019, 2022
    - MacOS hosts (64-bit):
      - 10.15 (Catalina)
      - 11 (Big Sur)
      - 12 (Monterey)
    - Linux hosts (64-bit):
      - Ubuntu 18.04 LTS, 20.04 LTS and 22.04
      - Debian GNU/Linux 10 ("Buster") and 11 ("Bullseye")
      - Oracle Linux 7, 8 and 9
      - CentOS/Red Hat Enterprise Linux 7, 8 and 9
      - Fedora 35 and 36
      - Gentoo Linux
      - SUSE Linux Enterprise server 12 and 15
      - openSUSE Leap 15.3
- SSE2 (Streaming SIMD Extensions 2) support is required for host CPUs
- Microsoft Visual C++
- Python core / win32api (optional)

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/BLEiEBw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to https://www.virtualbox.org and click on the 'Download VirtualBox 7.0' icon
</p>
<br />

<p>
<img src="https://i.imgur.com/ZYgFDfI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the corresponding host platform.  In other words, which operating system (OS) are you running on your host (physical) machine?
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox Extension Pack.  Does not matter which OS you're running.
</p>
<br />

<p>
<img src="https://i.imgur.com/VFSCsOk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to your Control Pannel and select Programs and Features
</p>
<br />

<p>
<img src="https://i.imgur.com/LTvJsWT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Look for Microsoft Visual C++
</p>
<br />

<p>
<img src="https://i.imgur.com/FSBsvkL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If you do not have Microsoft Visual C++, then go to https://www.google.com and search for Microsoft Visual C++
</p>
<br />

<p>
<img src="https://i.imgur.com/bAYfHLG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the link that that shows Latest supported Visual C++ Redistributable downloads and select X64.
</p>
<br />

<p>
<img src="https://i.imgur.com/uqW4fqR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have downloaded C++,launch the .exe file in order to install it.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZzVqSPM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This step is optional.  If you don't have Python, go to https://www.python.org and hover your cursor over the 'Downloads' section and select 'Download Python 3.11.1
</p>
<br />

<p>
<img src="https://i.imgur.com/5qwLj8R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Launch the setup wizard for Python. MAKE SURE TO SELECT 'Add pythor.exe to PATH'
</p>
<br />

<p>
<img src="https://i.imgur.com/k6bF6Pl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After successful installation of Python, launch your command prompt (CMD) and run it as an Administrator
</p>
<br />

<p>
<img src="https://i.imgur.com/ttaxygO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In CMD, type the following command and press enter: pip install pywin32
</p>
<br />

<p>
<img src="https://i.imgur.com/G5s94Xm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If successful, you will get a reply that states: 'Succesfully installed pywin32-.05.  If unable to install, make sure you're running as an administrator.
</p>
<br />

<p>
<img src="https://i.imgur.com/0Eao4JG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you will launch the setup wizard for VirtualBox.  The application file will be in your 'Downloads' folder
</p>
<br />

<p>
<img src="https://i.imgur.com/UOdm7U9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next four steps will be to select 'Next'
</p>
<br />

<p>
<img src="https://i.imgur.com/sCTxEWv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here you will select the file loacation that you want VirtualBox to be saved in.  Select 'Next'
</p>
<br />

<p>
<img src="https://i.imgur.com/MEC1bsS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Network Interface Warning.  Select 'Yes'
</p>
<br />

<p>
<img src="https://i.imgur.com/SXcbcip.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The installation wiard is now ready to begin installation.  Select 'Install'
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox E
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox Extension Pack.  Does not matter which OS you're running.
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox Extension Pack.  Does not matter which OS you're running.
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox Extension Pack.  Does not matter which OS you're running.
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox Extension Pack.  Does not matter which OS you're running.
</p>
<br />

<p>
<img src="https://i.imgur.com/uMexifV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VirtualBox Extension Pack.  Does not matter which OS you're running.
</p>
<br />
