graph TD
    Internet --> FW[Firewall]
    FW --> DMZ[DMZ Network]
    DMZ --> WEB[Web Server]
    FW --> LAN[Internal Network]
    LAN --> DB[Database Server]