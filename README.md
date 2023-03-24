# GOOGLE PLAYSTORE APP ANALYSIS
An Excel and Tableau project carried out during my Data Analyst training with EntryLevel

# PROJECT DESCRIPTION

**Situation:** I was given a real world dataset of apps that are scraped from the Google Play App Store website to work with and understand where opportunities to drive growth and retention may lie and also track their performance in the play store.

**Task:** The purpose of this report was to understand where opportunities to devise strategies to drive app growth and retention may lie, and track their performances in the android app market. Data was scraped from the Google Play App Store website in a spreadsheet. Data collected are app categories, their ratings, reviews, number of installs, type, date updated, etc.

**Action:** I uploaded the dataset in Google spreadsheet, performed data cleaning, created pivot tables and charts in excel and finally created more visualizations and dashboard using Tableau Public.

**Result:** From the report, apps in the Games category has the highest number of reviews and therefore, has high performance while apps in the Events category has the lowest number of reviews. The root cause for underperforming apps in the Google play store is as a result of lack/poor updates of apps by their developer in the app store.


# PROBLEM

**What does the business want to achieve?** The business wants to drive growth and retention of apps and track their performance in the Google Play Store

**What is the cause of the problem?** Lack/poor updates of apps by their developers in the app store

**What data should be collected?** App categories, ratings, reviews, number of installs, type, date updated, and any other relevant data that may help in understanding app growth and retention.

**What will be the impact if the problem is not solved?** Apps will continue to underperform, leading to low growth and retention rates, resulting in decreased revenue and potentially losing market to competitors.


# DATA DESIGN

The Google Play apps data collected was unclean. I removed the duplicates, and the blank cells, ensured my headers are well written and ensured that there is consistency in the data, Below were the steps I used to clean the data;

**Duplicate Rows:** This is common in datasets and can affect the analysis. I removed duplicates from my spreadsheet (Google Sheets) with the ‘Remove Duplicate Function’ by selecting the entire datasheet by pressing the ctrl + A on my keyboard. I Clicked on Data > Remove Duplicates. All duplicated rows were removed.

**Duplicate Column:** Some apps appeared more than once in the App column. So, I deleted the duplicated apps by repeating the steps above but instead of selecting the whole datasets, I only selected the App column. 

**Blank Cells:** Blank cells can create gaps in the data and can make the data inconsistent and dirty. I used the Filter Function to remove blank cells. I selected the entire sheet/dataset and clicked on Data > Create filter. I clicked on the filter icon at the top of one of the columns which look like an inverted pyramid. In the dropdown menu that appeared, I clicked on the ‘Clear’ which deselects the filters. Then, I clicked on ‘Blanks’ after I have clicked on ‘Clear’ in the previous step and then clicked OK. All the blank rows were filtered out together and all the rows with data were hidden. Then I selected all the empty rows and deleted them. After deleting the blank rows, I now removed the filter by clicking on Data > Turn off Filter. The dataset was now free of blank rows. 

**Headers:** I ensured the headers were clear and concise by using underscores between words. 

**Consistent Data:** In the dataset, I noticed that “nan” was used to replace some values of “0”. So, I used the Edit > Find and Replace function to replace all values of “nan” with “0”, making my dataset consistent. 

After I cleaned the data, I now analyzed the dataset by creating pivot tables and charts with the Google sheet and designed a dashboard with Tableau Public for more insight into the data. 


# FINDINGS

From the dashboard;

The Games category has the highest number of reviews with an overall review sum of 1,415,536,650. While the Events category has the least number of reviews (161,018) followed by the Beauty (396,240) and the Parenting categories (958,331). 

Apps with 1,000,000+ installs have the highest installs in the Google play store with a total of 1,488 unique installs. 

Apps in the Family category have the highest count of ratings and apps in the Beauty and Comics have the least count of ratings. 

There are more free apps than paid apps in the app play store. 

Age category/Content rating ‘Everyone’ has rated the apps more than any others.

### Figure 1: Total Reviews by Category

![figure 1](https://user-images.githubusercontent.com/127628021/227494248-5c6856bc-e1b7-4846-86d3-a66187b04849.png)

The Games category has the highest app reviews while the Events category has the least reviews followed by the Beauty and the Parenting categories.

### Table 1: Top 20 Most Reviewed Apps 

![Tab 1](https://user-images.githubusercontent.com/127628021/227494692-7a5fc7fb-3acf-4eda-a44a-2292f8a3c104.png)

### Figure 2: The Count of Installs

![figure 2](https://user-images.githubusercontent.com/127628021/227494892-c49abfa7-d62b-4937-a7cf-85aa5278bc5b.png)

Apps with 1,000,000+ installs has the highest installs in the app play store with a total of 1,488 unique installs

### Table 2: The Count of Free and Paid Apps

![Tab 2](https://user-images.githubusercontent.com/127628021/227495495-3a5fc0f8-cab9-4533-a8f6-ff69a7fd0004.png)

### Figure 3: The Count of Apps by Category

![figure 3](https://user-images.githubusercontent.com/127628021/227495670-0592f888-b5d6-4122-aec5-fa92b5d6cdc9.png)

Apps in the Family category has the highest number of apps in the play store with 1,850 number of apps, and apps in the Beauty category has the lowest number of apps in the play store, having total number of 50 apps.


# ANALYSIS

We will use the 5 Whys technique to determine the root cause of poor app performance in the Google Play Store by repeatedly asking the question “Why”.

The Root Cause Analysis (The Whys): 

Why do some app categories have low performance in the Google Play App Store? Because they have a low number of installs. 

Why do apps have a low number of installs? Because they have low to no ratings and reviews. 

Why do they have low/no ratings and reviews? Because there can be bugs, poor UI, or fake apps. 

Why do we have bugs, poor UI, and fake apps in Google Play? Because of the non-update of apps to the latest version by the app creator or developer. 

Why have the apps not been updated regularly? Because the developers do not have a clear understanding of the user needs and preferences.


# CONCLUSION

Based on the insights gathered from the dashboard and the root cause analysis, it is clear that app developers need to focus on updating their apps regularly to improve their performance in the Google Play Store. To drive growth and retention, app developers should aim to fix bugs, improve the user interface, and ensure that their apps meet the needs and preferences of their users.

In addition, it is recommended that apps with low reviews be optimized, particularly those in the Social, News & Magazines, and Shopping Categories. Monetization of some apps could also be considered to increase revenue and support the development and improvement of the apps.

Finally, by addressing the root cause of the problem and optimizing and monetizing apps where necessary, app developers can improve app performance, increase customer reviews, ratings, and installs, and ultimately drive growth and retention in the Google Play Store.


