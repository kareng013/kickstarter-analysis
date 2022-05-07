# **Kickstarting with Excel**

## **Overview of Project**

Louise's play *Fever* came close to it's fundraising goals, she would now like to know how other campagins performed in relation to hers.

### Purpose

The purpose of this challenge is to visualize different campaign outcomes based on their launch date and funding goals. 

This will provide Louise with more information on the length of a campaign required in order to maximize funding goals. This will also provide a realistic goal to maximize funds.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

This analysis looks at the outcome of successful, failed, and canceled fundraisers for the parent category, *Theater*. 

In order to determine the outcomes, a pivot table was created to easily view the outcome for each month. I first created a new column labelled *Years* and used the =Year() function to determine the year the campaign had started. Then I selected the whole table and created a new Pivot table. Within the pivot table fields both Category and Years were filtered out. Then I used the Date Created Conversion field in the rows to determine the outcome by months. Finally, I used the outcomes field in Columns and Values to determine the count of outcomes. 
The last step for the pivot table was to filter out the category for Theater. 

In order to visualize this data, I used the *PivotChart* tool in excel to visualize the data by a line graph. In the x-axis are the months, and the y-axis displays the total amount for each of the outcomes.

![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)

One part of this step I found difficult was creating the Months in the rows area. At first I was dragging down Years, but it would just remove it from the filter and not give me an option to add months. I went back to the module 1 challenge hint, and reading the tip gave me an idea to instead move the *Date Created Conversion* down to rows. From there I filtered out for months, and thus was successful in achieving outcomes by Months. 



### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?