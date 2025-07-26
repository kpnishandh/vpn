# vpn
<img width="3333" height="1414" alt="image" src="https://github.com/user-attachments/assets/e5377f0d-7c0a-4b02-9f23-ff6dcfe0a65e" />

Site-A to Site-B [Site-to-Site] VPN. Go to VPN —> IPsec Wizard
<img width="3840" height="2200" alt="image" src="https://github.com/user-attachments/assets/214479c2-ba8e-4f5c-baa9-61d23060f457" />
Enter the Remote Site Public IP along with PSK(pre-shared key).
<img width="3838" height="2195" alt="image" src="https://github.com/user-attachments/assets/f329bc7d-3107-4aa3-9db9-ec6e49225113" />
Now it is time to add the interesting network (private subnet of both sides)
<img width="3840" height="2183" alt="image" src="https://github.com/user-attachments/assets/debfdaa7-ec02-42bd-b431-d5dcd6d6383a" />
Configure the Tunnel both the sides:(once both side tunnel configured and both the phase negotiation complete tunnel come up or you need to manually bring up the tunnel)
<img width="3831" height="2188" alt="image" src="https://github.com/user-attachments/assets/b5da11d1-1b02-4d78-aac1-9e92a576af59" />
once you passed the traffic between two peers the tunnel comes up:
<img width="3835" height="2183" alt="image" src="https://github.com/user-attachments/assets/a14bbe97-8a99-4156-b13e-15288b747216" />
Automatically Policy added: to allowing traffic from two different sites.
<img width="3831" height="2193" alt="image" src="https://github.com/user-attachments/assets/c5938185-8c6e-4138-9c3e-1d419b7f31a3" />
Static Routes between two Tunnel:
<img width="3840" height="2203" alt="image" src="https://github.com/user-attachments/assets/1a76d5e0-b05e-4ce5-bd22-895ca29542ec" />
To Monitoring the VPN Tunnel traffic and User actions:
<img width="3840" height="2195" alt="image" src="https://github.com/user-attachments/assets/ab8aa65f-332e-4a1d-90b8-e0cb75bcbf2c" />


Summary:

• Covers the architecture of IPsec, detailing its components and protocols for securing internet communications.

• Explains IKE Phase 1 & 2, which are crucial for establishing and managing secure VPN connections between peers.

• Provides a step-by-step guide on configuring IPsec VPN between FortiGate firewalls, ensuring secure communication channels between networks or devices.

This module equips administrators with essential knowledge and practical skills for setting up IPsec VPNs using FortiGate firewalls, enhancing network security, and enabling secure communication over the internet.



