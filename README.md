# Capstone
Capstone Project for Springboard
## Kickstarter Projects
### by Bridget Mabry


#### **The Problem**  
*What is the problem I want to solve?*

Kickstarter is just one of the ways that many individuals and organizations, raise money to fund their projects. But is it the best way? There are more ways to fundraise now, than ever before. Different types of projects tend to have a higher success rate on different platforms. For this project in particular, I plan to evaluate the "Film & Video" category, to see if this is where films should look to raise funds, or if they are better off going elsewhere.

**The Client**  
*Who is your client and why do they care about this problem? In other words, what will your client do or decide based on your analysis that they wouldn’t have otherwise?*

The client for this would be independent filmmakers. Studios have the money to fund a project, without having to crowdsource (that's what the producers are for), but the indie film scene doesn't typically have that luxury. Raising funds can be quite challenging, so finding the best platform is crucial. It can literally mean the success or failure of your project. Not only do I want to find out what the success rate is, but I would also like to take a look at the percentages of the funds raised. Were they close enough to their goal, to where the project might still be made, or were they so far off, there's no chance? With this information, indie filmmakers will be able to make an educated decision on whether or not to use Kickstarter for their campaigns.

**The Data**  
*What data are you going to use for this? How will you acquire this data?*

The Kickstarter data I am using is from Kaggle and can be found [here](https://www.kaggle.com/kemical/kickstarter-projects#ks-projects-201801.csv)

Variable | Description
---------|-------------
Name | Name of the project
Category | Sub-category of the project
Main_Category | Main category of the project
Currency | Currency the project funds were raised in
Deadline | When the funds needed to be raised by
Goal | How much money the project needed
Launched | When the project was launched
Pledged | How much money was raised
State | The outcome of the fundraiser
Backers | How many people donated
Country | Location of where funding will be sent
USD pledged | US dollars raised

install.packages()  
library()

kickstarter <- read_csv()

**The Approach**  
*In brief, outline your approach to solving this problem (knowing that this might change later)*

1. Data wrangling and cleaning: will be filtering out all other categories (only keeping "Film & Video")
2. Analyze the data: overall success rate, average percentage of goal earned, average number of donors, do certain genres do better than others? Is there a correlation between length of time the project has been up and how much money is raised?
3. Report my findings

**Deliverables**  
*What are your deliverables?*

My deliverables will include a report of my findings and the R code that was used.
