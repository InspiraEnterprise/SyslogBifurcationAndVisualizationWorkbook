# Data-Comparison-Hourly-Workbook-
Building a custom Sentinel Workbook to get an overview of data Comparison on Hourly basis of log sources 

# Description
The Data Ingestion Comparison Hourly workbook offers a comprehensive view of ingested data, presenting the total data volume and ingestion amounts in GB, categorized by each hour. This breakdown helps in monitoring and comparing data ingestion trends over time, ensuring visibility into hourly ingestion patterns and potential anomalies.
 
# Business Requirements

•  Real-Time Monitoring of Data Ingestion Trends: The workbook provides visibility into hourly data ingestion volumes, allowing businesses to track and monitor trends in real-time, ensuring that data from critical sources is ingested without delays.

•  Proactive Identification of Anomalies: The workbook helps identify inconsistencies or unusual drops in data ingestion volumes, enabling early detection of potential issues with data connectors or source systems, ensuring timely resolution.

•  Data Volume Optimization and Cost Management: By offering detailed insights into hourly data volumes in GB, the workbook allows businesses to optimize ingestion processes, helping to manage and forecast Azure consumption costs more effectively based on data usage patterns.

 
# Prerequisites
•	An active Azure subscription

•	Contributor RBAC role assigned to a development resource group

•	An active Sentinel workspace

•	A Log Analytics workspace linked to Sentinel

•	Basic Required Tables (Syslog, Events, Security Events, Azure Activity) 

 
# Setup Guide
The following provides step-by-step instructions to deploy the Workbook:
 
**Step 1: Access Microsoft Sentinel**
 
• Sign in to the Azure portal: https://portal.azure.com.

• In the search bar, type Microsoft Sentinel and click on it from the results.

• Select the appropriate Sentinel workspace where you want to deploy the custom workbook.

**Step 2: Navigate to the Workbooks Section**
 
• Once in the Sentinel workspace, on the left-hand panel, scroll down and click on Workbooks under the Threat Management section.

**Step 3: Create a New Workbook**
 
• At the top of the Workbooks page, click on the + New button to start creating a custom workbook.

• You’ll now see the workbook editor interface, where you can start designing your custom workbook.

**Step 4: Import a Custom Workbook Template**
 
• If you already have a custom workbook template in JSON format, click on the "Advanced Settings" gear icon (⚙️) in the top right corner of the workbook editor.

• In the menu, choose "Edit as Code".

• Copy your custom workbook JSON code and paste it into the code editor.

• Click Apply to load the template into the workbook.

**Step 5: Save the Workbook**
 
• Once your custom workbook is ready, click Save at the top of the page.

• Provide a name and description for your workbook.

• Select Save to Microsoft Sentinel or My Workbooks to choose the visibility of the workbook. Saving it to Sentinel will make it available to all users in the workspace.
 
# Solution Insights: Workbook Visuals
![image](https://github.com/user-attachments/assets/769e520b-84d8-4f13-bce8-c7bf6aa9dd56)
