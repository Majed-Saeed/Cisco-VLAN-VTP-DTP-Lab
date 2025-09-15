# Packet Tracer – Configure VLANs, VTP, and DTP

## Objectives
- Configure and verify DTP
- Configure and verify VTP
- Assign VLANs to ports
- Verify end-to-end connectivity

## Addressing Table
| Device | Interface | IP Address     | Subnet Mask     |
|--------|-----------|----------------|-----------------|
| PC0    | NIC       | 192.168.10.1   | 255.255.255.0   |
| PC1    | NIC       | 192.168.20.1   | 255.255.255.0   |
| PC2    | NIC       | 192.168.30.1   | 255.255.255.0   |
| PC3    | NIC       | 192.168.30.2   | 255.255.255.0   |
| PC4    | NIC       | 192.168.20.2   | 255.255.255.0   |
| PC5    | NIC       | 192.168.10.2   | 255.255.255.0   |
| S1     | VLAN 99   | 192.168.99.1   | 255.255.255.0   |
| S2     | VLAN 99   | 192.168.99.2   | 255.255.255.0   |
| S3     | VLAN 99   | 192.168.99.3   | 255.255.255.0   |

## Steps
1. Configure trunk links using DTP and set VLAN 999 as native VLAN.  
2. Configure VTP:
   - S1 as VTP Server  
   - S2 as VTP Client  
   - S3 as VTP Transparent  
3. Create VLANs 10 (Red), 20 (Blue), 30 (Yellow).  
4. Assign VLANs to switch ports.  
5. Verify connectivity with ping between PCs in the same VLAN.  

## How to Use
- Open `VLAN_VTP_DTP.pkt` in Cisco Packet Tracer.  
- Follow the objectives and steps above.  
