# malik.github.io memack@my.waketech.edu
School account 
This repository will hold assignments
# About Me 
- I was born and raised in Petersburg Va, Im an Army vet of 6 years, and I have one younger sibling.
## My Intrest 
- I enjoy playing video games, and modifying my car. Im also in school pursuing my cyber security degree
## website I recommend 
- [IBM] (https://www.ibm.com/think/topics/cybersecurity) - a little something about cyber security and what it means.
```mermaid
sequenceDiagram
    participant Attacker1 as Attacker 1
    participant Botnet as Botnet
    participant Attacker3 as Attacker 3
    participant Target as Target Server
    participant Network as Internet

    Attacker1->>Network: Forward requests to Target
    Botnet->>Network: Forward requests to Target
    Attacker3->>Network: Forward requests to Target
    Network->>Target: Forward incoming traffic
    Target->>Target: Process incoming requests
    Target-->>Network: Overwhelmed by excessive traffic
    Network-->>Target: More traffic arriving from multiple sources
    Target->>Target: Server crashes or becomes unresponsive
