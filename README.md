# 📘 VPN Setup & Usage

This project demonstrates how to set up and validate a VPN connection using **ProtonVPN**, alongside integrating VPN use with a **virtual machine (VM)** in Microsoft Azure. It’s intended for IT beginners, students, and aspiring cybersecurity professionals looking to build foundational hands-on skills.

---

## 🛠️ Setup Instructions

### 1. Install ProtonVPN
- Download and install the ProtonVPN desktop app.
- ![ProtonVPN Installed](https://imgur.com/a/saqdbrE)

### 2. Connect to a VPN Server
- Choose a server (e.g., Romania `RO-FREE#5`) and connect using WireGuard (UDP).
- Monitor connection status and traffic metrics.
- [![VPN Connected](ProtonVPN_Run.png)](ProtonVPN_Run.png)

---

## 🌐 IP Address Validation

### 3. Check Your IP Without VPN
- Visit [whatismyipaddress.com](https://whatismyipaddress.com) before connecting.
- Note your **real IP and geolocation**.
- [![Without VPN IP](VPN_CurrentIP-WithVPNoff.png)](VPN_CurrentIP-WithVPNoff.png)

### 4. Check Your IP With VPN
- After connecting, revisit the site.
- Confirm that your IP has changed to reflect the VPN endpoint (e.g., Romania).
- [![With VPN IP](VPN_IP-ChangedConfirmation.png)](VPN_IP-ChangedConfirmation.png)

---

## ☁️ VPN with Azure Virtual Machine

### 5. Deploy a Windows VM on Azure
- Use Azure Portal to create a Windows 11 VM (e.g., "VM-Run").
- Configure networking, region, and resources.
- [![VM Setup](VPN_VM-Setup.png)](VPN_VM-Setup.png)
- [![VM Setup 2](VPN_VM-Setup2.png)](VPN_VM-Setup2.png)

### 6. Validate VPN Protection on the VM
- Connect to the VM using Remote Desktop.
- Install ProtonVPN and verify traffic is tunneled through the VPN.
- [![VM Details](VPN_VM-Confirmation.png)](VPN_VM-Confirmation.png)
- [![Browsing with VPN](VPNRun_Example1.png)](VPNRun_Example1.png)
- [![Browsing Example 2](VPNRun_Example2.png)](VPNRun_Example2.png)
- [![Browsing Example 3](VPNRun_Example3.png)](VPNRun_Example3.png)

---

## 🎯 Learning Outcomes

By completing this project, you will:

- ✅ Understand how VPNs secure your network traffic and mask IP addresses
- ✅ Learn to validate VPN connections using IP check tools
- ✅ Practice integrating VPN clients inside Azure-hosted virtual machines
- ✅ Gain experience in configuring and managing cloud infrastructure
- ✅ Build a foundational IT lab for your resume or cybersecurity portfolio

---

## ✅ Summary

This project gives you practical experience with VPN setup, IP verification, and Azure VM integration — useful skills for entry-level IT and cybersecurity roles.

Feel free to fork this project or open an issue if you'd like to suggest improvements or request enhancements!
