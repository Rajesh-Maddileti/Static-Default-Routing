# Static & Default Routing – Cisco Packet Tracer (NOC / Network Engineer Lab)

This project demonstrates basic **Static Routing** and **Default Routing**
in a multi-router network using **Cisco Packet Tracer**.

The lab is designed to build foundational skills required for an
entry-level NOC / Network Engineer role, including configuration,
monitoring, and basic troubleshooting.

## Objective

- Configure static routing between multiple LANs
- Configure default routing on the edge router
- Verify network connectivity and routing tables
- Understand packet flow across routers

## Network Topology

- Routers: R1, R2, R3
- One ISP router for external connectivity
- Each router connected to a separate LAN
- End devices used for testing connectivity

R3 is configured as the **gateway of last resort**.

## Routing Configuration

- **Static routing** configured on R1 and R2
- **Default route (0.0.0.0/0)** configured on R3
Example:
ip route 0.0.0.0 0.0.0.0 192.168.7.2

## Verification
The following commands were used to verify the network:

show ip route
show ip interface brief
ping <destination-ip>

Successful ping results confirm end-to-end connectivity.

## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI
## Skills Practiced

- Static routing
- Default routing
- Routing table verification
- Basic network troubleshooting

  ## Network Topology

- [View Network Topology](topology.jpeg)

  ## Router Configurations

- [R1 Configuration](R1-config.jpeg)
- [R2 Configuration](R2-config.jpeg)
- [R3 Configuration](R3-config.jpeg)

  ## Ping Verification

- [Ping Verification](ping-verification.jpeg)
