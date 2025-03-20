# Data-Analytics_Deloitte-Forage-Internship

# Task 1 
Using a data unification algorithm, the tech team at our client, Daikibo, has converted all telemetry data collected from its 4 factories:

Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 mins. Daikibo has been collecting this data for one month (May 2021) and they've shared this data in the form of a single JSON file.

The reason the client wanted to collect telemetry was to answer 2 questions:

1.In which location did machines break the most?
2.What are the machines that broke most often in that location?

## Insights and Analysis
1. In Daikibo Factory Seiko (Osaka, Japan) machines break the most following with Daikibo Shenzhen (Shenzhen, China).
2. LaserCutter and Laserwelder broke the most

# Task 2

We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:

Factory
Job Role
Equality Score (integer; ranging between -100 and +100; 0 is ideal)
Here is your task:

Create a 4th column (Equality class), classifying the equality score into 3 types:
Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)
Examples:

10 → Fair
-9 → Unfair
-30 → Highly Discriminative
