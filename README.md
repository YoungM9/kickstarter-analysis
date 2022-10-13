# Kickstarter-Analysis
**Overview of Project: Explain the purpose of this analysis.**
The purpose of the analysis was to determine the most important dimensions of the most successful campaigns that were categorized as plays, and emulate it based on the data analyzed from the Kickstarter file.
**Analysis and Challenges: Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.**
To perform my analysis I used different sheets to separate the data after filtering for outcomes. I then went to the outcomes analysis sheet where I used the code
~~~
COUNTIFS(Successful!"$A:$A","<1000")
COUNTIFS(Failed!"$A:$A","<1000",Failed!"$A:$A",<=4999)
=SUM(B2:B13)
~~~
As for challenges, it mainly had to do with the tedious amount of syntax required to complete my analysis. This resulted in frivolous mistakes such as forgetting a zero in 10000 or accidentally referencing the wrong worksheet. I overcame this by going through each column and row and looking to see if the data was making sense

**Results: Answer the following questions in complete and coherent sentences.**
**What are two conclusions you can draw about the Theater Outcomes by Launch Date?**
One conclusion is that the months of May, June and July are most optimal if we would want to fundraise money for a theatre play. However, the months of Janurary and Feburary prove to be the least optimal months for plays.

**What can you conclude about the Outcomes based on Goals?**
Generally, the less money that is invested into a play, the more successful it will be. This means that when thinking about launching a play, its important to consider a smaller budget so that resources can be alloted correctly

**What are some limitations of this dataset?**
The variables being analyzed are very general. There are many aspects to a play that could be evaluated to understand why, counterinuitively, there seems to be less success with plays that invest more money compared to those that don't. It would benefit to understand how that money is being distributed, to whom, etc...

**What are some other possible tables and/or graphs that we could create?**
We could make a bar chart comparing the success and failures of the different kinds of plays by their name
