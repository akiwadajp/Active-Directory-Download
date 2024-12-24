
<h1>Download Active Directory</h1>

<h2>Description</h2>
Downloading and Installing Active Directory Module via Powershell Scripts
<br />
<br />
<br />

<h2>Process walk-through:</h2>
Right-click the Start button and select "Windows PowerShell" then select Run as Administrator.
<br />
<br />
<br />
Listing RSAT Capabilities: <br/>
Get-WindowsCapability -Name RSAT* -Online | Select-Object -Property Name, State
<br />
This command lists all RSAT capabilities available on your system and their current state
<br />
<br />
<br />



Installing a Specific RSAT Capability:
<br />
Add-WindowsCapability -Online -Name RSAT.ActiveDirectory.CertificateServices.Tools
<br />
<br />
<br />
<br />
<br />
<br />
<br />
