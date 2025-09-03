# "F1 Insights" Project: Building a Data Product for Strategic Decision-Making
This project is not just a demonstration of data engineering skills, but the creation of a high-value data source for Formula 1 performance analysis. Its objective is to provide a clean and structured database that serves as a "product" for analysts, data scientists, or team managers to make insight-driven strategic decisions.

My focus is on leading every phase of creating this data product, from ideation to delivery.

## Challenges and Solutions (Project Management Approach)
The main challenge was data acquisition. The lack of a public API or standard HTML structure for web scraping forced me to adopt a problem-solving approach that went beyond conventional methods. This strategic decision was key to ensuring the integrity and scalability of the final data product.

Problem Identification: F1 data is fragmented and in non-standard formats, making it difficult to analyze.

Solution Design:

Instead of relying on limited tools, I explored and validated alternative data extraction methods.

I developed an optimization script with Pandas that automates the download and merge of all tables for each season, reducing the complexity of manual scraping.

The parameterizable function allows setting the URL, save path, final file name, and merge method per driver, generating data sets ready for analysis with a single command.

This approach not only solved the initial problem but also turned data acquisition into a fast, robust, and reusable process, aligned with the needs of a scalable product.

## Data Product Features
The final product is a robust and easy-to-use dataset, designed with a clear purpose: to facilitate analysis.

- Scope: Covers the 2020 to 2025 seasons, providing a consistent timeframe for trend analysis.

- Content: Includes race results, practice sessions, qualifying data, and driver and team performance metrics.

- Value: Data cleansing, integration, and structuring save analysts hours of work, allowing them to focus on insight generation rather than data preparation.

## Roadmap and Lessons Learned
Current Status: The project is complete. The Jupiter notebook serves as a record of the process and technical decisions made to overcome data acquisition challenges.

Key Lessons for a Product Manager:

The Value of Data Engineering: The quality of the final product directly depends on the quality of the underlying data. A PM must understand this principle to make decisions that ensure product reliability.

Strategic Adaptation: A good product leader doesn't adhere to a rigid plan. They must be able to adapt the strategy to meet technical challenges to meet project objectives.
User-Centered Design: A data product is only valuable if it is easy to use. The final design was guided by the need for users to be able to query it efficiently.

## Notes on Previous Versions
This repository includes two initial notebooks showing early attempts at data acquisition with Beautiful Soup and manual workflows.
*Prototype: F1_Season2020_AUS_GP_F1.ipnb, F1_Season_2020_StyriaGP.ipynb* 

These prototypes are maintained as a historical reference for the process, but **the optimized version is the official product version**.
