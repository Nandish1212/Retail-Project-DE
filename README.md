# Retail Sales-Project-DE
BUSINESS REQUIREMENTS
1. We have to build an end-to-end data pipeline for the retail clients
2. We have data coming from multiple data sources, and we need to bring the data into the data lake.
3. We have transaction data available in AZURE SQL DB.
4. WE have store and product data available in AZURE SQL DB.
5. WE have customer data coming from API - JSON FORMAT.

**The Data flow source to Final Dashboard.**
<img width="1291" height="522" alt="image" src="https://github.com/user-attachments/assets/41322251-75a4-400d-9e93-4572215dbc63" />
**Steps:**
**Step-1: **The data is copied from the SQL database and API JSON to ADLS. 
By using the data factory, I created a pipeline that consists of copy activities.
**Step-2: **Mounting the data into the databricks using the mount. U can find the code to mount in the HTML file given.
**Step-3: **Using the Meddalion architecture transformed the data from raw to cleaned usage for the end user.
**Step-4: **Downloaded the CSV file, the final transformed data, i.e Gold Layer.
**Step-5: **Finally created an interactive dashboard using Power.

**Final Dashboard**
<br><img width="1215" height="676" alt="image" src="https://github.com/user-attachments/assets/7202b166-d832-48c4-9380-6ff621a947ce" />
