# **Notes**
- Static routes between R1, R2 & R3.
- Default routes on R1 & R2 pointing to R3.
- Default route on R3 pointing to internet router for non-LAN traffic.

# **Difficulty**
- (1/5)

# **Network Diagram**


# **Commands used**
- ip route (dest-network) (subnet-mask) (next-hop-address)
- ip route 0.0.0.0 0.0.0.0 (next-hop-address)
- show ip route
