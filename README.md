# An Analysis of Kickstarter Campaigns

#### Steps taken for analysis

From a dataset with kickstarter campaigns, I performed data analysis on several thousand crowdfunding projects to uncover any hidden trends.

1. First, understand what the dataset is trying to tell us. Columns to focus on include:

  a. The Goal column tells us how much money each campaign will need to succeed.
  
  b. The Pledged column tells us how much each campaign actually made.
  
  c. The Outcomes column tells us if the campaign met its goal.
  
  d. The Country column lists the country in which the campaign was started.

2. To start with the analysis, create two excel sheets showing results based on launch date and goals of each campaigns.

3. Filter and format based on conditions accordingly.

4. Ensure to debug errors such as "#DIV/0!" using "=IFERROR(value,value_if_error)" formula. This formula catches errors and replaces them with a user-defined input. 

5. Next, to vbisualize data, use pivot tables and charts.

** To find specific kickstarters use VLOOKUP which lets us pull specific columns from our main dataset into a new sheet without having to search for each column and then copy and paste the data.

![Categoryoutcomes](https://github.com/Kalkidanalemaye/Kickstarter-analysis/blob/master/Categoryoutcomes.png)
![Outcomes](https://github.com/Kalkidanalemaye/Kickstarter-analysis/blob/master/Outcomes.png)
The kickstarters with lower goals were more succesful achieving it as seen on the descriptive statistics sheet.
Recommendation: Set lower goal for startup and have a limited time for the campaign. 
## Focus of this project

For this project I looked at how many Kickstarter campaigns were able to reach their goal in a short amount of time? Does the length of a campaign contribute to its ultimate success or failure.

### Challenge
The percentage of success of a kickstarter is the higher when the goal amount is lower. 
When the goal is high the likelyhood of a kickstarter project failing and getting cancelled are high.
The best times to launch a kickstarter project is between the months of April to June.
![Goals](https://github.com/Kalkidanalemaye/Kickstarter-analysis/blob/master/Goals.png)
![launchdate](https://github.com/Kalkidanalemaye/Kickstarter-analysis/blob/master/launchdate.png)
