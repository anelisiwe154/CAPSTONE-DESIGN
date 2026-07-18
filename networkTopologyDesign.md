graph TD
    A["Kali Linux (Attacker)"] --> B["Ubuntu (Future SIEM/Honeypot)"]
    C["Windows (Victim)"] --> B
    B --> D["Planned Cloud Wazuh SIEM"]
    D --> E["SOC Analysts"]
    F["Claude Desktop"] --> G["MCP Server (Middleware)"]
    G --> A
