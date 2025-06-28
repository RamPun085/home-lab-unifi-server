# 🏠 UniFi Home Lab – UDM Pro + NAS + UPS Setup

This project showcases my home lab built to simulate a secure, production-like enterprise network using **UniFi hardware**, a **dedicated home server**, **NAS with RAID**, and **power backup**. It reflects hands-on experience in IT infrastructure, network configuration, and home automation — valuable for roles in IT support, networking, and system administration.

---

## 🌐 Lab Overview

| Component             | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| 🧠 **UniFi Dream Machine Pro (UDM Pro)** | Acts as main router, firewall, and UniFi controller (UniFi OS)   |
| 🔌 **UniFi 24-Port Managed Switch**     | Handles device connectivity, PoE, VLAN segmentation               |
| 💾 **NAS with Red Partition (RAID)**    | Provides local data storage with redundancy and backup strategy  |
| 🔋 **CyberPower UPS**                   | Power backup and surge protection for all critical devices       |
| 🖥️ **Home Server**                     | Hosts local services (media, monitoring, automation, backups)    |

---

## ⚙️ What I Configured

| Feature                    | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| 🎛️ UDM Pro Configuration   | Setup WAN, LAN, DHCP, DNS, port forwarding, and threat detection           |
| 🔒 Firewall Rules          | Custom rules for external access and internal device isolation              |
| 📶 Wi-Fi Networks          | Created multiple SSIDs for Home, Guest, and IoT devices                     |
| 📈 Network Monitoring      | Real-time monitoring via UniFi dashboard and alerts                         |
| 📦 NAS Storage             | Configured RAID (Red Partition) for data reliability and local access       |
| 🔌 Managed Switching       | VLAN assignment, port profiles, PoE control via UniFi 24-port switch        |
| 🔋 UPS Management          | Ensures uptime and protection during power outages                          |

---

## 🎥 UniFi Protect – Camera Setup

- Integrated UniFi Protect cameras via UDM Pro
- Enabled **remote live access** through the UniFi Protect mobile app
- Set up **motion alerts, event recording**, and storage management
- Verified mobile and web streaming performance internally and remotely

---

## 🧠 Skills Demonstrated

- 🔧 Network setup (LAN, DHCP, DNS, VLANs, firewall rules)
- 🧩 VLAN planning and inter-network segmentation (in progress)
- 🖥️ Device provisioning and lifecycle management (UDM, switches, APs)
- 💾 RAID storage planning and basic NAS access control
- 🔋 Power protection design and failover planning with UPS
- 📹 Live security camera setup with UniFi Protect
- 📊 Real-time network and device monitoring

---

## 🗺️ Planned Screenshots 

- 🌐 UDM Pro dashboard overview
- 🧠 UniFi Protect interface (with cameras live)
- 🔌 UniFi 24-port switch config UI
- 📶 Wireless setup view (SSID, channel, radios)
- 🗃️ NAS dashboard (storage volume info)
- 🔋 CyberPower UPS status and runtime report

---

## 🚀 Roadmap

- 🔐 Configure VLANs for Guest, IoT, Admin, and Work zones
- 🌐 Set up VPN (WireGuard or OpenVPN) for secure remote access
- 📦 Document NAS backup strategy and enable remote file access
- 📊 Integrate Netdata or Grafana for real-time dashboard metrics
- 📁 Automate NAS + device config backups using shell or Python scripts

---

## 📚 Related Tools

- 📘 [UniFi OS Documentation](https://help.ui.com/)
- 💾 [Synology/TrueNAS/ZFS Guide (if applicable)](https://www.truenas.com/)
- 🔋 [CyberPower UPS Monitoring](https://www.cyberpowersystems.com/)
- 📊 [Netdata](https://www.netdata.cloud/)
- 📦 [Pi-hole](https://pi-hole.net/)

---

> 💡 This home lab simulates real-world enterprise infrastructure and demonstrates hands-on experience in IT support, system admin, and network engineering.  
> 📫 I'm always looking to collaborate and grow in the IT infrastructure space — feel free to reach out!



