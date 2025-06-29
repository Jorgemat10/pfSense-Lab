<h1>Network Firewall Lab - pfSense</h1>

<h2>Description</h2>
pfSense is an open-source firewall and router platform widely used to secure networks of all sizes. In this lab, pfSense is used to create a virtual firewall for a segmented lab environment. Key features implemented include DHCP server setup, firewall rules, NAT, port forwarding, and multi-factor authentication (MFA) for admin login access.

This firewall is used as the front-line defense in a virtualized cybersecurity lab setup and supports secure communication between other VMs like Wazuh, Nessus, and Windows.

<h2>Tools and Technologies Used</h2>
- <b>pfSense CE</b>
- <b>VirtualBox</b>
- <b>Multi-Factor Authentication</b>

<h2>Environments Used</h2>
- <b>pfSense VM</b>
- <b>VirtualBox NAT Network</b>

<h2>Firewall Configuration Walk-through</h2>

<p align="center">
Initial Setup and Network Interfaces <br/>
<img src="LINK_TO_IMAGE_pfsense_interfaces.png" height="80%" width="80%" />

<br /><br />
WebGUI Login Page <br/>
<img src="LINK_TO_IMAGE_pfsense_login.png" height="80%" width="80%" />

<br /><br />
DHCP Server Configuration Example <br/>
<img src="LINK_TO_IMAGE_pfsense_dhcp.png" height="80%" width="80%" />

<br /><br />
Firewall Rules: Allow Internal Access <br/>
<img src="LINK_TO_IMAGE_pfsense_rules.png" height="80%" width="80%" />

<br /><br />
MFA Login Setup for pfSense Admin Access <br/>
<img src="LINK_TO_IMAGE_pfsense_mfa.png" height="80%" width="80%" />
</p>
