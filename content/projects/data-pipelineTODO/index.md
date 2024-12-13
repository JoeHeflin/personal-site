---
title: Building a customizable ETL pipeline
type: page
description: Click on me to see the content.
topic: career
---
My goal for this project was to build a flexible data processing pipeline that could clean, transform, and validate transaction data from a variety of sources. The main focus was to automate as much of the data cleaning process as possible, while enabling necessary manual intervention in a stable and simple manner.

The pipeline has several key functions to transform and validate data in specific ways, such as shortening text fields, verifying uniqueness, converting currency formats, and ensuring date consistency. When data is incomplete, the system isolates these records for manual review and resumes processing remaining entries. The pipeline is configuration-driven, using YAML and JSON files to control the transformation rules. This setup not only keeps things flexible but also enables future updates and extensions without modifying the source code.

Working on this project reinforced a few key skills. Using Python and the Pandas library in particular was the bulk of it. Using YAML and JSON for configuration management was also a solid exercise in building adaptable, reusable code that can work across different scenarios. I also spent time improving the project structure to keep the code organized and test-friendly, which helped make the system more maintainable and easier to debug.
    
I learned a lot along the way. The source data was rarely complete or clean, so building a system that gracefully handles errors and automatically resumes where able was crucial. It also highlighted the importance of logging and having clear error handling in place, making troubleshooting simpler. The experience also showed how effective a configuration-driven design can be in creating flexible solutions that can adapt to changes in business rules without needing code changes.

In short, this project built up skills in data processing, error handling, and flexible configuration, resulting in a reliable and user-friendly pipeline that’s easy to maintain and scale.

[GitHub Repository for Project](https://github.com/JoeHeflin/transaction-ETL-project/)
