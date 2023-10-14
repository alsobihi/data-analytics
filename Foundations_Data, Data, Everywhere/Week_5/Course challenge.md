
\*Course challenge\*
====================

Graded Quiz. • 50 min

*   English

DueNov 5, 11:59 PM +03

Assessment passed

Congratulations! You passed!
----------------------------

Grade received 90%




### 1.Question 1

**Scenario 1, question 1-5**

You’ve just started a new job as a data analyst. You’re working for a midsized pharmacy chain with 38 stores in the American Southwest. Your supervisor shares a new data analysis project with you.

She explains that the pharmacy is considering discontinuing a bubble bath product called Splashtastic. Your supervisor wants you to analyze sales data and determine what percentage of each store’s total daily sales come from that product. Then, you’ll present your findings to leadership.

You know that it's important to follow each step of the data analysis process: ask, prepare, process, analyze, share, and act. So, you begin by defining the problem and making sure you fully understand stakeholder expectations.

One of the questions you ask is where to find the dataset you’ll be working with. Your supervisor explains that the company database has all the information you need.

Next, you continue to the prepare step. You access the database and write a query to retrieve data about Splashtastic. You notice that there are only 38 rows of data, representing the company’s 38 stores. In addition, your dataset contains five columns: Store Number, Average Daily Customers, Average Daily Splashtastic Sales (Units), Average Daily Splashtastic Sales (Dollars), and Average Total Daily Sales (All Products).

**Considering the size of your dataset, you decide a spreadsheet will be the best tool for your project. You proceed by downloading the data from the database. Describe why this is the best choice.**

1 / 1 point

* Databases can’t be used for analysis.
* Spreadsheets are most effective when working with queries.
* [ **Spreadsheets work well for processing and analyzing a small dataset, like the one you’re using.** ]
* Only spreadsheets let you download and upload data.

> Correct

### 2.Question 2

**Scenario 1 continued**

You’ve downloaded the data from your company database and imported it into a spreadsheet. **IMPORTANT**: To answer questions using this dataset for the scenario, click the link below and select the “Use Template” button _before answering the questions._

