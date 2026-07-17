## Desciption 
This flowchart illustrates the penetration testing process automated by Claude AI via MCP. It begins with reconnaissance, moves through exploitation and credential harvesting, and culminates in domain compromise. Defensive detection and response workflows are triggered at each stage.

flowchart TD
    Start([Start Simulation]) --> Recon[Reconnaissance & Enumeration]
    Recon --> Exploit[Exploitation (SQL Injection, Samba Root)]
    Exploit --> Harvest[Credential Harvesting & Cracking]
    Harvest --> Compromise[Domain Compromise]
    Compromise --> Detect[SIEM Detection & Correlation]
    Detect --> Respond[Incident Response Workflow]
    Respond --> End([End Simulation])
