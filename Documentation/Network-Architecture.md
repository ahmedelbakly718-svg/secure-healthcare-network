# Network Architecture

## 1. Overview
The proposed network architecture provides a secure, scalable, and reliable communication infrastructure for a healthcare organization.

## 2. Network Design
The network follows a hierarchical design consisting of three main layers:

### Core Layer
- Provides high-speed backbone connectivity.
- Connects the main network infrastructure.
- Supports communication between network segments.

### Distribution Layer
- Connects access switches to the core layer.
- Applies routing and network access policies.
- Controls communication between VLANs.

### Access Layer
- Connects computers, printers, medical devices, and wireless access points.
- Provides network access to hospital departments.

## 3. Network Segmentation
The network is divided into separate VLANs:

| VLAN ID | Department | IP Network |
|---|---|---|
| 10 | Administration | 192.168.10.0/24 |
| 20 | Doctors | 192.168.20.0/24 |
| 30 | Nursing | 192.168.30.0/24 |
| 40 | Laboratory | 192.168.40.0/24 |
| 50 | Radiology | 192.168.50.0/24 |
| 60 | Reception | 192.168.60.0/24 |
| 70 | Servers | 192.168.70.0/24 |
| 80 | Guest Wi-Fi | 192.168.80.0/24 |
| 99 | Network Management | 192.168.99.0/24 |

## 4. Main Network Components
- Core Layer 3 Switch.
- Distribution Switches.
- Access Switches.
- Edge Router.
- Firewall.
- DHCP and DNS Servers.
- Application and Database Servers.
- Wireless Access Points.

## 5. Network Security Architecture
- VLAN-based network segmentation.
- Firewall protection at the network boundary.
- Access Control Lists (ACLs).
- Restricted guest network access.
- Secure management access.
- Monitoring and logging.

## 6. Network Communication
Inter-VLAN communication is controlled through Layer 3 routing and security policies. Access to healthcare servers is restricted according to departmental requirements.

## 7. Simulation Environment
Cisco Packet Tracer will be used to create and test the proposed network topology.

## 8. Conclusion
The proposed architecture provides an organized foundation for secure communication, network management, and future expansion of healthcare systems.

Note: The IP addressing plan and VLAN assignments are proposed values for the project simulation.
