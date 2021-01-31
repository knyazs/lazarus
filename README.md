# Lazarus

Project Lazarus (code name Lazarus_1329) is a data collaboration project.

It collects data from various data sources and data source types (API, Website, FTP, Database, etc.) into a single place using common architecture and storage. For that purpose, project utilized Azure Synapse Analytics which is modern, all-in-one, solution for data processing, analytics and reporting. Later, data is available to be used directly from a data lake (parquet) or from SQL Pools (raw and historical data).

Azure Data Factory is used for the orchestration, SQL Pool for permanent data storage and history preservation and Spark Pool for custom data processing, such as Web scraping.