Link to template: [Course Challenge - Scenario 1Opens in a new tab](https://docs.google.com/spreadsheets/d/1pIiGuiZ8SZ2xNfXHEIIb5gpX1NNOuKAUbaqtmPh1GUY/template/preview?resourcekey=0-p4GIOWHIaC6wZTvc9HZzyA#gid=0)

OR

If you don’t have a Google account, you can download the template directly from the attachment below.

[Download CSV File
Course Challenge Dataset - Scenario 1 - Scenario 1\_ Pharmacy Data - Part 1
CSV File](https://d3c33hcgiwev3.cloudfront.net/jgOcTMW9S-uDnEzFvfvrYQ_c46ee66727424d2298e2ff73090392f1_Course-Challenge-Dataset---Scenario-1---Scenario-1_-Pharmacy-Data---Part-1.csv?Expires=1697414400&Signature=Qm~iUfy60OrFP25IV0x9JvMvvzyyxa-nfkjMyKDsrXOvvb15LmR9~ng1Gdz16mwt-959crh1YDIjDwIj7pwpvveap2xX2WTV5srOxUx9ivzhWgGEa2B3k8rZPlxdhX5E~EfChZDUbonb-7dMRV19NIMU0C3FbcmPoGot3ENhBZA_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dVuIRwzdTUibiEcM3V1INg_93ac3942fb2e40e9b9fe4fd8b44e22f6_dotted-line-right.png?expiry=1697414400000&hmac=M9x0gKbyWpdIkreuYZRiDZveLcqfOnsFZfFGA1JUyvc)

Now, it’s time to process the data. As you know, this step involves finding and eliminating errors and inaccuracies that can get in the way of your results. **While cleaning the data, you notice that information about Splashtastic is missing for Store Number 15 in Row 16. Which of the following would be an appropriate course of action?**

0 / 1 point

* Investigate previous projects and see how this was dealt with there. [ **الإجابة الصحيحة** ] 
* Sort the spreadsheet so the row with missing data is at the bottom.
* Delete the row with the missing data point.
* [ **Replace the row with the average values of the other data points.** ] خطأ

> Incorrect
> الإيجابة خطأ
>
> Review [the section on the data analysis processOpens in a new tab](https://www.coursera.org/learn/foundations-data/home/week/3) for a refresher.

### 3.Question 3

**Scenario 1 continued**

Once you’ve found the missing information, you analyze your dataset.

**During analysis, you create a new column F. At the top of the column, you add: Average Percentage of Total Sales - Splashtastic. What is this column label called?**

1 / 1 point

* A title
* A reference
* [ **An attribute** ]
* A headline

> Correct

### 4.Question 4

**Scenario 1 continued**

Next, you determine the average total daily sales over the past 12 months at all stores. The entire range of cells that contain these sales are E2:E39. **The correct syntax is =AVERAGE(E2:E39).**

1 / 1 point

* [ **True** ]
* False

> Correct

### 5.Question 5

**Scenario 1 continued**

**You’ve reached the share phase of the data analysis process. It involves creating a data visualization to highlight the Splashtastic sales insights you've discovered.**

1 / 1 point

* [ **True** ]
* False

> Correct

### 6.Question 6

**Scenario 2, questions 6-10**

You’ve been working for the nonprofit National Dental Society (NDS) as a junior data analyst for about two months. The mission of the NDS is to help its members advance the oral health of their patients. NDS members include dentists, hygienists, and dental office support staff.

The NDS is passionate about patient health. Part of this involves automatically scheduling follow-up appointments after crown replacement, emergency dental surgery, and extraction procedures. NDS believes the follow-up is an important step to ensure patient recovery and minimize infection.

Unfortunately, many patients don’t show up for these appointments, so the NDS wants to create a campaign to help its members learn how to encourage their patients to take follow-up appointments seriously. If successful, this will help the NDS achieve its mission of advancing the oral health of all patients.

Your supervisor has just sent you an email saying that you’re doing very well on the team, and he wants to give you some additional responsibility. He describes the issue of many missed follow-up appointments. You are tasked with analyzing data about this problem and presenting your findings using data visualizations.

An NDS member with three dental offices in Colorado offers to share its data on missed appointments. So, your supervisor uses a database query to access the dataset from the dental group. The query instructs the database to retrieve all patient information from the member’s three dental offices, located in zip code 81137.

**The table is dental\_data\_table, and the column name is zip\_code. How do you complete the following query?**

SELECT \* FROM dental\_data\_table

1 / 1 point

* WHERE\_zip\_code = 81137
* [ **WHERE zip\_code = 81137** ]
* zip\_code = 81137
* WHERE = 81137

> Correct

### 7.Question 7

**Scenario 2 continued**

The dataset your supervisor retrieved and imported into a spreadsheet includes a list of patients, their demographic information, dental procedure types, and whether they attended their follow-up appointment. To use the dataset for this scenario, click the link below and select “Use Template.”

Link to template: [Course Challenge - Scenario 2Opens in a new tab](https://docs.google.com/spreadsheets/d/1tXJvXgUP58iYYSW6tBfiGMD5lJFOgHXvHx2EdDOCxnA/template/preview?resourcekey=0-Ha_b6RzKHJFYElJN20NOyg#gid=0 "Course Challenge - Scenario 2")

OR

If you don’t have a Google account, you can download the template directly from the attachment below.

[Download CSV File
Course Challenge Dataset - Scenario 2
CSV File](https://d3c33hcgiwev3.cloudfront.net/UVdWSYRdQgeXVkmEXaIHXQ_c621f39757c840b6a484589670699cf1_Course-Challenge-Dataset---Scenario-2.csv?Expires=1697414400&Signature=AjLLCgrhkUa7I7giwYfbRMlDrWT5nFkz41lGFs4S89TWlVHaSF0QxvEb0Zsu-fiPARw9wMEgjO04h1x12rqKIHn3nukOmGG6c1AHajZw1bBK0~GUhmM26RVq617k~T0Tr2DQ4Hi7XylrmAbnsifQWdIqFCMHYy8moeaV9A6s14k_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Iq-8pt8wTvmvvKbfMM75Tw_92b4d9f2803f43b3a7ef7a3a64528f13_dotted-line-right.png?expiry=1697414400000&hmac=d7C9S0zdkPem2uOvRfnZNMSkzK8_Qqt_pb9Ycq8Baig)

The patient demographic information includes data such as age and gender. As you’re learning, it’s your responsibility as a data analyst to make sure your analysis is fair. **Looking at the geographic data, you notice that all the patients live in the same zip code. How might this negatively impact the analysis?**

1 / 1 point

* It could cause the analysis to be unbiased.
* [ **It could cause the analysis to be biased.** ]
* It could cause the analysis to be useless.
* It could cause the analysis to be fair.

> Correct

### 8.Question 8

**Scenario 2 continued**

As you’re reviewing the dataset, you notice that there are a disproportionate number of senior citizens. So, you investigate further and find out that this zip code represents a rural community in Colorado with about 800 residents. In addition, there’s a large assisted-living facility in the area. Nearly 300 of the residents in the 81137 zip code live in the facility.

You recognize that’s a sizable number, so you want to find out if age has an effect on a patient’s likelihood to attend a follow-up dental appointment. You analyze the data, and your analysis reveals that older people tend to miss follow-ups more than younger people.

So, you do some research online and discover that people over the age 60 are 50% more likely to miss dentist appointments. Sometimes this is because they’re on a fixed income. Also, many senior citizens lack transportation to get to and from appointments.

With this new knowledge, you write an email to your supervisor expressing your concerns about the dataset. He agrees with your concerns, but he’s also impressed with what you’ve learned and thinks your findings could be very important to the project. He asks you to change the business task. Now, the NDS campaign will be about educating dental offices on the challenges faced by senior citizens and finding ways to help them access quality dental care.

**Changing the business task involves defining the new question or problem to be solved.**

1 / 1 point

* [ **True** ]
* False

> Correct

### 9.Question 9

**Scenario 2 continued**

You continue with your analysis. In the end, your findings support what you discovered during your online research: As people get older, they’re less likely to attend follow-up dental visits.

But you’re not done yet. You know that data should be combined with human insights in order to lead to true data-driven decision-making. So, your next step is to share this information with people who are familiar with the problem professionally. They’ll help verify the results of your data analysis.

**Fill in the blank: Subject matter experts are people who are familiar with a problem. They can help by \_\_\_\_\_, offering insights into the business problem, and validating the choices being made.**

1 / 1 point

* [ **identifying inconsistencies in the analysis** ]
* collecting data relevant to the business problem
* creating a presentation with the data
* redefining the business problem

> Correct

### 10.Question 10

**Scenario 2 continued**

The subject-matter experts are impressed by your analysis. The team agrees to move to the next step: data visualization. You know it’s important that stakeholders at NDS can quickly and easily understand that older people are less likely to attend important follow-up dental appointments than younger people. This will help them create an effective campaign for members.

It’s time to create your presentation to stakeholders. It will include a data visualization that demonstrates the lifetime trend of people being less likely to attend follow-up appointments as they get older.

**Which type of chart will be most effective?**

1 / 1 point

* A doughnut chart
* [ **A line chart** ]
* A table
* A pie chart

> Correct
