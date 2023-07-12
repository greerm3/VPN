<h1>Virtual Private Network</h1>
<h2>Description</h2>
To change an IP address to a different location around the world using a Virtual Machine, Remote Desktop and Proton VPN.
<h2>Languages and Utilities Used</h2>

- <b>Azure Virtual Machine</b>
- <b>Remote Desktop</b>
- <b> Proton VPN

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Setup:</h2>
<p align="left">

- <b>Go to https://whatismyipaddress.com and write down the IPv4 address and city<b>
- <b>Create a Virtual Machine resource. *Leave Resource Group blank and choose a Region different from your own <b>
<p>
<img src="https://i.imgur.com/fF5CWDB.png" height="80%" width="80% alt="vpn"/>

- <b>Log into VM in Remote Desktop using public IP address from VM
- <b>Go to https://whatismyipaddress.com and write down new IPv4 address and city</b>
- <b>Go to https://protonvpn.com/
- <b>Create free account and download
<p>
<img src="https://i.imgur.com/QYvkAaK.png" height="80%" width="80% alt="vpn"/>

- <b>Sign in and choose country to access vpn
<p>
<img src="https://i.imgur.com/wYAdVec.png" height="80%" width="80% alt="vpn"/>

- <b>Go to google.com or another website to see it in the language from the country you chose

<h2>End</h2>
*Please make sure to delete resource groups in Azure when finished.
