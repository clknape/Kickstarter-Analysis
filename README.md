# Kickstarting with Excel

## Overview of Project
    The Purpose of the project is to analyze the success of different theater fundraising campaigns with relation to their launch date and fundraising goal. Data was collected from theater projects between 2009 and 2017 and their outcomes were illustrated with two graphs; one showing the correlation between month of launch and success rate of campaigns and the second showing the correlation between funding goal and success rate.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A correlation  was analyzed between the months that fundraising projects were launched and their success rate. July is the most successful month and November is the least successful month.

### Analysis of Outcomes Based on Goals

     A line graph was created to show a correlation between the the fundraising goals and the percentage of success.  With the exception of the "3500 to 3999" range and the "4000 to 45000" range, the success rate decreases as the funding goal increases.

### Challenges and Difficulties Encountered

     The biggest challenge of the project was filtering the data to count only successful theater projects within predetermined ranges. This was accomplished using the countifs formula (=COUNTIFS(Kickstarter!$D:$D,">=15000", Kickstarter!$R:$R, "plays", Kickstarter!$D:$D,"<=19999", Kickstarter!$F:$F, "successful").

## Results

    The most successful launch date for fundraising campaigns is in the summer months, with July the highest at 111 successful campaigns.  In addition, the winter/holiday months proved to be the least effective months for launching fundraising campaigns.  Those months had the lowest success rates with December showing only 37 successful campaigns which only two more than the number of failed campaigns. Campaigns with a goal over $45,000.00 were the least successful with 100% failed campaigns in the $45,000 to $49,999 range. The lower the funding goal , the most successful as shown by the "Less Than 1000" fundraising goal with a 76% success rate.  Although the data set shares 
information about launch dates, it does not show the length of the funding campaigns. A line graph that compared length of fundraising campaigns on thex-axis and percent success on the y-axis would provide additional information that would help when launching a campaign.  In addition, it doesn't share any information about the campaign marketing. It would be beneficial to see which communciation strategies (social media, email, flyers) and events brought in the most money.  A bar graph with the strategy (social media, email, flyers, donor events, etc.) on the x-axis and outcomes of each on the y-axis would provide a picture of which strategy is most successful.
