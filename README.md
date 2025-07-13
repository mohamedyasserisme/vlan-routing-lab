# vlan-routing-lab
Cisco Packet Tracer project for VLAN and Inter-VLAN routing (Router-on-a-Stick lab)

🔧 VLAN & Inter-VLAN Routing Lab (Cisco Packet Tracer)

 📁 Project Overview:
This is a simulated enterprise network built using **Cisco Packet Tracer**, designed to demonstrate:

- VLAN creation and segmentation
- Trunking between switches
- Router-on-a-Stick configuration
- Inter-VLAN routing between two departments (IT & HR)

---
 🖥️ Topology Summary:

```
Devices Used:
- 2 x Cisco 2960 Switches
- 1 x Cisco Router (2 x Gigabit interfaces)
- 8 x End Devices (PCs and Laptops)
```

- VLAN 10 – IT Department:  
  IP Range: `192.168.10.0/24`

- VLAN 20 – HR Department:  
  IP Range: `192.168.20.0/24`

- Router Sub-Interfaces:
  - `Gig0/0.10` ➝ IP: `192.168.10.1`, Encapsulation: dot1Q 10
  - `Gig0/0.20` ➝ IP: `192.168.20.1`, Encapsulation: dot1Q 20

- **Trunk Link** between switches:  
  Configured using FastEthernet ports with `switchport mode trunk`

---

✅ Features Implemented:

- VLAN configuration on both switches
- Assigning access ports to appropriate VLANs
- Trunk configuration between switches
- Router-on-a-Stick with sub-interfaces
- Ping tested successfully between:
  - Same VLAN devices
  - Different VLANs (via router)

---

💡 Skills Demonstrated:

- Networking fundamentals (Layer 2 & 3)
- VLAN & Trunking concepts
- Subnetting & IP addressing
- Cisco CLI configuration
- Network troubleshooting

---

📂 Files

- `VLAN_Lab.pkt` → The full Cisco Packet Tracer project file

---

🧠 Author

Mohamed Yasser Abdellah 
Cybersecurity & Network Student | Red Team Track  
[LinkedIn Profile](https://www.linkedin.com/in/mohamed-yasser-613b77297?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

 📌 Note

This project is part of my practical training during my cybersecurity learning journey. More labs coming soon!
