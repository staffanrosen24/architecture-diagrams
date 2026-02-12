# Enterprise Semantic Architecture

```mermaid
flowchart BT

    Snowflake --> Enterprise
    Databricks --> Enterprise
    Enterprise[Enterprise Semantic Layer] --> Product[Product Semantic Views]
    Product --> Consumers[Consumers]
```
