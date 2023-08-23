<p align="center">
<img src="https://images.credly.com/size/340x340/images/0bf0f2da-a699-4c82-82e2-56dcf1f2e1c7/image.png"/>
</p>

<h1>Install Software In a Linux Distrubution Lab 1 & 2</h1>
This tutorial outlines the Google Cybersecuirty Lab 1 & 2 and a break down of how to install software in a linux distrubtion.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- {If you have a Coursera account and are currently enrolled in the cert you may follow along}
- Coursera VM Lab

<h2>Operating Systems Used </h2>

- Windows 11</b>

<h2> Objectives</h2>

- Ensure that APT is installed  
- Install and uninstall the Suricata application
- Install the tcpdump application
- List the installed applications
- Reinstall the Suricata application

<h2>Steps</h2>

<p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/d64f577a-9c7f-4fb6-9682-de611f3b2cbe"/>
</p>
<p>
First you need to check that the APT application is installed then you can use it to manage the application all you have to do is type apt in the command line then press enter.
</p>
<br /> 


<p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/e0b890ed-c086-4b64-9225-35371ef68091"/>
</p>
<p>
Next we are going to install Suricata application go to the command line and type sudo apt install suricata.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/b5df4bbb-dbfa-484a-b42e-ff8888920b9b"/>
</p>
<p>
Next you need to type in y for yes then suricata will install and show a progression bar on the bottom left.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/22963969-0c8d-4217-8910-550690e7e3ec"/>
</p>
<p>
Next once the progression bar say 100%. We need to then see if suricata is installed type in suricata in the command line.
</p>
<br />
<p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/50a1ce4d-332d-4176-b666-f896f61b034a"/>
</p>
If you see the commands for suricata as shown in the image above then suricata is installed.
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/34f73107-2690-4d3e-b450-5bb409b82b9e"/>
</p>
Next we are going to uninstall suricata type in sudo apt remove suricata
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/f9f310c2-d4cd-4058-8432-9e70f2c72fcb"/>
</p>
Next you need to type in y to allow suricata to be uninstalled
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/6c77c348-9dbc-47e5-b98d-49b2b7189c63"/>
</p>
Next type suricata in the command line it should say the following "No such file or directory"
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/5b9edffa-ecf9-4178-ab0b-d937dc5efe27"/>
</p>
Next we are going to install the tcpdump application type in sudo apt install tcpdump in the command line
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/9f0bad26-fd60-470b-829a-04ab6218adda"/>
</p>
Next we are going to list out the installed applications type apt list --installed in the command line
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/694ef1a3-0ea6-4b96-a3c4-fdb359a74f58"/>
</p>
You can see tcpdump is installed in the image above
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/fec80dd8-4311-4193-99cf-5b15544e8f49"/>
</p>
Next we are going to install suricata again type in sudo apt install suricata in the command line 
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/90e279e0-b242-4bd5-9eed-a4317d375f6f"/>
</p>
Type y for yes again to allow installation
</p>
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/dfbd5292-a5a6-43b9-8bdd-a2e64373a15a"/>
</p>
We can see the list of all the applications type apt list --installed one more time in the command line
<img src="https://github.com/Jacobsushi54/InstallSoftwareInaLinuxDistrubution/assets/142194385/e84d2378-d06d-46ad-958a-78c22122d3fc"/>
</p>


