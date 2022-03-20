# Kickstarter-Analysis
## Module 1: Curtains for Louise


### Overview:
The purpose of this analysis is to determine whether or not Louise should start a fundraiser for her play "Fever."


### Analysis and Challenges:


A sample of over 4,000 fundraiser projects was used to determine how Louise should plan her fundraiser. The original sample, was filtered down to 1,067 projects specifically raising funds for plays. This provides the most-appropriate data for Louise, as Technology or Food projects may have little to no similarities to Theater projects. This analysis focuses on the data from two angles: outcomes based on each project's launch date and outcomes based on the financial goal of each project. These criteria were chosen to gauge seasonal sensitivity as well as goal sensitivity- two factors over which Louise has direct control in the planning process.

The most challenging aspect of the analysis was establishing appropriate range benchmarks for the Outcomes Based on Goals chart. Nesting the correct COUNTIFS arguments required some trial and error, and the benchmarks themselves could be deemed inadequate for the analysis. 

### Results:
The data shows that Louise's best chances are to start her fundraiser in May or June. **May had the highest success rate as well as the greatest number of successful fundraisers.** October and December in particular should be avoided- October had the highest number of failures and ranked sixth in successes, and December saw almost as many failed projects as successful ones.

<img width="245" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/101079957/159175860-1b88a50d-8b4c-4f2f-a1bd-b47ac1c5a5ac.png">

With respect to setting her fundraising goal, Louise should keep it under $10,000. The trendline shows that as a fundraiser's goal increases, there are fewer proportional successes. Notably, the success rate increases for projects between $35,000 and $45,000, but that is due to there being a significantly smaller sample- only nine projects fell into this category. The 534 projects with goals between $1,000 and $5,000 provide a sample much less sensitive to outliers.

<img width="240" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/101079957/159175859-910a9306-e543-44c2-81d0-be903b2b709b.png">

One limitation to a clear result is the range of our data. 1,067 projects may seem like quite a large sample, but as they are spread across 12 months in the year and range from $50 to $200,000 goals, there is substantial variation in both data sets examined. Additionally, while the start date is captured, the *duration* of the fundraiser is not. It is quite possible that a fundraiser was given too little time to collect the necessary funds. Further, the scope itself is limited, as no data was collected pertaining to the subject matter of each play proposed or how vigorously the plays' fundraisers were being marketed or "shared" on social media. Additionally, as theater is within the realm of "the arts," there is an inherent subjectivity which may be greatly swayed by trends.

Ultimately, Louise should proceed with caution if she intends to go through with fundraising her new play. This data scientists recommends another analysis addressing the above limitations before executing her plan.
