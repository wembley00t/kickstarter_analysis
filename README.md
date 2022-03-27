# Kickstarting with Excel

## Overview of Project
Louise funded her play "Fever" through a crowdfunding campaign.  The budget for her play is $10,000.  The campaign came close
to its fundraising goal.  This project is to provide additional analysis to Louise to provide deeper understanding of
the fund raising campaign and its outcomes based on specific criteria.

### Purpose
The purpose of this project is to provide analysis on how different campaigns performed based on their launch date
and funding goals.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To complete the analysis of Outcomes Based on Launch Date, the following steps were performed:

  * In the "Kickstarter" worksheet, a new column labeled "Years" was added.
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
      
  * The COUNTIFS() function was used to populate the "Number Successful," "Number Failed," and "Number Canceled" columns. 
    The criteria for the COUNTIFS() function was based on the "Kickstarter" worksheet using the "goal," "outcome" and subcategory
    of "plays."  An example of the function for the "Number Successful" is below.
    
    ![image](https://user-images.githubusercontent.com/100876517/160288457-309be781-9ab7-4c9f-aae0-513cd6d9463f.png)
    
  * The "Total Projects" column was completed by using the SUM() function to add the columns "Number Successful," "Number Failed"
    and "Number Canceled."
  * The percentages of successful, failed and canceled projects was calculated.
  * A line chart labeled "Outcomes_vs_Goals" was created to show the relationship of the percentage successful, failed or canceled
    on the y-axis to the goal amount on the x-axis.
  ![image](https://user-images.githubusercontent.com/100876517/160288241-66cf08e7-3bf1-47ed-98e8-38bc18955bfc.png)
  
  This chart was saved as a .png file and is part of the resources folder.
  

### Challenges and Difficulties Encountered

This project was straight forward.  Possible challenges for this project could include the application of the YEAR() and COUNTIFS() functions
if not familiar with the functions.  The pivot table used for the Outcomes Based on Launch Date could also be a challenge.  The pivot table 
required filtering "Outcomes" for the proper outcomes of "Successful," "Failed" and "Canceled."  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  The most successful theater outcomes based on launch date was in the month of May closely followed by the month of June.  The number
  of canceled outcomes was low and fairly consistent over the 12 month period with a slight uptick reflected in the month of January.

- What can you conclude about the Outcomes based on Goals?
  
  Most of the activity or 85% occurs within the $0 to $9,999 goal range.  The most successful outcomes were those with a goal of $4,999 or less.
  This goal range of $0 to $4,999 reflected a 73% to 76% success rate.
   
- What are some limitations of this dataset?   
 
  This dataset does not reflect the reason some plays were successful and others were not even within the same goal range.  A subcategory for 
  type of play may give additional information.  

- What are some other possible tables and/or graphs that we could create?

 Other possible tables and/or graphs could include a further breakdown of the successful outcomes to show the number of backers and average donation
 compared to the failed outcomes.  A table or graph to see if there is a correlation between launch date and goal amount based on outcome 
 could also be helpful.  
