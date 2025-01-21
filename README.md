# malik.github.io memack@my.waketech.edu
School account 
This repository will hold assignments
# About Me 
- I was born and raised in Petersburg Va, Im an Army vet of 6 years, and I have one younger sibling.
## My Intrest 
- I enjoy playing video games, and modifying my car. Im also in school pursuing my cyber security degree
## website I recommend 
- [IBM] (https://www.ibm.com/think/topics/cybersecurity) - a little something about cyber security and what it means.
- ```mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant WebServer
participant Firewall
  
    Attacker->>Botnet: Command to start DDoS attack (Flood Webserver)
    Note right of Attacker: The Attacker controls the Botnet and instructs them to send traffic to the target server (Webserver).

    Botnet->>Webserver: Send massive traffic (Flood of requests)
    Note right of Botnet: The Botnet consists of many compromised devices (bots) which generate a high volume of traffic to overwhelm the Webserver.

    Webserver->>Firewall: Forward requests for filtering (Pass traffic through Firewall)
    Note right of Webserver: The Webserver receives the traffic, but first checks the Firewall for any malicious requests.

    Firewall->>Firewall: Inspect incoming traffic for DDoS signatures
    Note right of Firewall: The Firewall inspects each incoming request for patterns or signatures that match DDoS attack characteristics.

    Firewall-->>Webserver: Block some traffic or allow based on rules
    Note right of Firewall: The Firewall filters out some malicious requests based on its security rules (rate limiting, IP blocking, etc.).

    Webserver->>Webserver: Start dropping requests due to overload
    Note right of Webserver: Despite the Firewall's filtering, the Webserver is still overwhelmed by the sheer volume of requests, which leads to performance degradation.

    Webserver-->>Firewall: Alert: Server is overwhelmed, continuing attack
    Note right of Webserver: The Webserver sends an alert to the Firewall indicating that the server is becoming unresponsive due to the flood of traffic.

    Firewall->>Firewall: Adjust rules to block more traffic
    Note right of Firewall: The Firewall adjusts its rules to block more malicious traffic, but the attack is still ongoing.

    Webserver->>Webserver: Server crashes or becomes unresponsive
    Note right of Webserver: The Webserver is eventually overwhelmed to the point of crashing or becoming unresponsive, completing the DDoS attack.

    %% Final note: Overall impact
    Note right of Webserver: The goal of the attacker is to exhaust the resources of the Webserver, causing downtime or service disruption.
