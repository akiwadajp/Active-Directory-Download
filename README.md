
<h1>Download Active Directory</h1>

<h2>Description</h2>
Downloading and Installing Active Directory Module via Powershell Scripts
<br />
Right-click the Start button and select "Windows PowerShell" then select Run as Administrator.
<br />
<br />

<h2>Process walk-through:</h2>

Listing RSAT Capabilities: <br/>
Get-WindowsCapability -Name RSAT* -Online | Select-Object -Property Name, State
<br />
<br />
<br />
<br />
<br />
<br />
