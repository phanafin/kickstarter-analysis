# Kickstarting with Excel

## Overview of Project
This project is an analysis of CrowdSource Funding Data at the request of Louise.  This report utilizes the raw KickStarter Data and analyzes the data to reveal relevent information for the client to act upon. 
    
### Purpose
Louise is the aspiring producer of a play entitled Fever.  Louise has tasked us with the analysis of the CrowdSoursing Data in an effort to strategize the best plan for acquiring additional funding to produce the play.
    
## Analysis and Challenges
There was a vast amount of data to filter through.  Much of the data had nothing to do with Louise's core concerns.  The data was filtered to include only plays, and individual items, for example launch date, success, failure, cancellation, goal dollar amounts, were all taken into consideration during the analysis.
    
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85403978/121817565-64bc4c80-cc3f-11eb-8f5f-35f61348e726.png)
As is shown in the graph, there is a slight risk of cancellation of projects all throughout the year, but in further analysys, you'll find that No plays were cancelled.  There is a risk of Failure of Theater project throughout the year as well, however, that risk is at it's lowest in early spring.  This also happens to be the time of year when the vast majority of successful projects are launched, reaching their zenith in May.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85403978/121818061-35f3a580-cc42-11eb-9d41-1d5fb352e387.png)
According to the data, there are a variety of amounts for funding that have a high potential of success.  Louise's initial request was for $10,000.  According to the data, this dollar amount happens to be beyond a point where funding projects for play start to decline ($5k) in success rate (With an inverse reaction for Failed Projects at the same dollar amount).  However, there appears to be a recovery and projects that are requesting between $35k and $45k have almost as much success as those initial dollar amounts ($0-$5k).

### Challenges and Difficulties Encountered
Identifying and understanding the significance of outliers has been challenging in this analysis.  The larger dollar goal amounts in plays that seemingly have just a slightly lower success rate than the opening dollar amounts may be a misnomer due to the fact that there is only a grand total of 9 projects that fall in that dollar amount compared to the 720 records that fall into the $0-$5,000 range.
    
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the Launch Date, it is obvious that funding projects that are related to theater plays are significantly more apt to be successful when their CrowdSource Funding projects are launched in May.  Also, The slight uptick in October is a misnomer as the increase of successful projects coincides with an increase in failed projects, which may both be related to the absence of cancelled projects.

- What can you conclude about the Outcomes based on Goals?
Obviously, the lower dollar amount projects see more success than the projects requesting higher dollar amounts.  If Louise wants a better chance of being successful, she'll ask for quantities between $0 and $5,000.  There is still a chance of being successful at the $10,000 amount that she initially requested, but that seems to be the tipping point where projects of larger dollar amounts see a significant drop in success rate.  The $0 to $10,000 success rate stands at 70%, and if launched in May, Louise stands a great chance of success.

- What are some limitations of this dataset?
The initial data suggested that there is a possibilty that some of the CrowdFunding projects (Successful, Failed or Cancelled) that were related to theater might be asking for a dollar amount the produce not only a play but a building as well.  The dataset did not show if those projects that were failed or cancelled gathered enough money to at least cover the cost of the play which could then be performed at a different location...perhaps Louise's

- What are some other possible tables and/or graphs that we could create?
Perhaps a graph that shows the success/failure rate of all theater vs theater/plays.  This analysis might show an opportunity to collaborate with a project from another category.


