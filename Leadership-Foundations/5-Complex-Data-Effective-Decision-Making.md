# Complex Data and Effective Decision Making

### Introduction

As a leadership competency, decision making is the ability to use qualitative and quantitative data, analyze and intepret it, and act upon it to achieve a desired goal.
We will look at how analytics can be used or abused in decision making, as well as more generally, how data in the form of 360 feedback from others, can also inform our decisions.

Goals:
- Undestand the importance of data and different opportunities data presennts
- Recognize a few common errors in evaluating quantitative data. 
- Reflect on the data you have available to make decisions about your own growth as a leader.

### Data and Analytics in Business

The amount of data is growing faster and faster. Good analysis of this data can lead to huge profits. It has been shown that companies using analytics to their advantage have better financial performance, they're more likely to make timely decisions, and they're more likely to executive on their plans. Managers need to learn how to deal with data or manage people. However, to make useful decisions with data, you need to learn extract useful information, be critical about the data and models used and correctly account for any uncertainty and flaws in your data. Best form of data analysis and data-driven decision making are only useful if they're guided by strong leadership. Develop high level understand of your data, signficantly improve your leadership impact to the data analysts on your team. Data comes in many shapes and sizes (structured like excel spreadsheet or unstructured like performance review, images and video files)
One of the challenges in dealing with data is figuring out how to store and process it. While this require important decision and strategy, it won't be our focus here. 
We're interested in using data to make better decisions. Use data to make value. There are three main ways that data is used to make better decisions. 

1. Descriptive Analysis (focused on visualizations and summary statistics; goal to clearly describe patterns in the data) 
2. Predictive Analysis (forecast or predict different outcomes, goal being better understand or anticipate an outcome) 
3. Prescriptive Analysis (tries to determine the optimal actions to take, goal is to provide specific actions on what to do)

Many different tools to make better decisions.

HBR 5 Essential principles for understanding Analytics.

1. Identifying and Framing the Analytical Problem
2. Working with Quantitative People
3. Understanding Different Types of Data and Their Implications
4. Understanding Different Types of Analytics and Their Implications
5. Exploring Internal and External Uses of Analytics

Details
1. Identifying and Framing the Analytical Problem
  - Proper quantitative analysis starts with recognizing a problem or decision and beginning to solve it. In decision analysis, this step is called framing, and it's one off the most critical parts of a good decision process.
  - Several sources that lead to this first step, including pure curiosity (manager's common sense or observation of events), experience on the job, or the need for a decision or action
  - Analytics haven't yet come to play at this step. Decision to forge ahead with some analysis may be driven by a hunch or intuition. Standard evidence is low
  - Quantitative analysis is to eventually test your hunch against data (analytical thinkers vs others: test their hunches with evidence and analysis)
  - Explore alternative framings with analysts
2. Working with quantitative people
  - Managers to establish close relationship with them
  - Understanding of the business problem
  - Your quant has the understanding of how to gather data on and analyze
  - Help analyst fully undnerstand problem
  - Analyst communicate with you in normal business language, engage with your issue, and work at it unntil you're satisfied.
  - Find middle ground 
3. Understanding different types of data and their implications
  - Big data is valuable for business. Managers don't understand the difference between big and small data, and uses big data indiscriminately
  - Small data - is data of manageable size (fit in a single server, that is structured (rows and columns)) and changes relatively infrequently.
  - Small data comes from financial systems, CRM, order management
  - Analyzed for many year 
  - Essential for knowing your customers, understanding company's financial performance, tuning supply chain
  - Big Data is unruly. Too big to fit on a single server, relatively unstructured, fast moving
  - Likely outside of businnenss transactions (call reps, social media, moving around store)
  - Big data offers great opportunity, challenge is to get it into a structured form. needs a data scientist
4. Understanding Different Types of Analytics and Their Implications
  - For many years, the vast majority of analytics were descriptive - simple reports or dashboards with numbers about what happened
  - Predictive Analytics uses statistical models on data about the past to predict the future
  - Prescriptive Analytics create recommendations for how workers can make decisions in their jobs
  - Some managers need some urging to adopt the less familiar predictive and prescriptive analytics, more valuable than descriptive variety
  - Automated Analytics - Analyticall decisions are made not by humans but by computers
  - Analytical Decisions - issuing credit by banks, insurance policies, automatically
5. Exploring Internal and External Use of Analytics
  - Finally, managers need to be aware of the distinction between internal and external usues of analytics
  - Analytics were used almost exclusively to support internal decisions


### An Initial Analysis Debrief
Data Case Study to be given at interview:
- Data can be collected about many attributes of a business
- One area that's relevant - related to every business, employee satisfaction and retention
- Data 451 people who were employed as managers in the last few years
- Variables: (10 is most satisfied, 1 least satisfied)
  - Satisfaction (1 - 10)
  - Last evaluation (1-10)
  - Average Monthly Hours (x hours)
  - Time at company (n years)
  - Salary level (high, medium, or low)
  - Promotion (1 to 0) in last five years
  - Left the company (1 to 0)
- Descriptive Analytics
  - Current level of satisfication vs evaluation score (direct correlation) -> Scatterplot (level of satisfaction vs )
  - Mean satisfication score (higher salary -> more satisfied)
  - Manager promotion (more promotion -> retention) 

1. What conclusion can you draw? What decisions might you make? What does this tell you about managers at the company?
2. A decision is made to increase all manager salaries by 10% to incraese employee satisfcation. Using this data and analysis, do you think this a good or bad decision?
3. A decision is made to give promotions to the top performing managers so that they don't leave the company. Using data and anaylsis do you think this is a good or bad decision?
4. What additional information would you like to collect to better enable decision making with this data?

Look at sampling (bias in those who responded)

Data Analysis: several flaws with our anaylsis. 
1. Sampling bias (selection bias) does this data set include all of the managers at the company? If not, how were these managers selected? If we did not collect data for a random or representative group of managers, we should not be drawing conclusions about the managers as a whole.
2. Employees with higher satisfaction and higher evaluation score. Lower = Lower. Which piece of information came first? Employees not satisfied because they're receiving poor evaluations? Or low satisifcation with their jobs? Impossible to establish casuality with this data, unless we know timing of the events. We should be more careful of the data and experiment, if we want to claim any sort of causal relationship between two variables.
3. Promotion - promotion less likely to leave company. Major flaw in analysis. If the employee leaves the company, definitely can't get a promotion. Survivor Bias (including people stay different times, naturally change the rate at which they get promotions). Data differently, select different sample of managers. Stayed for at least two years and whether or not receive a promotion within two years. All employees have the same amount of time to receive a promotion.
4. Higher salaries = More satisfied than lower salaries (what is causing the different salaries? Perhaps these employees work in different departments/location). Might not be the salaries that's causing dissatisfaction at all. Careful about moitted variables (not in dataset)

Common Errors
1. Sampling Bias
2. Survivor Bias
3. Omitted variables

Data analysis can be very useful but can also easily lead to erroneous conclusions.
