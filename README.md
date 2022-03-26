# Kickstarting with Excel

## Overview of Project
Louise funded her play Fever through a crowdfunding campaign.  The budget for her play is $10,000.  The campaign came close
to its fundraising goal.  This project is to provide additional analysis to Louise to provide deeper understanding of
the fund raising campaign and its outcomes based on specific criteria.

### Purpose
The purpose of this project is to provide analysis on how different campaigns performed based on their launch date
and funding goals.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To complete the analysis of Outcomes Based on Launch Date, the following steps were performed:

  * In the Kickstarter worksheet, a new column labeled "Years" was added.
  * Using the Year() function, the year was extracted from the "Date Created Conversion Column."
  * A new pivot table based on the Kickstarter data was placed in the new worksheet, "Theater Outcomes by Launch Date."
  * The pivot table was filtered based on "Parent Category" and "Years."
  * The row labels were the months of January through December.
  * The column labels were "successful," "failed," and "canceled."
   ![image](https://user-images.githubusercontent.com/100876517/160254948-e34212d4-d1f6-4a9a-a13a-32c629c70e84.png)
  * The parent category was filtered for "theater."
  * The campaign outcomes were sorted in descending order.
  ![image](https://user-images.githubusercontent.com/100876517/160255018-946f93cc-41d5-4962-970b-746e0875c118.png)
  
A line chart was created from the pivot table labeled Theater Outcomes Based on Launch Date.
![image](https://user-images.githubusercontent.com/100876517/160254715-951c2d49-e2fa-4baa-be32-62d1c142c74c.png)

This chart was saved as a .png file and is part of the resources folder.


### Analysis of Outcomes Based on Goals

To complete the analysis of Outcomes Based on Goals, the following steps were performed:

  * A new worksheet labeled "Outcomes Based on Goals" was created.
  * The new worksheet contains eight columns and twelve rows with the below information
  
      Columns
      * Goal
      * Number Successful
      * Number Failed
      * Number Canceled
      * Total Projects
      * Percentage Successful
      * Percentage Failed

      Rows
      
     ![image](https://user-images.githubusercontent.com/100876517/160255319-2509b569-205d-41e1-81c5-58de84d35494.png) 
      
  * A new pivot table based on the Kickstarter data was placed in the new worksheet, "Theater Outcomes by Launch Date."
  * The pivot table was filtered based on "Parent Category" and "Years."
  * The row labels were the months of January through December.
  * The column labels were "successful," "failed," and "canceled."
  
  * The parent category was filtered for "theater."
  * The campaign outcomes were sorted in descending order.
 


### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
