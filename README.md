<h1>Implementing a SOC and Honeypot in Azure</h1>

<h2>Description</h2>
In this lab I setup Microsoft Sentinel (SIEM) and connected it to a live virtual machine acting as a honey pot.  I was able to observe attacks happening in live time (RDP Brute Force) from all around the world. I used a custom Powershell script to look up the attackers Geolocation info and plot it on the Microssoft Sentinel Map.
<br />


<h2>Languages</h2>

- <b>Powershell: Extract failed logon logs from the Windows Event Viewer in our Virtual Machine</b>

<h2>Utilities Used </h2>

- <b>ipgeolocation.io: IP Address to Geolocation API</b>

<h2>Attacks from Russion incoming; Custom Logs being output with geodata:</h2>

<p align="center">
<img src="https://i.imgur.com/IllBIUa.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/d9JE5uP.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
