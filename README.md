# ecommerce-analytics
dbt + BigQuery analytics model of an e-commerce business: tested star schema, CI/CD, and a governed semantic layer that Claude queries via MCP, with measured answer accuracy.

Trusted e-commerce metrics, for people and AI

This project models an online retailer's orders, products, customers and inventory as a tested, documented star schema in dbt on BigQuery. Every metric has one agreed definition, so dashboards and AI assistants give the same answer.

Dimensional model (facts and dimensions with stated grain, SCD2 product history)
Automated tests and CI on every pull request
Incremental, partitioned models that cut query cost by X%
Claude connected through MCP to the governed marts only.
