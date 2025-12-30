# Consumer Complaints Dashboard – Data Cleaning & Analysis (Power BI)

## Why I built this
This project started as a dashboard task but quickly became a **data cleaning learning experience**.

The dataset looked simple initially, but while building KPIs and charts, multiple issues surfaced due to **messy real-world data**.

## Key Challenges Faced
- Columns containing **text, numeric values, nulls, and blanks together**
- Date columns with **multiple formats, nulls, and errors**
- Categories appearing blank in visuals despite no visible blanks in data
- Percent-based KPIs behaving incorrectly due to inconsistent base data
These issues directly affected charts, KPIs, and filtering logic.

## What I Learned 
- Data cleaning is critical before trusting KPIs or visuals
- A visual rendering does NOT mean the data logic is correct
- Mixed data types in a single column can silently break charts
- Percentages can be misleading if nulls and “N/A” values are not handled properly
- Sometimes replacing a KPI (Avg Response Days instead of Timely Response %) improves clarity
- Sorting and Top N logic matter even after filtering

## Dashboard Pages Overview
### Page 1 – Overview 
- Total complaints
- Consumer disputes
- Unique issues
- Average response time (days)
- Yearly and product-level trends

### Page 2 – Issues
- Top companies by complaints
- Top complaint issues
- State-wise complaint distribution
- Timely vs untimely responses

### Page 3 – Complaints 
- Company-wise complaint performance
- Complaint contribution by product & issue
- Response time trends
- Complaint outcome by product

## Tools & Skills Used
- Power BI
- Power Query (Data Cleaning)
- DAX Measures (COUNT, DISTINCTCOUNT, AVERAGEX)
- Business-focused dashboard design
- Handling real-world messy data

## Key Takeaway
This project taught me that **real-world data is messy**, and the ability to clean, validate, and question data is more important than building complex visuals.

## Preview
Dashboard screenshots available in the `images` folder.
