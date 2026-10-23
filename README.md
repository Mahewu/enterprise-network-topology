# Enterprise VLAN & Inter-VLAN Routing Simulation

## 📌 Project Overview
This project demonstrates a core enterprise switching topology built and validated inside **EVE-NG**. The lab focuses on isolating broadcast domains using VLANs, configuring 802.1Q trunking links between switches, and enabling Inter-VLAN routing to allow secure communication between different subnets.

## 🗺️ Network Topology
![Network Topology Diagram](topology.png)

## 🛠️ Technologies & Features Configured
*   **Layer 2 VLANs:** Segmented network traffic to reduce broadcast domains.
*   **802.1Q Trunking:** Configured trunk ports between switches to carry traffic for multiple VLANs.
*   **Inter-VLAN Routing:** Enabled routing between isolated networks.
*   **Native VLAN Security:** Changed default native VLANs to secure unused traffic paths.

## 🚀 How to Review This Project
1. **View the Architecture:** Look at the `topology.png` screenshot above to see the structural layout of the switches, routers, and host machines.
2. **Key Validation:** This layout successfully separates client traffic while providing a controlled path for cross-VLAN communication.
