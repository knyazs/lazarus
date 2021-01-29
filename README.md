# Lazarus

Project Lazarus uses Azure Synapse Analytics to implement data extraction from various sources, such as Web sites (scraper), APIs, FTPs, databases, etc. After extraction data is stored in data lake as parquet file as well as loaded into Azure Synapse SQL Pool for various applications.

Azure Data Factory is used for the orchestration, SQL Pool for permanent data storage and history preservation and Spark Pool for custom data processing, such as Web scraping.
