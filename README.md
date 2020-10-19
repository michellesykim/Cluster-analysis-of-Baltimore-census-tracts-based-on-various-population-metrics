# Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics
This repository conducts a cluster analysis of Baltimore census tracts based on various population metrics

# Background
According to the analysis of $670 million of budgeted capital projects in Baltimore (2017) [ Baltimore budgeted capital projects analysis](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-ci-capital-budget-race-inequality-20171211-story.html), over the past years, an average of $15 million of the budget was used for Baltimore neighborhoods where more than 75% of residents are white where as only $8 million was used in neighborhoods where more than 75% of people are minorities. Also, only $3.5 million of funding was used in neighborhoods where more than 40% of residents were below the poverty whereas $14 million of funding was used in neighborhoods where fewer than 20% of residents lived in poverty. These numbers seemed not equitable to me and i realized that the fund is not being invested to help adjust the historical injustices or for the people who need the most. Thus, I wanted to group the census tracts in Baltimore into four clusters to get a clear idea of what distinctive population metrics that each cluster have and based on that i wanted to suggest how the capital/public/private fund can be most efficiently invested in these negihborhoods. For example, if one of the clusters indicate it has a significantly higher teenage birth rate, the funds would be invested more in health realted projects compared to other neighborhoods in Baltimore. 

# Business question
How are census tracts in Baltimore grouped based on different population metrics?

# Data question
How are census tracts in Baltimore grouped based on the incarceration rate, teenage birth rate, poverty, race, and median rent?

# Original data
[Incarceration rate in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_jail_rP_gP_pall%20(15).csv

[Teenage birth rate in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_teenbirth_rP_gF_pall%20(3).csv

[Poverty rate in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_poor_share2016%20(3).csv

[Fraction non-white in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_nonwhite_share2010%20(5).csv

[Median rent in Baltimore] https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/shown_tract_median_rent2016%20(3).csv

# Analysis Data
[Cluster analysis of census tracts in Baltimore] put link here| 

Attached file contains the cluster analysis and the origianl data sets.

# Key findings
![alt text](https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/Screen%20Shot%202020-10-19%20at%204.40.02%20PM.png)
Census tracts in Baltimore that fall into anchor1 (group1) have slightly low iincarceration rate, slightly high teenage birth rate, average poverty rate, slightly high percentage of non-white, and slightly high median rent

Census tracts in Baltimore that fall into anchor2 (group2) have low incarceration rate, low teenage birth rate, low poverty rate, low percentage of non-white, and high median rent 

Census tracts in Baltimore that fall into anchor3 (group3) have high incarceration rate, high teenage birth rate, high poverty rate, high percentage of non-white, and low median rent

Census tracts in Baltimore that fall into anchor4 (group4) have slightly low incarceration rate, slightly low teenage birth rate, slightly low poverty rate, low percentage of non-white, and average median rent

![alt text](https://github.com/michellesykim/Cluster-analysis-of-Baltimore-census-tracts-based-on-various-population-metrics/blob/main/min3.png)

Based on the cluster analysis, among the five factors, it is obvious that incarceration rate, in most of the cases, teenage birth rate, poverty rates, and percentage of non-white are positively correlated and they are negatively correlated with the median rent (For example, when poverty rate and non-white percentage increase, median rent tend to decrease). Among the anchors, Anchor 2 and 3 have the most extreme features. Most of the people residing in Anchor 2 tracts are wealthy white people who can afford the high rent in those areas, and the areas tend to have less incarceration rate and teenage birth rate. The least amount of tracts in Baltimore fall into anchor2 (21%). On the other hand, in Anchor3, most of the people are non-white with high poverty rate who can only afford the low median rate in those areas. These areas tend to have high incarceration rate and high teenage birth rate as well. Most tracts in Baltimore fall into anchor3 (30%) which is the highest percentage among the four anchors.  

Based on the comparison of anchor 4 and 2, even though both have a very similar percentage of non-white, Anchor 4 has higher rates for incarceration rate, teenage birth rate, and poverty rate compared to anchor 4. Also, median rent is lower compared to anchor 2. But overall they both have lower-than-average trends in all the population metrics and there is a high possibility that this is due to the low non-white percentage (since they both had low and similar percentage of non-white). Lastly anchor 4 is pretty much average on all the factors except that it is slightly over average for non-white percentage, however interesting fact is that eventhough it has higher poverty rate than anchor4, it has a higher median rent than anchor4, thus it would be more of a struggle for people residing in tracts in anchor 1 to pay their relatively high rent while they have higher poverty than anchor4. Tracts that fall into anchor 1 and 4 accounts for 26% and 23% respectively.

# Summary

Based on the cluster analysis, i was able to group census tracts in baltimore into four anchors. And they all had distinctive features. The main takeaways are that for anchor 3, where there is a high poverty rate, there tend to be more non-white population, teenage birth rate, and incarceration rate. And for anchor 2 and anchor 4, where there is a low non-white percentage, there tend to be much less incarceration rate, teenage birthrate, and poverty rate compared to anchor 1 and 3. This definitely shows that there are still on-going impact of the racial segregation as the 2017 study mentiond. Based on the cluster analysis, city government or city planning department can determine how to distribute the community-focused fund/capital budget to adjust the historical injustices and imbalances and to really provide help to the people who need the most. For example, tracts in baltimore that fall into anchor 3 would need the most funds compared to other anchors given that it has significantly higher rate in incarceration rate, teenage birth rate, and poverty rate, and non-white percentage and given that high percentage of census tracts in baltimore fall into anchor3. . Funds can be focused on like creating non-profit organizations for crime prevention, teen pregnancy prevention funds including education on unsafe sexual sexual practices of teens and job skills, and more financial support for those how suffer from poverty. And for anchor1, less fund can be allocated but more focused on the initiatives related to teenage birth prevention would be necessary (Health focused funds) given its relatively higher teenage birth rate. And given that it has a higher poverty rate compared to anchor4, it has a higher median rent, thus, part of the funds can be used for Baltimore rental assistance programs. Lastly for anchor4, least amount of funds can be allocated given it’s relatively lower rates for all incarceration, teenage birth rate, and poverty rate, however it could focus on the crime prevention initaiton especially crime prevention educaiton for young children. And analyzing how the rent capital budgets of baltimore are focusin on like health or infrastructure would be nice to know. And also knowing what actually derived the difference between anchor 2 and 4 given the same non-white percentage. Additional data could be dataset from 2018 to 2020 to see how this trend changed. This is important for me that baltirmoe, where i am living right now, still suffering from the reamining effect of the racial segreation. And the cluster analysis shows that communities with significantly lower non-white population have singifincilaty lower rates for all incaraefariton, poverty, and teenage birth rate. It is also important for me to think about how the funds would have to be distributed in a more equitable way. 

