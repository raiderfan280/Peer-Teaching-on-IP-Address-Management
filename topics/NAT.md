# Network Address Translation (NAT)

NAT is a method used in networks to modify the source or destination IP address of packets. It allows multiple devices within a local network to share a single public IP address.

### Example Configuration
```bash
Router(config)# ip nat inside source list 1 interface GigabitEthernet0/0 overload
```

### Key Points
- NAT conserves public IP addresses.
- It hides the internal network structure from external networks.
