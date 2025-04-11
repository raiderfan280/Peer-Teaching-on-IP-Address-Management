# DHCP Configuration

**Dynamic Host Configuration Protocol (DHCP)** is a network management protocol used on IP networks. It automatically assigns IP addresses to devices in the network, eliminating the need for manual IP assignment.

### Example DHCP Configuration
```bash
Router(config)# ip dhcp pool OFFICE
Router(dhcp-config)# network 192.168.1.0 255.255.255.0
Router(dhcp-config)# default-router 192.168.1.1
Router(dhcp-config)# dns-server 8.8.8.8
```

### Key Points
- DHCP reduces manual configuration errors.
- Can be configured for specific address ranges.
