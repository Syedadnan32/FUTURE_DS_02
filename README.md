# FUTURE_DS_02      
**Task 2 Completed : Customer Support Ticket Analysis**    

**Project: End-to-End Customer Support Ticket Analysis**

This project showcases a comprehensive data analysis workflow, from initial data handling and cleaning to insightful visualization and actionable recommendations, all aimed at optimizing customer support operations. My approach leveraged a combination of Python for robust data manipulation and Excel for preliminary analysis and supplementary visualizations, culminating in an interactive Tableau Dashboard.

**1. Data Preparation & Preprocessing (Google Colab - Python & Excel)**

**Objective**: To transform a raw, messy customer support ticket dataset into a clean, structured format for in-depth analysis.

Initial Assessment: Loaded customer_support_tickets.csv into a Pandas DataFrame in Google Colab, revealing its shape (8469 rows, 17 columns) and initial rows.

Handling Missing Values: Identified significant null values in 'Resolution', 'First Response Time', and 'Time to Resolution' columns. Strategically dropped rows with null values in Python, resulting in a clean dataset of 2769 entries.

Excel for Initial Data Scan & Validation: Utilized Excel for a quick initial scan of the dataset, cross-referencing column types and identifying potential formatting inconsistencies before or in conjunction with Python cleaning. This step helped in understanding data nuances visually.
Text Preprocessing Foundation: Initiated the setup for text analysis using NLTK in Python, including downloading necessary resources (punkt, stopwords) to prepare for extracting insights from 'Ticket Description' or 'Ticket Subject'.

**2. Exploratory Data Analysis (EDA) & Insights (Google Colab - Python & Excel)**

Summary Statistics: Performed a comprehensive describe(include='all') in Python to understand the distribution and unique values of all columns, highlighting key categories like 'Refund request' as the top Ticket Type and 'Network problem' as the top Ticket Subject.
Distribution Analysis: Analyzed the distribution of 'Ticket Priority', 'Ticket Status', and 'Ticket Channel' in Python, identifying 'Critical' as the top priority and 'Email' as the most used channel.

Time-Based Performance: Grouped data by 'Ticket Priority' in Python to calculate average 'Response Hours' and 'Resolution Days', providing insights into service level agreement adherence across different urgency levels.
Excel for Quick Aggregations & Visualizations: Leveraged Excel's pivot table functionality for quick aggregations and basic charts to explore initial trends, validate Python outputs, and perform ad-hoc analyses on specific columns or time periods. This provided rapid insights and a complementary perspective to the Python-based EDA.

**3. Interactive Data Visualization**

**Objective**: To translate the complex analysis into an intuitive and interactive dashboard for stakeholders. 

**Key Visualizations Include:**      
**Overall Performance Metrics**: Prominently displaying Ticket Count (2770) and Average Customer Satisfaction Rating (2.99).       
**Demographic & Channel Analysis**: "Tickets by Gender" pie chart and "Ticket Channels" horizontal bar chart (Email, Phone, Social Media, Chat).       
**Time-Series Trends**: "Tickets by year" bar chart (2020, 2021) and "Ticket volume Over Time" line chart (Jan-Dec).       
**Issue Identification**: "Status By Ticket Type" area chart showcasing various ticket subjects like "Account access", "Battery life", "Network problem", etc.        
**Prioritization & Efficiency**: "Ticket Count by Priority" bar chart for Critical, High, Low, Medium priorities.        
**Interactivity**: Dynamic filters for 'Years', 'Gender', and 'Channels' to allow users to drill down into specific data segments. 

**Impact: This comprehensive dashboard empowers support teams to:**     
    Quickly identify and prioritize recurring issues.
    Improve resolution efficiency by understanding bottlenecks.
    Optimize resource allocation based on channel usage and satisfaction.
    Drive data-driven decisions for enhanced customer experience.

**Tools & Technologies:**    
**Python**: Pandas, Matplotlib, Seaborn, NLTK, WordCloud      
**Google Colab**: For robust data processing and EDA      
**Microsoft Excel**: For initial data exploration, validation, and supplementary analysis/visualizations      
**Microsoft Excel**: For interactive dashboard creation and advanced data visualization            
**CSV-based Dataset Analysis**       
       This project highlights a versatile skill set, showcasing my ability to utilize multiple industry-standard tools to conduct a thorough data analysis, from data ingestion to actionable insights, ultimately 
         driving business improvements.

**📎 Dataset**
🔗 Customer Support Ticket Dataset (Kaggle)   

**📬 Contact**
   **Syed Adnan**      
        **LinkedIn** - www.linkedin.com/in/syedadnan1230|      
           **GitHub** - github.com/Syedadnan32/FUTURE_DS_02
       
