1\) What is Power BI and how does it differ from Excel?

Ans:- A business analytics tool by Microsoft that allows you to visualize data, create interactive dashboards, and share insights across an organization.

 	Differences from Excel:



 	Excel is primarily for spreadsheet calculations, while Power BI focuses on data visualization and reporting.

 	Power BI handles large datasets better and can integrate multiple data sources.

 	Power BI supports interactive dashboards, whereas Excel is more static.

 	Power BI uses DAX and Power Query for advanced analytics; Excel uses formulas and pivot tables.





2\) Explain the concept of data modeling in Power BI.

Ans:- Data modeling: Structuring data to define relationships between tables and creating a logical model that supports analysis.

 	Tables, relationships, calculated columns, and measures are used to build a model.

 	Helps in efficient analysis and faster reporting by connecting multiple data sources.





3\) What are the different types of connections available in Power BI?

Ans:- Import: Data is imported into Power BI; fast queries, but requires refresh to update.

 	Direct Query: Data remains in the source; queries run live on source data.

 	Live Connection: Similar to Direct Query but mainly for Analysis Services; no data stored in Power BI.

 	Composite Model: Combination of Import and Direct Query



4\) How do you handle data transformation in Power BI?

Ans:- Use Power Query Editor to:

 	Remove duplicates, filter rows, and clean data.

 	Merge or append queries.

 	Change data types and split columns.

 	Create calculated columns.





5\) What is DAX (Data Analysis Expressions) and why is it important in Power BI?

Ans:- DAX is a formula language used to create calculations in Power BI.

 	Important for:

 	Creating measures and calculated columns.

 	Performing complex aggregations, time intelligence, and dynamic calculations.





6\) Explain the difference between calculated columns and measures in Power BI.

Ans:-	| Feature    | Calculated Column      | Measure                 |

 	| ---------- | ---------------------- | ----------------------- |

 	| Storage    | Stored in table        | Calculated on-the-fly   |

 	| Evaluation | Row by row             | Aggregated dynamically  |

 	| Use Case   | Row-level calculations | Aggregations in visuals |







7\) How do you handle relationships between tables in Power BI?

Ans:- Define relationships in Model View:

 	One-to-one, one-to-many, or many-to-many.

 	Cross-filtering direction can be single or both.

 	Use primary key–foreign key relationships to connect tables.





8\) What is the purpose of a Power BI Gateway?

Ans:- Acts as a bridge between on-premises data and Power BI Service.

 	Allows scheduled refresh and live queries without moving data to the cloud.





9\) How can you schedule data refresh in Power BI Service?

Ans:- Go to Dataset settings → Scheduled refresh.

 	Configure:

 		Frequency (daily/weekly).

 		Time zone.

 		Credentials for the data source.





10\) Explain the concept of row-level security (RLS) in Power BI.

Ans:- Restricts access to data based on user roles.

 	Users see only data that applies to them.

 	Implemented using roles and DAX filters.







11\) What is the Power BI Desktop and how does it differ from Power BI Service?

Ans:- 	| Feature            | Power BI Desktop            | Power BI Service        |

&nbsp;	| ------------------ | --------------------------- | ----------------------- |

&nbsp;	| Platform           | Local application           | Cloud-based             |

&nbsp;	| Main Use           | Data preparation \& modeling | Sharing \& collaboration |

&nbsp;	| Data Refresh       | Manual/Direct Query          | Automated \& scheduled   |

&nbsp;	| Dashboard Creation | Full features               | Limited editing         |







12\) Explain the concept of Direct Query in Power BI.

Ans:- Direct Query keeps the data in the source and queries it live.

&nbsp;	Advantages: always up-to-date, handles large datasets.

&nbsp;	Limitations: slower visuals if the source is slow, restricted DAX functions.







13\) What are Power BI templates and how are they useful?

Ans:- Files with extension .PBIT.

&nbsp;	Contain report structure, visuals, and queries but no data.

&nbsp;	Useful for standardizing reports across projects.





14\) How do you handle incremental data refresh in Power BI?

Ans:- Refreshes only new or changed data instead of the full dataset.

&nbsp;	Configured in Power BI Service for large datasets.

&nbsp;	Improves performance and reduces load times.





15\) What is the role of Power Query in Power BI?

Ans:- Extract, transform, and load (ETL) tool in Power BI.

&nbsp;	Cleans and reshapes data before loading it into the model.

&nbsp;	Supports: merging, appending, pivot/unpivot, and calculated columns.





16\) Explain the difference between calculated columns and calculated tables.

Ans:- 	| Feature    | Calculated Column        | Calculated Table              |

&nbsp;	| ---------- | ------------------------ | ----------------------------- |

&nbsp;	| Output     | Column in existing table | Entire new table              |

&nbsp;	| Storage    | Stored in model          | Stored in model               |

&nbsp;	| Evaluation | Row by row               | Calculated during refresh     |

&nbsp;	| Use Case   | Row-level calculations   | Aggregations, filtered tables |





17\) How do you create custom visuals in Power BI?

Ans:-  Use Power BI Marketplace to import visuals.

&nbsp;	Create visuals using R or Python scripts.

&nbsp;	Use Power BI Developer Tools to develop fully custom visuals.





18\) What are the best practices for optimizing performance in Power BI?

Ans:- Reduce the number of visuals on a page.

&nbsp;	Use star schema for data modeling.

&nbsp;	Avoid calculated columns if measures suffice.

&nbsp;	Filter unnecessary data at source.

&nbsp;	Optimize DAX queries and aggregations.





19\) How can you integrate Power BI with other Microsoft products like Azure and Office 365?

Ans:- Azure: Connect to Azure SQL, Azure Data Lake, or use Azure Machine Learning models.

&nbsp;	Office 365: Embed Power BI in Teams, SharePoint, and use Excel as a data source.

&nbsp;	Supports Single Sign-On and cloud collaboration.





20\) Explain the concept of aggregations in Power BI.

Ans:- Pre-calculated summary data used to improve performance.

&nbsp;	Reduces query load by querying the aggregated table instead of raw detailed data.

&nbsp;	Useful for large datasets.





21\) How do you handle error handling and data quality in Power BI?

Ans:- Use Power Query for data cleansing: remove duplicates, fill missing values, correct data types.

&nbsp;	Use Data Profiling to identify anomalies.

&nbsp;	Handle errors in DAX using functions like IFERROR and ISBLANK.





22\) What is the purpose of Power BI Embedded and when would you use it?

Ans:- Power BI Embedded allows embedding Power BI reports and dashboards in custom applications.

&nbsp;	Useful for ISVs or developers who want to provide analytics to their customers without giving them full Power BI access.

