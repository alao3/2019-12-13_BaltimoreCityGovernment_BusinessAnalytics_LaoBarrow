# Illegal Dumping in Baltimore City

# Problem Statement
Illegal trash dumping is a growing problem in Baltimore City--the Department of Housing and Community Development issued almost 1,150 citations for illegal dumping in 2018, however, there isn’t much insight into why this is happening and what we can do about it. We’d like to better understand the trends that help explain illegal dumping in Baltimore City, and explore potential interventions that can help prevent illegal dumping.

This has not changed since the original presentation. 

## Process

In our midterm project, we analyzed whether or not Baltimore had a trash problem. Through our findings, we wanted to identify geographic hot spots that had the highest trash accumulation. 

Now, this project allows us to dive deeper into a specific environmental trash problem: illegal dumping. Our approach is two fold: first, we wanted to find trends in 311 Reporting and the number of Environment Citations, as well as possible relationships between the two datasets. 

Second, identifying geographic hotspots of high illegal citations and reporting will give insight into specific areas to target on a city council district level and neighborhood level. By identifying 'hot spots', we hope to advise the city to focus on specific areas first to mitigate the ramifications of illegal dumping.

## Findings
PART 1: We analyzed the 311 and environmental citations annually and geographically. 
### 311 Findings
Annually we see an increase in the annual number citations from 2014 (2889 citations) to 2019 (10,269 citations).

Geographically, District 9 had the highest number of illegal dumping citations (5877) across all years. In addition, we compiled an analysis on a neighborhood level with the greatest number of reporting.

At this point, we diverted to answer an additional question - Does baltimore have more efficient reporting methods that led to increased reporting? Or is Baltimore becoming dirtier? Therefore, we analyzed the methods for how to report 311 citations, and found that API and Phone were the highest. 

Reporting methods include email, mail, phone, system, and web. Across all years, API and Phone had the highest number of reportings, with Phone being consistently higher than API. We wanted to see if the type of reporting had any effect on an increase or decrease in reports. By identifying the District API:Phone ratio compared to the number of reports, we created a scatter plot - the findings were that although there is higher phone use, it doesn't necessarily lead to more or less reports, lower API:PHONE ratios resulted in both high and low reports in multiple districts. Therefore, the method of reporting doesn't affect reporting quantities, but overall there is still an increase in reporting over the years.

To see if Baltimore is becoming dirtier beyond illegal dumping, we looked at 311 reporting citations that were related such as bulk scheduled, clean up, cleaning, dirty alley, dirty street. By removing the irrelevant subsections, we wanted to compare All Dumping to All Bulk Pickup, All Cleaning, and All Dirty Alley and Streets citations. Overall, reporting has not changed much over the years for Bulk Pickup and Cleaning; there is a huge increase in reporting for illegal dumping (as we know), and reports for Dirty Alley and Streets went down substantially. Baltimore isn't necessarily becoming dirtier, however we know that illegal dumping is reported much more frequently than other similar categories.

### Environmental Citations Findings 

Initially we intended to only analyze the environmental citations specifically for illegal dumping but we realised that the data collected for this violation was actually corrupted. As a compromise, we instead focused on citations given for violations similar to illegal dumping, trash accumulation and bulk trash in particular. 

From 2014 to now, there has been an exponential increase in the number of both citations.

We then looked at the citations by council district. In every council district there were more citations given for trash accumulation than bulk trash. District 13 had the highest number of both trash accumulation and bulk trash citations, whereas District 11 had the lowest number of both citations.

Then we did the same with the different neighborhoods and compiled a list of which neighborhoods have the greatest total citations in the two categories.

PART 2: After analyzing these two datasets, we wanted to better understand the relationship between the two. 
We analyzed both citation + 311 data on an annual level, and found that there were much higher reporting over the years compared to citations. Both were exponentially increasing over the years as well.

Second, we looked at a neighborhood level and matched the datasets to find the top neighborhoods that had both high citations and high reporting. Out of a top 30 out of around 250 neighborhoods, we found 16 neighborhoods that had both high reporting and citation numbers, and we mapped them out using the 311 dashboard given to us by City gov. After mapping them through their mapox dashboard on power BI, we found that these neighborhoods formed several clusters primarily in the NE region and SW region of Baltimore.

## Future Analysis

Overall, reporting is going up, citations are going up, meaning that the problems are being dealt with. We want to continue encouraging the same rates of reporting so the government knows where to take action. Phone is the most popular method of reporting, so finding ways to promote the phone number on billboards/campaigns will remind people to continue reporting.

Building off of the neighborhood mapping, we want to propose a targeted intervention strategy in these specific clusters/'hot spots' using a surveillance camera system. We plan to look into neighborhoods where reports are not being closed on time and thus the government needs more interventions in these regions. Next week, we will build on a possible implementation strategy including pricing/budget, which clusters to target first, and a possible timeline.

We need to build visuals, write out or excel steps, create the presentation, write out the analysis, and outside research to understand pricing for cameras or see what other cities have done in the past to combat illegal dumping. 


## Problems we faced/forsee
- After the first meeting with city government, we realized the data we downloaded was inaccurate, leading us to obtain very skewed and inaccurate results.
- As mentioned before, after redownloading the data, we got better results for the 311 citations, however we are still having trouble identifying accurate data for environmental citations. As a result, we will use data related to 'illegal dumping' (we used 'bulk trash' and 'trash accumulation')to understand the general trash/dumping problem. We know this is an expensive intervention so we aren't sure how feasible this would be (however it is cheaper than assigning personnel to oversee illegal dumping).
- We are not sure if city government will see the immediate value in building awareness around reporting/using phones to report, but we believe this is a great step because the government will benefit from people reporting, as they act as the eyes and ears of the city. It would be better to have them report rather than not, which could lead to increased trash problems, rat problems, etc. 


# Additional Sources Baltimore Open Data
We used the Environmental Citations and 311 Reporting Data from the open data website. 
