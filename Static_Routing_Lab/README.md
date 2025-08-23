# **Notes**
- Static routes between R1, R2 & R3.
- Default routes on R1 & R2 pointing to R3.
- Default route on R3 pointing to internet router for non-LAN traffic.
- Not including any configurations to do with inter-vlan routing.
  
# **Network Diagram**
<img width="665" height="643" alt="Image" src="https://github.com/user-attachments/assets/f40750be-7d7f-4701-91ef-24bf785bc329" />

# **Commands used**
- ip route (dest-network) (subnet-mask) (next-hop-address)
- ip route 0.0.0.0 0.0.0.0 (next-hop-address)
- show ip route
