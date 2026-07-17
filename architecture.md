```mermaid
graph TD
    A[Simulated Endpoints] --> B[Honeypots]
    B --> C[SIEM Wazuh Elastic]
    C --> D[Elasticsearch Database]
    D --> E[Kibana Dashboard]

    F[Claude AI] --> G[MCP Server]
    G --> H[Kali Linux Tools SQLmap Aircrack-ng Hydra]
    H --> C

    E --> I[SOC Analysts]
```


