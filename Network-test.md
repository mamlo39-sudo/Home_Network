```mermaid
graph TD
    Internet --> Firewall
    Firewall --> LoadBalancer
    LoadBalancer --> WebServer1
    LoadBalancer --> WebServer2
    WebServer1 --> DBServer
    WebServer2 --> DBServer
