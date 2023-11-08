# AtliQ-Hardware Project

### Table of Contents:
[Tableau Dashboard](https://public.tableau.com/app/profile/julynda.vaughn/viz/AtliQCustomerAnalysisv6_2/AtliQCustomerDemographics)

[Project Visualizations](https://github.com/julyndav/AtliQ-Hardware/tree/main/Analysis%20Images)

[AtliQ Decomposition Plan](https://github.com/julyndav/AtliQ-Hardware/blob/main/AtliQ%20Decomposition%20Plan%20Project.pdf)

[Jupyter Notebook](https://github.com/julyndav/AtliQ-Hardware/blob/main/AtliQ%20Customer%20Analysis%20Final.ipynb)
<br>
<br>
<br>


# AtliQ Hardware Customer Analysis
### AtliQ Project Analysis Plan 

The TTWC team assigned to AtliQ will conduct the necessary research, and create informative dashboards that AtliQ will be able to use later. Certain sections of the TTWC team will select one of the three above areas to focus on. My team is responsible for Customer Analysis. 

During the Customer Analysis, customer segmentation will be used to understand the purchasers and gain an understanding on more effective sales, marketing, and personalization strategies. Each segment can answer a myriad of questions that the company may have. To further help with the segmentation, we will connect the customers to the products and sales data to give a better overview of the customer focused analysis.  

To really embrace the real-world feel and to set good habits, the decomposition plan was created as if I was an actual Analyst for TTWC.  Below is a snippet of the decomposition plan, you can see the entire plan from the link in the Table of Contents. 

![Decomposition Plan](https://github.com/julyndav/AtliQ-Hardware/blob/main/readmepics/decomp.png)
<br>
<br></br>
### To help with the intial analysis we used software for get a visual of the dataset tables and how they relate to each other.
![Table Relationships](https://github.com/julyndav/AtliQ-Hardware/blob/main/Analysis%20Images/Database%20flowchart.png)

The goal is to segment the customer data on various metrics and create an actionable dashboard. This will allow AtliQ to gain a better understanding of their customers' habits and possibly give insight on new, potential markets. 




<p></p>
<i> *Note:  TTWC is a fictional company.  This entire analysis was done for course project completion to simulate real-world work environment.</i>
<br>
<br>
<hr style="border:2px solid black">

### SQLite required to connect to the supplied database:
![Database Connection](https://github.com/julyndav/AtliQ-Hardware/blob/main/readmepics/dbase%20connection.png)


### Now to import the libraries that will be used for the analysis:
![Import Libraries](https://github.com/julyndav/AtliQ-Hardware/blob/main/readmepics/libraries.png)

<br>
<hr style="border:2px solid black">

## Analysis Process:
1. Data cleaning and processing
2. Geographic segmentation: <i>(used SQL to group the database tables)</i>
   <blockquote> Some good questions to ask are:<br>
                What areas have the most customers?<br>
                How many customers are there in total?
                What countries contain AtliQ customers?</blockquote>
3. Cohort Analysis with Churn rate

Project analysis was closed out with an overall conclusion and insights on the loyalty of the company's customer base.  From the 2019 data (the last year data was collected), AtliQ retrained 76% of it's customer base. Customer trends and purchasing behaviors for the 5 year time line were also analyized to give the company better insights on successful market regions and which products helped boost revenue.  
<br></br>
<hr style="border:2px solid black">
<br></br>

### Resources used for the completetion of the project:
<blockquote>
<b>Project Resources:</b>
<li> Quick DBD for database flowchart layout</li>
<li> https://learnsql.com/blog/grouping-data-in-microsoft-sql-server/</li>
<li>https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.to_csv.html</li>
<li>https://learnsql.com/blog/how-to-join-two-tables-in-sql/</li>
<li> Markdown Cheat Sheet - https://medium.com/analytics-vidhya/the-ultimate-markdown-guide-for-jupyter-notebook-d5e5abf728fd</li>
<b>Tableau Resources:</b>
<li> https://www.tableau.com/blog/LOD-expressions</li>
