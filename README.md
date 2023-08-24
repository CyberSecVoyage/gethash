<h1>How to Generate Hash</h1>

<h2>Description</h2>
This is a simple demostration how I generate hash from a file downloaded from Visual Studio Code, checking the generated hash against hash from the download page on Visual Studio Code to ensure the hash is the same. If source of download does not share its hash to check for integrity, checking the generated hash on VirusTotal can help to determine if the file is malicious.
<br />

<h2>Environments Used </h2>

- <b>Kali Linux</b>

<h2>Program walk-through:</h2>

<p align="center">
Generate hash in Linux (MD5 and SHA256 Hash) <br/>
<img src="https://imgur.com/dunMQy7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />



<p align="center">
Check SHA256 hash from download page<br/>
Go to "https://code.visualstudio.com/download" and click "See SHA256 Hashes".<br/>
<img src="https://imgur.com/MNYKvpC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />



<p align="center">
Go to VirusTotal <br/>
<img src="https://i.imgur.com/fVGvuyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

9cbc6a28a584f5a55826c260e5f43094

<p align="center">
Search the hash VirusTotal <br/>
<img src="https://imgur.com/AaM7PtV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
No Issue. Safe to download <br/>
<img src="https://imgur.com/IMLnLgF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
