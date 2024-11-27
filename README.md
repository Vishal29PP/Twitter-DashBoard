## Twitter-DashBoard-Project

### Dashboard Link :- https://app.powerbi.com/groups/me/reports/8a554169-cc20-42fe-b98f-ef90948d36dc/3791fe25c66bd30df772?experience=power-bi

## Overview

Twitter analytics provides valuable insights into audience behavior,preferences and engagement with your content, enabling data-driven decision-making for marketing strategies and brand management. By analyzing Twitter data, business can track trends, sentiments, and conversation around their brand, products, or industry, facilitating proactive response and strategic adjustments. Twitter analytics allows for the assessment of the effectiveness of marketing campaigns, helping businesses optimize their content and investment for maximum impact.

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

Step 2 : We will use line chart to display the count of tweet by dayweek. Drag and drop the "Dayweek" in x-axis and "Count of Tweet" in y-axis.

![Linechart1](https://github.com/user-attachments/assets/f8ac884a-370b-4695-8389-b2bf84821c4b)

Step 3 : We will again use the line chart to display the sum of impression by dayweek. Drag and drop the "Dayweek" in x-axis and "Sum of impression" in y-axis.

![linechar2](https://github.com/user-attachments/assets/d6661e92-940c-4679-aef9-6e5b3c95e696)

Step 4 : We will use Clustered Column chart to display the count of media views and count of media engagements by Dayweek. Drag and drop "Dayweek" in x-axis and "Count of media views", "Count of media engagements" in y-axis.

![Clchart](https://github.com/user-attachments/assets/2149c111-6359-4ec0-957b-be8c527c4396)

Step 5 : We will use the Clustered Column chart to display the count of tweet by dayweek. Drag and drop the "Dayweek" in x-axis and "Count of tweet" in y-axis.

![ccl2](https://github.com/user-attachments/assets/cd620387-ecb0-45da-aa1d-e74db5848694)

Step 6 : We will use the Clustered bar chart to display the sum of url clicks by tweet. Drag and drop the "Tweet" in x-axis and "Sum of url clicks" in y-axis.

![clusbarchart](https://github.com/user-attachments/assets/d83aa3ce-114e-4172-ab2e-8a1ca80cfebf)

Step 7 : We will use the pie chart to display the count of hashtag clicks, url clicks, user profile clicks. Drag and drop the "Count of hashtag clicks", "Count of url clicks", "Count of user profile clicks" in values.

![piechart](https://github.com/user-attachments/assets/715b39dc-4610-4698-9cd3-f5edd6010e44)

Step 8 : We will use the Gauge to display the sum of likes. Drag and drop the "Sum of likes" in values.

![gauge1](https://github.com/user-attachments/assets/99cfc057-e7f0-432b-ba60-26155f956300)

Step 9 : We will again use the Gauge to display the sum of retweets. Drag and drop the "Sum of retweets" in values.

![gauge2](https://github.com/user-attachments/assets/38e9f7c2-0c09-498b-bc71-95d32cc24e41)

Step 10 : We will use slicer to display month name. Drag and drop the "MonthName".

![slicer](https://github.com/user-attachments/assets/18572359-41f0-4b73-86d9-799af014db8a)

### Snapshot of Dashboard (Power BI Services)

![Project dashboard](https://github.com/user-attachments/assets/163af122-ef20-49d2-a4f5-88dda75ffe35)



