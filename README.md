# Navigating the Cloud - AWS

In this project, I will be navigating the cloud using Amazon Web Services (AWS) to help MSBA Financial group make recommendations on its portfolio for the next fiscal year. By the end of this project, I will have demonstrated:
1) how to build a complete end-to-end pipeline in the cloud data architecture for MSBA Financial Group.
2) how to clearly explain MSBA Financail Group's prototyped cloud data architecture.
3) how to think deeply and critically about MSBA Financial Group's objectives.

Business Case (Project Prompt): "You work as an analyst for MSBA Financial Group, a specialized investment firm. MSBA holds information on publicly traded companies from three different sources, saved in the following tables: 
- A Vendor, DataCorp, provides a collection of data from company balance sheets and income statements into the table, datacorp_financials.csv.
- Analyst A is responsible for calculating certain important accounting ratios, using data from DataCorp. These ratios are stored in a table called msba_fg_ratios.csv.
- Analyst B is responsible for tracking publicly traded companies that have filed for bankruptcy. They store this data in a table called msba_fg_bankruptcy.csv. 

The new Chief Information Office (CIO) is frustrated with the decentralized nature of MSBA’s data architecture. She has tasked you with prototyping a cloud-native data architecture in AWS that will achieve the following objectives: 
- Provide a landing place for incoming data of various data types, sizes, and sources. 
- Provide a data warehouse that can facilitate a more centralized “single source of truth” of data for the company’s analyst teams to use regularly.
- Make future data ingestion easy to replicate or automate.
- Connect to machine learning tools that can perform cursory exploratory data analysis, and create a machine learning model that can predict a company’s likelihood of bankruptcy in the next fiscal year.
- MSBA is considering 10 companies for a new portfolio. Use the model to make predictions and determine each of the 10 companies’ likelihood of filing for bankruptcy."

Click this link to watch the full presentation: https://youtu.be/DLM9gBxlo_g
