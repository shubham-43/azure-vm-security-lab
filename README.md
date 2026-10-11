Azure VM Security & Troubleshooting Lab

Project Status

In Progress — learning and documentation lab.

Objective

Learn how Azure virtual machines are connected and secured, and develop a structured approach to troubleshooting common connectivity problems.

Architecture Components

- Azure Virtual Machine: A server running an operating system and applications.
- Virtual Network (VNet): Provides private network connectivity for Azure resources.
- Subnet: Divides a virtual network into smaller IP-address ranges.
- Network Security Group (NSG): Filters inbound and outbound network traffic.
- Azure Bastion: Provides browser-based remote access to VMs through their private IP addresses.

- Network Address Plan

Component| Example address
Virtual Network| 10.0.0.0/16
VM Subnet| 10.0.1.0/24
Linux VM Private IP| 10.0.1.4

These addresses are used for the proposed lab design. No Azure resources have been deployed.

Security Principles

- Apply least-privilege access.
- Allow only the network traffic required.
- Avoid exposing SSH or RDP directly to the entire internet.
- Verify connectivity and access permissions systematically.

Lab Activities

1. Document the proposed network architecture.
2. Study NSG inbound and outbound rules.
3. Analyse simulated SSH connectivity failures.
4. Document findings, corrective actions and verification steps.

Current Progress

- [x] Learned the roles of the main Azure architecture components.
- [ ] Document the network and IP-addressing plan.
- [ ] Analyse NSG traffic scenarios.
- [ ] Complete troubleshooting exercises.

Important Note

This is a learning and documentation project. No Azure infrastructure has been deployed as part of the initial activities.
