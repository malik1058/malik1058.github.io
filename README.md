# malik.github.io memack@my.waketech.edu
School account 
This repository will hold assignments
# About Me 
- I was born and raised in Petersburg Va, Im an Army vet of 6 years, and I have one younger sibling.
## My Intrest 
- I enjoy playing video games, and modifying my car. Im also in school pursuing my cyber security degree
## website I recommend 
- [IBM] (https://www.ibm.com/think/topics/cybersecurity) - a little something about cyber security and what it means.
sequenceDiagram
    participant Attacker as Attacker
    participant Botnet as Botnet (Multiple Bots)
    participant Firewall as Firewall
    participant Webserver as Webserver

    Attacker->>Botnet: Command to flood traffic
    Botnet->>Webserver: Send large volume of traffic
    Botnet->>Webserver: Send more requests
    Webserver->>Firewall: Forward incoming requests
    Firewall->>Firewall: Inspect traffic for DDoS
    Firewall-->>Webserver: Allow or block requests based on rules
    Webserver->>Webserver: Overwhelmed by requests
    Webserver-->>Firewall: Alert: Resource overuse
    Firewall->>Webserver: Continue blocking requests
    Webserver->>Webserver: Server crashes or becomes unresponsive
