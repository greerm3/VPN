<h1>Virtual Private Network</h1>
<h2>Description</h2>
To change an IP address to a different location around the world using a Virtual Machine, Remote Desktop and Proton VPN.
<h2>Languages and Utilities Used</h2>

- <b>Azure Virtual Machine<b>
- <b>Remote Desktop<b>
- <b>Proton VPN

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Azure<b>

<h2>Setup:</h2>


- <b>Go to https://whatismyipaddress.com and write down the IPv4 address and city<b>
- <b>Create a Virtual Machine resource. *Leave Resource Group blank and choose a Region different from where you live<b>
<p>
<img src="https://imgur.com/ono7yvJ.png" height="80%" width="80% alt="vpn"/>

- <b>Log into Remote Desktop using public IP address from Virtual Machine<b>
- <b>Go to http://whatismyipaddress.com and write down new IPv4 address and city<b>
- <b>Go to https://protonvpn.com/<b>
- <b>Create free account and download<b>
<p>
<img src="https://i.imgur.com/QYvkAaK.png" height="80%" width="80% alt="vpn"/>

- <b>Sign in and choose country to access vpn<b>
<p>
<img src="https://i.imgur.com/wYAdVec.png" height="80%" width="80% alt="vpn"/>

- <b>Go to google.com or another website to see it in the language from the country you chose<b>

<h3>End</h3>

- <b>Logout and disconnect fron VPN</b>
- <b>Disconnect from Remote Desktop </b>

*Please make sure to delete resource groups in Azure when finished.
