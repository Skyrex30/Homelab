This repository documents my homelab, where I experiment and learn about networking, security, and embedded systems.

My main router is a Mercusys MR80X running OpenWRT, flashed directly using a CH341A flasher. I use an HP mini PC running Proxmox to virtualize OPNSense with Snort IPS for traffic inspection and security experiments. Additional LXC containers run Wireguard (VPN), HomeAssistant, and PiHole.

Server & Virtualization: My main server runs OpenMediaVault with CasaOS to manage Docker containers and deploy virtual machines for security testing. I use these VMs to simulate attacks and follow various cybersecurity guides.

I have been flashing Tasmota on pre-flashed IoT hardware to enhance security and remove reliance on cloud services. I also work with Zigbee and other wireless protocols to reduce single points of failure and minimize the attack surface of my smart home network.

I'm experienced with electronics, UART flashing, and embedded programming. I’ve built multiple projects using microcontrollers (Arduino, ESP32, Raspberry Pi) and have a solid understanding of low-level hardware interactions.
