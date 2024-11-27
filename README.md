## Twitter-DashBoard-Project

### Dashboard Link :- https://app.powerbi.com/groups/me/reports/8a554169-cc20-42fe-b98f-ef90948d36dc/3791fe25c66bd30df772?experience=power-bi

## Overview

Twitter analytics provides valuable insights into audience behavior,preferences and engagement with your content,enabling data-driven decision-making for marketing strategies and brand management. By analyzing Twitter data, business can track trends, sentiments, and conversation around their brand, products, or industry, facilitating proactive response and strategic adjustments.Twitter analytics allows for the assessment of the effectiveness of marketing campaigns, helping businesses optimize their content and investment for maximum impact.

### Steps followed For Data Cleaning

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section Use the "Change Type" option in Power Query to alter data types for each column.
- Step 3 : We will convert the time column in new column name [ConvertedDateTime] to get the Date and time.
- Step 4 : Use the "Remove Duplicates" option in Power Query to remove duplicate values from the dataset.
- Step 5 : Use the "Transform Data" tab and the "Remove Rows" option to select the "Remove Blank Rows" option to remove any blank rows from the dataset.
- Step 6 : Now we will create new columns with the help of custom column in power query and we will make Year, Month, Date, Quater, MonthName, DayWeek columns
- Step 7 : We will close and apply our dataset.

### Visual Insights

Step 1: We will use Card visual to display the Tweet count, Engagement Rate, Media Views, Impressions. Drag and drop the "Count of Tweet", "Average of engagement rate", "Sum of media views", "Count of impressions"
![Cards](https://github.com/user-attachments/assets/11c55e9a-e610-4c02-81bd-4a9a7d4833f0)



