# Cluster-analysis-of-census-tracts-in-Baltimore-based-on-various-population-metrics
This repository talks about the cluster analysis of Baltimore census tracts based on various population metrics

# Background
According to the analysis of $670 million of budgeted capital projects in Baltimore (2017) [ Baltimore budgeted capital projects analysis](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-ci-capital-budget-race-inequality-20171211-story.html), over the past years, an average of $15 million of the budget was used for Baltimore neighborhoods where more than 75% of residents are white whereas only $8 million was used in neighborhoods where more than 75% of people are minorities. Also, only $3.5 millions of funding was used in neighborhoods where more than 40% of residents were below the poverty whereas $14 millions of funding was used in neighborhoods where fewer than 20% of residents lived in poverty. These investments seemed not equitable and seemed like the fund is not invested in the people who need the most. Thus, I wanted to group the census tracts in Baltimore into clusters based on various population metrics to see if census tracts can be grouped together and get a clear idea of what distinctive population metrics that each group has. And, based on the analysis, I want to suggest how the community focused funds/other government funds can be effectively invested in these neighborhoods based on their specific needs.

# Business question
How are census tracts in Baltimore grouped based on different population metrics? And can we suggest different types of funds based on the group's specific need?

# Data question
How are census tracts in Baltimore grouped based on the incarceration rate, teenage birth rate, poverty, race, and median rent? 

# Original data
[Incarceration rate in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_jail_rP_gP_pall%20(15).csv

[Teenage birth rate in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_teenbirth_rP_gF_pall%20(3).csv

[Poverty rate in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_poor_share2016%20(3).csv

[Fraction non-white in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_nonwhite_share2010%20(5).csv

[Median rent in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_median_rent2016%20(3).csv

# Analysis Data
[Cluster analysis of census tracts in Baltimore]https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/miniproject3final.xlsx
Attached file contains the cluster analysis and the origianl data sets.

# Key Findings
![alt text](https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/Screen%20Shot%202020-10-19%20at%204.40.02%20PM.png)


![alt text](https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/min3.png)

Among the anchors, anchor 2 and 3 have the most extreme features. Most of the people residing in anchor 2 census tracts are wealthy white people who can afford the high rent in those areas, and the areas tend to have less incarceration rate and teenage birth rate. Based on the pie chart, the least number of tracts in Baltimore fall into anchor 2 (21%). On the other hand, for anchor 3 tracts, most of the people are non-white with high poverty rate who can only pay the low median rate in those areas. These areas tend to have high incarceration rate and high teenage birth rate as well. Highest numbers of tracts in Baltimore fall into anchor 3 (30%). Based on the comparison of anchor 4 and 2, even though both have a similar percentage of non-white, anchor 4 has a higher rate of incarceration rate, teenage birth rate, and poverty rate compared to anchor 2. Also, median rent is lower compared to anchor 2. But overall, they both have lower-than-average trends in all the population metrics and there is a high possibility that this is due to the low percentage of non-white (since they both had low and similar percentage of non-white). Lastly, anchor 1 is average on all the factors except that it has slightly over-average percentage of non-white. However, interesting fact is that even though anchor 1 has a higher poverty rate than anchor 4, it has a higher median rent than anchor 4, thus it would be more of a struggle for people residing in tracts under anchor 1 to pay their relatively higher rent. Tracts that fall into anchor 1 and 4 accounts for 26% and 23% respectively.

# Summary

With cluster analysis, I was able to group census tracts in Baltimore into four anchors based on various population metrics. Since we now know the population metrics of tracts under each anchor, city government or city planning department can determine how to distribute the community-focused fund/capital budget among neighborhoods in Baltimore to adjust the historical injustices and imbalances and to provide financial support to the people who need the most. For example, tracts in Baltimore that fall into anchor 3 would need more funds than the other anchors given that it has significantly higher rate in incarceration rate, teenage birth rate, and poverty rate, and non-white percentage and given that highest percentage of census tracts in Baltimore fall into anchor 3. For action items, funds for anchor 3 can be focused on creating non-profit organizations for crime prevention or teen pregnancy prevention education, including education on unsafe sexual practices of teens. Also, funds focused on education on job skills and personal finance for those how suffer from poverty would be helpful for Baltimore citizens in anchor 3. For anchor 1, less fund can be allocated than anchor 3, but funds focused on the initiatives related to teenage birth prevention would be necessary (Health focused funds) given its relatively higher teenage birth rate. 

For additional information, data on where and how the recent capital budgets of Baltimore were used would be informative. Are those funds used in health-related projects? Infrastructure-related projects? Also, same datasets that I used in my analysis but from 2018 to 2020 (recent) would be useful to see how these trends might have changed. This is important for me since Baltimore, where I am living right now, still suffers from the remaining effect of the racial segregation (looking at anchor 3) and the funds are not allocated equitably. I hope this analysis could provide a guideline for the future funds to be distributed in a more equitable way based on each anchor of neighborhoods' specific needs.

