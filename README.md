<div align="center">

# 🌐 Cisco Packet Tracer – Create a Simple Network

### Computer Networks Practical Assignment

**Student:** Thabiso Nkambule

**Course:** BSc Computer Science

**Institution:** Walter Sisulu University

**Software:** Cisco Packet Tracer 8.x

![Cisco](https://img.shields.io/badge/Cisco-Packet_Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Networking](https://img.shields.io/badge/Computer-Networks-0A66C2?style=for-the-badge)
![IPv4](https://img.shields.io/badge/IPv4-Configured-success?style=for-the-badge)
![DHCP](https://img.shields.io/badge/DHCP-Enabled-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

# 📖 Project Overview

This project demonstrates the design and implementation of a **simple Local Area Network (LAN)** using **Cisco Packet Tracer**.

The objective of this practical was to understand fundamental networking concepts by building a small network, configuring end devices, obtaining IP addresses through DHCP, and verifying connectivity between devices.

---

# 🎯 Objectives

✔ Build a simple network topology

✔ Connect networking devices using the correct cables

✔ Configure wired and wireless end devices

✔ Obtain IPv4 addresses using DHCP

✔ Verify IP configuration

✔ Test network connectivity using the `ping` command

✔ Understand the role of the default gateway

✔ Explore basic IPv4 networking concepts

---

# 🛠 Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Cisco Packet Tracer | Network Simulation |
| IPv4 | Device Addressing |
| DHCP | Automatic IP Address Assignment |
| Ethernet | Wired Communication |
| Wireless LAN | Laptop Connectivity |
| ICMP (Ping) | Connectivity Testing |

---

# 📂 Repository Structure

```
cisco-packet-tracer-simple-network
│
├── packet-tracer/
│   └── Create_Simple_Network.pkt
│
├── assignment/
│   └── Assignment.pdf
│
├── screenshots/
│   ├── topology.png
│   ├── pc-ipconfig.png
│   ├── laptop-ipconfig.png
│   ├── successful-ping.png
│   └── browser-test.png
│
└── README.md
```

---

# 🖥 Network Topology

The network consists of the following devices:

| Device | Purpose |
|---------|----------|
| 🖥 PC | Wired End Device |
| 💻 Laptop | Wireless End Device |
| 📡 Wireless Router | DHCP Server & Default Gateway |
| 🌐 Cable Modem | Internet Access |
| ☁ Internet Cloud | ISP Connection |

> **Insert your Packet Tracer topology screenshot below**

<p align="center">
<img src="screenshots/topology.png" width="800">
</p>

---

# 🔧 Network Configuration

## PC Configuration

- Connected using Copper Straight-Through Cable
- DHCP Enabled
- Automatically received IPv4 Address
- Successfully communicated with other devices

---

## Laptop Configuration

- Replaced Ethernet NIC with Wireless WPC300N Module
- Connected to **HomeNetwork**
- Received IPv4 Address automatically through DHCP
- Successfully accessed the network

---

# 🌍 IP Addressing

| Device | IPv4 Address | Subnet Mask | Default Gateway |
|---------|--------------|-------------|-----------------|
| PC | 192.168.0.x | 255.255.255.0 | 192.168.0.1 |
| Laptop | 192.168.0.x | 255.255.255.0 | 192.168.0.1 |

> Replace the placeholder IP addresses with the values obtained from `ipconfig`.

---

# 📡 Connectivity Verification

The following commands were used during testing:

```bash
ipconfig

ipconfig /all

ping 192.168.0.2
```

### Expected Output

```
Reply from 192.168.0.2

Reply from 192.168.0.2

Reply from 192.168.0.2

Reply from 192.168.0.2
```

Receiving four successful replies confirms that the devices can communicate across the network.

---

# 📷 Screenshots

## 🖥 Network Topology

<p align="center">
<img src="topology.png" width="850">
</p>

---

## 📋 PC IP Configuration

<p align="center">
<img src="pc-ipconfig.png" width="750">
</p>

---

## 💻 Laptop IP Configuration

<p align="center">
<img src="screenshots/laptop-ipconfig.png" width="750">
</p>

---

## 📡 Successful Ping Test

<p align="center">
<img src="screenshots/successful-ping.png" width="750">
</p>

---

# 📚 Key Networking Concepts Learned

During this practical, I gained hands-on experience with:

- Local Area Networks (LAN)
- IPv4 Addressing
- Dynamic Host Configuration Protocol (DHCP)
- Default Gateway
- Subnet Masks
- Wired Networking
- Wireless Networking
- Network Connectivity Testing
- Cisco Packet Tracer Simulation
- Basic Network Troubleshooting

---

# 🚀 How to Run

1. Install **Cisco Packet Tracer 8.x** or later.

2. Clone this repository

```bash
git clone https://github.com/Thabiso0503/cisco-packet-tracer-simple-network.git
```

3. Open

```
packet-tracer/Create_Simple_Network.pkt
```

4. Verify device configuration.

5. Test connectivity using

```bash
ipconfig

ipconfig /all

ping 192.168.0.2
```

---

# 🎓 Learning Outcomes

This project strengthened my understanding of:

- Building a LAN topology
- Device configuration
- DHCP operation
- IP Address allocation
- Network communication
- Connectivity troubleshooting
- Cisco Packet Tracer fundamentals

---

# 📌 Future Improvements

- Configure Static IP Addressing
- Implement VLANs
- Add Additional Switches
- Configure Static Routing
- Introduce Network Security Features
- Configure DNS Services

---

# 👨‍💻 Author

## Thabiso Nkambule

Final Year BSc Computer Science Student

Walter Sisulu University

🔗 GitHub: **https://github.com/Thabiso0503**

🔗 LinkedIn: *www.linkedin.com/in/thabiso-nkambule-08a037342*

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a star!

</div>
