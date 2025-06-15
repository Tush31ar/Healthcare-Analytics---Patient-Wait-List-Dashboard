1. Healthcare Analytics - Patient Wait List Insights Dashboard

	An interactive, dynamic data visualization tool designed to analyze and uncover insights from Patient Wait List data, with a focus on Inpatient, Outpatient, and Day Case categories. It enables users to explore trends, identify bottlenecks, and support informed decision-	          making for improving access and efficiency in patient care.
   

2. Summary:
   
   The Patient Wait List Dashboard is a visually engaging and analytical Power BI report designed to help users providing a comprehensive view of patient waiting      lists to support operational planning and service improvement. It tracks the current status of patients awaiting care, segmented into Inpatient and Outpatient      categories, offering insights into volumes and average wait times. The dashboard also presents a historical monthly trend analysis to identify patterns or          surges over time. Additionally, it includes detailed breakdowns by medical specialty and patient age group, helping stakeholders identify service bottlenecks,      prioritize high-risk groups, and allocate resources more effectively.

3. Tech Stack:
   
	The Dashboard was built using the following tools and technologies:
	* 📊 Power BI Desktop - Main data visualization platform used for report creation.
	* 📂 Power Query - Data transformation and cleaning layer for reshaping and preparing the data.
	* 🧠 DAX (Data Analysis Expressions) - Used for calculated measures , dynamic visuals and conditional logic.
	* 📝 Data Modelling - Relationships established among tables (Inpatients, Outpatients and Mapping_Specialty) to enable cross-filtering and aggregation.
	* 📁 File Format - .pbix for development and .png for dashboard reviews.

  
  
4. Data collection and preparation:
   
    Collected patient wait list data capturing case type (Inpatient/Outpatient), age group, medical specialty, and wait times for both the current and prior            months, enabling month-over-month comparison and in-depth analysis across key dimensions.

5. Dashboard Design:
   
    -Summary
   
   ![Patient Wait List - Summary](https://github.com/user-attachments/assets/24155ead-1a52-42fc-b5ad-a6dc095ddbcd)

	* KPIs provide a quick comparison of current vs. previous month wait list counts for trend monitoring.
	Donut chart shows case type proportions, supporting capacity and resource planning.
	* Bar chart illustrates age distribution across wait time bands, enabling targeted service improvements.
	* Multi-row card highlights the top 5 specialties with the highest wait times to guide prioritization efforts.

    -Detailed View
	* Detailed table enables granular analysis to identify high and low-performing specialties, age groups, and wait time bands.
	* Case type trends across specialties reveal patterns in patient demographics and service utilization.
	* Wait time comparisons by case type help uncover bottlenecks and support patient flow optimization.
