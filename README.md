Kickstarting with Excel
## Overview of Project
Help Louise with her project campaign to help identify and determine hidden trends in the data such as which campaign goals were successful, failed or cancelled thus identifying such trends in different criteria’s. For instance, observing and comparing the data trends against different categories, countries and time periods (i.e sorting and filtering the data by “plays” in the US vs Great Britain and by the year & month). 

### Purpose
Perform data analysis on several data to help identify any hidden trends and be able to present it in a more readable and easier to interpret visualized data.
## Analysis and Challenges
There was a learning curve with using Excel in this capacity. For instance, making sure the data was correctly converted to make it readable i.e. the data contained in the “deadline and launched_At” column contained Unix timestamps rather than dates in standard forms which one could’ve mistaken as just random numbers. Using filters and making sure not to omit critical needed data as well as capturing the correct data needed to generate data analysis was a challenge. Lastly, using and applying the formulars correctly and making sure that each cell was populating data from the correct source. As mentioned earlier, this was a learning curve using Excel in this capacity but once I was able understand the functions and formulars it was much easier to utilize and apply them in this project. 
  
### Analysis of Outcomes Based on Launch Date
This analysis focused on parent category “theater” by creating a pivotable dataset containing parent category and year. It was straightforward once all the data was in a readable format and choosing the appropriate pivotable fields in the columns, rows and value section in order to populate the desired outcome.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89875689/132951432-ba8b6062-968a-4304-a1a0-e3558c088d54.png)

### Analysis of Outcomes Based on Goals
This analysis focused on subcategory “plays” and goals in terms of dollar amount ranges (i.e., < $1000, $1000-$4999, $5000-$9999 etc.) Using the “CountIF” formular helped to populate the number of successful, failed and cancelled plays within the different goal amount ranges in the campaign as well the number of percentages within those different criteria for analysis.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89875689/132951439-2242a3b0-d0c8-4ebf-82e1-014605854ca6.png)

### Challenges and Difficulties Encountered
As mentioned earlier, there was a learning curve with using Excel in this capacity. Hence, having to apply the new knowledge into such a large data set was a challenge. For example, the analysis of Outcomes Based on Goals was a challenge having to understand and apply the “CountsIF” formular making sure that data was extracted from the correct source in order to populate the desired outcome. However, after a few errors and trials I was able to conduct the analysis successfully.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
The month of May had the most successful Kickstarter champaign with a point value of 111.Whereas the months of January, March, September, November and December had roughly the same number of canceled campaigns with a point value of 33,33,34,31 and 35 respectively. Hence, if Louise was to launch a theater campaign in the future, she should then conduct it in May as it seems promising for success. 

- What can you conclude about the Outcomes based on Goals?
Most successful projects had a goal of less than $5000 with approximately 76% successful rate whereas goals greater than $45,000 were least likely to succeed. In addition, the percentage successful and percentage failed mirrored each other throughout. Percentage successful started out higher in the beginning but lower in the end while percentage failed started out lower in the beginning but higher in the end. However, I believe that if we further performed analysis based on other outcomes while including other categories, it would help determine/explain some of the gaps in the percentage (successful, failed and cancelled) rates. Currently, this dataset helps to suggest to Louise that she needs to re-evaluate her budget being that successful campaigns were based on small goals.  
- What are some limitations of this dataset?
Per the module challenge, the constraints were performing data analysis based on only two outcomes as follows: Theater outcomes by launch date and outcomes based on goals) thus setting scope limitations. Hence, the dataset evaluation was not a representation of all play projects. Lastly, I believe it would have been beneficial to perform data analysis based on project duration as well. Performing analysis based on project duration would help Louise in her Kickstarter campaign in terms of proper budgeting and achieving successful deliverables.

- What are some other possible tables and/or graphs that we could create?
We could create a column graph to view the data in parallel for easier visualization while adding other pivotable fields i.e subcategory to help analyze other hidden trends in the dataset. 
![Outcomes_vs_Goals (other graphs)](https://user-images.githubusercontent.com/89875689/132951446-e3aa4468-495c-49e5-9dc7-18338b1fc7f6.png)


  

