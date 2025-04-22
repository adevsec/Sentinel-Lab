<h1>Failed RDP to IP Geolocation Information</h1>


 ### [YouTube Demonstration (@16:20)](https://youtu.be/RoZeVbbZ0o0?t=980)


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewe
<h2>Key Characteristics</h2>
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer
- Vulnerability ID: MS17–010
- CVE Identifiers:
- CVE-2017–0144: Related to remote code execution through the SMBv1 protocol.
- CVE-2017–0145: Related vulnerability affecting the SMB protocol.
- CVE-2017–0146: Another associated vulnerability.
- Affected Systems: Windows 7, Windows Server 2008, and earlier versions with SMB v1 enabled.
- Impact: Remote Code Execution, allowing attackers to gain full control of the system.
<h2>Utilities Used</h2>




<br />
<br />

<p align="center">
<img src="https://i.imgur.com/3d3CEwZ.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/LhDCRz4.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
