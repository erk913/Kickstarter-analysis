# Detailed Analysis of Kickstarter Campaigns.  


## Overview of Project

    In this Analysis we will take a deeper look and gain a better understanding of some the factors that have helped or hindered plays from around the world to generate funding.

### Purpose

        The purpose of this analysis was to disect the data provided by the client to gain an understanding of the finicial and operational success or failure of various geners in live and recorded entertainment from different markets around the world.  We will present data that displays the outcome of these plays to generate funding while providing a closer look at some of the factors that either aided or prevented them from being successful. 

## Analysis and Challenges

**Theater Outcomoes based on Launch Date:**

    This analysis was performed by extracting all of our data into a pivot table.  Once the pivot table was created, we factored the data by looking for commonalities shared by our client.  We determined that the two most relevant factors were **Play** and **Year**.  To help provide better isight into the succes or failure of these plays to gain fundning we broke them out into 3 categories over the course of 12 months.  The categories we selected were:  

        1. Successful 
        2. Failed 
        3. Canceled

    The most difficult part of disecting this data was that the date came in [epoch time](https://www.epochconverter.com/) and we had to convert it into a form that would allow us to filter our data by the year it was attmepted.  We used the the following formula to convert the date:  

    **=(((J2/60)/60)/24)+DATE(1970,1,1)**

    Once the date was converted we extracted the the year and created our pivot table.

**Outcomes Based on Goal**

    This analysis was performed by looking at successful, failed, and canceled plays and putting them into classes based on their finicial goal.  We extracted the data from our initial dataset and created a line chart that displays the percentage of successful, failed, and canceled plays with a fundraising goal of $0 and greater than $50,000.  

### Analysis of Outcomes Based on Launch Date
        
        ![Graph of Outcomes](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

        ![Graph of outcomes based on Goal](Outcomes_vs_Goals.png)
        
### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
