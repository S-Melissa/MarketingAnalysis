# MarketingAnalysis
## A (fake) shop marketing analysis and visualization executed over PowerBI.

The dataset can be found here, under the name Marketing Campain Results : https://www.mavenanalytics.io/data-playground?page=7&pageSize=5

*Unfortunately, not owning a pro licence on PowerBI, I couldn't share a link and had to share screenshots instead.*

**The questions answered in this analysis are : **

**1. What factors are significantly related to the number of web purchases?
2. Which marketing campaign was the most successful?
3. Which channels are under or overperforming?
4. 4. What does the average customer look like?**

-------------------------------

The data cleaning was the following : 

Check of null data
Taking off unrelevant data and standardization of the values :  
  ⦁	Marital status
    ⦁	"Absurd", "YOLO" = Unanswered
    ⦁	"Alone" = Single
    ⦁	"Together" = Couple
  ⦁	Income : empty lines were deleted
  ⦁	Year of Birth : Taking off a few outliers born before 1940
  ⦁	Graduation
    ⦁	"Graduation" = Bachelor
    ⦁	"Basic" = High school 
    ⦁	"2nd cycle" = master
