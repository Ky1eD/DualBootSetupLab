# DualBootSetupLab
<h1>Dual Booting Windows 11 and Kali Linux </h1>

 

<h2>Description</h2>
Project consists of making my laptop be able to boot in either Kali Linux or Windows 11 using a dual boot. This allows you to have two different OS's and files for each OS on one system
<br />


<h2>Languages and Utilities Used</h2>

- <b>Installing OS</b> 
- <b>Disk Management</b>
- <b>Rufus</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (22H2)
- <b>Kali Linux</b> (2023.3)
<h2>Walk-through:</h2>

<p align="center">
Download the OSI File for the OS you want to be able to dual boot into: <br/>
<img src="https://i.imgur.com/zZ23Nq7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Plug in USB drive you want to use and open the software Rufus:  <br/>
<img src="https://i.imgur.com/xt1vq04.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In Rufus Select your USB for the Device and correct ISO file for your boot selection and click start: <br/>
<img src="https://i.imgur.com/MFwuVC5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next on the devive you want to dual boot on. Go to Disk Management :  <br/>
<img src="https://i.imgur.com/pM2iHxU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next you need to shrink part of your drive to be able to install the OS and any files you need for it. I chose to give it 200gb, because I don't exatctly know what Im going to use it for yet but you should give it atleast 40gb of space:  <br/>
<img src="https://i.imgur.com/MFwuVC5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After you do that plug in the USB drive and restart and go into BIOS:  <br/>
<img src="https://i.imgur.com/pPsxrBw.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Make the USB drive your first boot option and turn off secure boot:  <br/>
<img src="https://i.imgur.com/uLN0eCA.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After you do that plug in the USB drive and restart and go into BIOS:  <br/>
<img src="https://i.imgur.com/pPsxrBw.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Then save it then leave bios to boot into the Kali Linux Install and go through the install proccess:  <br/>
<img src="https://i.imgur.com/kLjBteq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Lastly after installing the OS you wanted to dual boot into take out the USB drive and then you are all done:  <br/>
<img src="https://i.imgur.com/SZUla49.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
