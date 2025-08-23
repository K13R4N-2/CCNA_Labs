# **Notes**
- L3 router is not being used with ROAS for vlan tagging.
- no native vlan configured.

# **Network Diagram**
<img width="791" height="433" alt="Image" src="https://github.com/user-attachments/assets/75c6a82e-1f95-4f46-96be-ca4a32c7cb60" />

# **Commands used**
- switchport mode access
- switchport access vlan (vlan-id)
- switchport mode trunk
- switchport trunk access vlan (vlan-id)
- interface (interface)(sub-int)
- encapsulation dot1q vlan (vlan-id)
- vlan (vlan-id)
- interface vlan (vlan-id)
- ip address (ip-address) (subnet-mask)
- ip routing
- ip route (destination-network) (subnet-mask) (next-hop)
