```mermaid
flowchart BT
    Snowflake --> Enterprise
    Databricks --> Enterprise
    Enterprise --> Product
    Product --> Consumers

    classDef platform fill:#E3F2FD,stroke:#1E88E5;
    classDef semantic fill:#E8F5E9,stroke:#2E7D32;
    classDef consumer fill:#FFF3E0,stroke:#EF6C00;

    class Snowflake,Databricks platform;
    class Enterprise,Product semantic;
    class Consumers consumer;
```
