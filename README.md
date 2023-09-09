<h1>Azure Sentinel Failed RDP Global Map</h1>

 ### [Video Demonstration](https://www.loom.com/share/c3b71b9db65a4718b079e75bff005347)

<h2>Description</h2>
This project consists of creating a honeypot that uses a custom PowerShell script to extract metadata from Windows Event Viewer, which is then forwarded to an API to derive geolocation data. After configuring the Log Analytics Workspace in Azure to take in custom logs for geographic information, (latitude, longitude, state/province, and country) you can configure a Azure Sentinel (Microsoft Cloud’s SIEM) workbook to display global attack data (RDP brute force) on a world map according to physical location, and number of attacks.

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell: Extract RDP failed logon logs from Windows Event Viewer</b> 

<h2>Environments Used </h2>

- <b>ipgeolocation.io: IP Address to Geolocation API0</b> (21H2)

<h2>Custom logs being output with geodata: </h2>
<img src="https://i.imgur.com/BvdON3p.png" height="80%" width="80%" alt="Global Map"/>

<p align="center">
  <h2>World map of incoming attacks after 24 hours: </h2>
<img src="https://i.imgur.com/v2tdyXK.png" height="80%" width="80%" alt="Powershell Script"/>
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
