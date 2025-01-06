Power BI Report server Installation
To start, we required Power BI Premium license.
1.	Download and install PowerBIReportServer.exe from site https://powerbi.microsoft.com/en-us/report-server/
2.	Download and install PowerBIDesktopRS.exe from site https://powerbi.microsoft.com/en-us/report-server/
3.	Configure Report Server below points.
1.	SQL database engine name - Need SQL server details to configure.

![image](https://github.com/user-attachments/assets/fa774895-9c17-4e9e-90c6-53caeb2abcc4)


2. Set web service URL

   ![image](https://github.com/user-attachments/assets/bf41d80c-64cb-4535-b7bc-a700d61357e3)


3. Set web portal URL


![image](https://github.com/user-attachments/assets/d44114bf-55d3-412e-b116-e14263575924)

Before configuration, we required SQL server to setup database engine to access the Power BI report server.

 

Limitation of Power BI Report Server

1. Does not support composite model
2. Need power premium license for report server web portal (Power BI Premium or SQL Server EE with Software Assurance (SA))
3. Power BI RS update release cycle in every 3 months
4. Does not support Q&A
5. Does not support Many-to-many relationships
6. Does not support Full-screen mode
7. Does not support dashboard

Reference - https://learn.microsoft.com/en-us/power-bi/report-server/compare-report-server-service

Currently I don’t have access to save the report in Power BI report server.
Getting below popup.
 
![image](https://github.com/user-attachments/assets/fdc4cec1-b585-4fde-bd31-a0ac28263b64)
