⚙️ Configuration Summary
Network topology was built according to the given diagram and all interfaces were enabled (no shutdown).
RIP (version 2) was configured on R1, R2, and R3 for dynamic routing, with passive interfaces where needed.
Default static routes were configured between R1 and R4 for external connectivity.
Default route was redistributed into RIP on R1.
On R4, a Loopback0 interface was created with IP 8.8.8.8/32 and hostname/comment set as required.
DHCP was configured on R2 and R3 for automatic IP assignment to clients.
R4 configuration was backed up to a TFTP server.
All interfaces were properly configured and tested for connectivity.
