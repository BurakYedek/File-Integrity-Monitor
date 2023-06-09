# File-Integrity-Monitor

<h2>Description</h2>
Project consists of;
A simple PowerShell script that walks the user through creating an integrity baseline of target files/folders using the SHA-512 hashing algorithm and continously making comparison of actual files vs baseline, raised alerts if any deviations occured.

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Hashing Algorithms (SHA512)
- <b>A little bit of Automation

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Calculating Hash: <br/>
<img src="https://i.imgyukle.com/img/2023/05/06/rPJsxh.jpeg" height="80%" width="80%"/>
<br />
<br />
Storing Hash in the Baseline:  <br/>
<img src="https://i.imgyukle.com/img/2023/05/06/rPJ20I.jpeg" height="80%" width="80%"/>
<br />
<br />
Notify if a File Has Been Created/Modified: <br/>
<img src="https://i.imgyukle.com/img/2023/05/06/rPJwGP.jpeg" height="80%" width="80%"/>
<br />
<br />
File Has Been Created Alert:  <br/>
<img src="https://i.imgyukle.com/img/2023/05/06/rPJ0bq.jpeg" height="80%" width="80%"/>
<br />
<br />
File Has Been Modified Alert:  <br/>
<img src="https://i.imgyukle.com/img/2023/05/06/rPJdg0.jpeg" height="80%" width="80%"/>
<br />
<br />
File Has Been Deleted Alert:  <br/>
<img src="https://i.imgyukle.com/img/2023/05/06/rPQRqp.jpeg" height="80%" width="80%"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
