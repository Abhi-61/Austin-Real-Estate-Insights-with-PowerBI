# Austin, Texas Real Estate Insights with PowerBI

# Introduction
Austin, Texas, has a bustling real estate market, with houses ranging from a few hundred thousand dollars to millions of dollars.
Prospective buyers also come from various backgrounds including single family, couples, businessmen and more. Each prospective buyer looks for unique things in the next house they are looking to buy. These things could include the proximity to a school or the waterfront view.
To summarize such a vast demographic in the market while retaining the essence of the dataset, a Power BI report proves to be a crucial tool in doing so.

# Procedure
The dataset provided is a relational dataset where all the information is consolidated in a single table.
The first and foremost action taken in such a case is to break the data down into simpler and more readable tables, using the Power Query Editor
In Power BI, this involves splitting a table into a singular fact table that contains the skeleton of the dataset, connected to multiple dimension tables that contain the rest of the information.
This relational database schema can also be called a Star Schema.
The Data cleaning procedure reduced the size of the dataset from around 10,000 Kilobytes to around 7,000 Kilobytes. While this might not seem like much since this is a small dataset, performance issues can be mitigated if the dataset was considerably larger.

Once the data has been processed into simpler tables, we begin to create insights. Visualizing insights must be done while keeping in mind the user's technical expertise and how easily they can digest information.
The report was divided into 5 pages, namely Summary Insights, Geolocational Information, Properties available based on proximity to nearby schools and the rating of said schools, and a Key Influencers page.

Each page deals with a certain aspect of the dataset that is meant to cater to a particular demographic's needs. For example, An average single-family looking for new properties in Austin may want to buy a property where there are very good schools nearby for their kids to study in.
At the same time, a prospective buyer with more money to spare might be interested in amenities like a pool or a waterfront view, or properties advertised with a more private living space.

All pages are interactive and the requested information can be retrieved by changing the sliders or clicking on the visualized data.
<img width="1550" alt="image" src="https://github.com/user-attachments/assets/47f4244c-44db-434e-b07a-c6c839398440">

# How to use:
Simply download the Final Report.pbix and sift through the different pages in the report.
All visualized data have been added with adequate legends or self-explanatory titles.
