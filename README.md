# Cyber_security NMAP

**Nmap (Network Mapper)** is a powerful tool used for scanning open ports on devices. By scanning for open ports, we can potentially identify vulnerabilities on platforms (not specific URLs). Nmap supports several scan types, including `-sS` (SYN scan) for stealthy TCP scanning and `-sV` to detect the version of the services running on those ports.

Devices connected to the same network as the local host can be scanned to check for open ports. **TCP (Transmission Control Protocol)** is used for reliable communication over a network.

Some commonly found open ports include:

UPnP (Universal Plug and Play): Typically used for automatic device discovery and communication. However, it can be unreliable and pose security risks due to automatic port openings and weak or no authentication.
afs3-fileserver: A legacy file-sharing service that, if not properly secured, can be a vulnerability. It may expose sensitive files and data.

