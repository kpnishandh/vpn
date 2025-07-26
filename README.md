# vpn
<img width="3333" height="1414" alt="image" src="https://github.com/user-attachments/assets/e5377f0d-7c0a-4b02-9f23-ff6dcfe0a65e" />

Site-A to Site-B [Site-to-Site] VPN. Go to VPN —> IPsec Wizard

Enter the Remote Site Public IP along with PSK(pre-shared key).




Now it is time to add the interesting network (private subnet of both sides)


Configure the Tunnel both the sides:(once both side tunnel configured and both the phase negotiation complete tunnel come up or you need to manually bring up the tunnel)



once you passed the traffic between two peers the tunnel comes up:


Automatically Policy added: to allowing traffic from two different sites.



Static Routes between two Tunnel:



To Monitoring the VPN Tunnel traffic and User actions:


Summary:
	• Covers the architecture of IPsec, detailing its components and protocols for securing internet communications.
	• Explains IKE Phase 1 & 2, which are crucial for establishing and managing secure VPN connections between peers.
	• Provides a step-by-step guide on configuring IPsec VPN between FortiGate firewalls, ensuring secure communication channels between networks or devices.
This module equips administrators with essential knowledge and practical skills for setting up IPsec VPNs using FortiGate firewalls, enhancing network security, and enabling secure communication over the internet.











<img width="592" height="4034" alt="image" src="https://github.com/user-attachments/assets/a95193ac-16b3-40f3-bfe2-42bc415a7a30" />
