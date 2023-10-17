# amazon-in-sales-analysis
a business analysis initiative aimed at understanding and optimizing Amazon's sales performance in the Indian market. This project includes data analysis, reports, and insights to drive data-informed decision-making and strategic planning for Amazon's operations in India.

# OBjective
![pb](https://github.com/Benalayanaim/amazon-in-sales-analysis/assets/98695786/6cde82e2-2bd9-4e17-b67e-b50e447c49da)

# Data Warehouse
-We chose the  snowflake schema for several reasons in our data modeling process. The

snowflake schema is a variant of the star schema that offers additional normalization of

dimensional tables. Furthermore, this model have many advantages such:

- It is particularly suitable when dealing with one fact table and multiple related

dimensional tables

- It subdivides tables into fact and dimensional tables, providing a clear separation between

measures and dimensions.

- The snowflake schema offers flexibility in terms of data usage.

- The dimensional tables are shared across multiple fact tables. This reduces redundancy

and promotes data consistency

![trrrrrr](https://github.com/Benalayanaim/amazon-in-sales-analysis/assets/98695786/f15aea35-a816-490c-a39e-ffcefe0a2fe8)

# ETL (Extract Transform Load) 

-is a data integration process that transfers raw data from a source

system, prepares it for downstream use, and sends it to a database, a data warehouse or target

server. In this process the transformation of the data takes place on an intermediate server before

loading on the target. ETL process involves complex data transformations that require extra space

to temporarily stage 17 the data between the data sources and the data warehouse. To handle this

problem, we need to have a Data Staging Area (DSA) to quickly extract data from and minimize

the impact of the sources.

![etl](https://github.com/Benalayanaim/amazon-in-sales-analysis/assets/98695786/c6e07b3e-f83e-40fd-ab5b-b488b837a4f8)


# Data Visualization
