# Data Analysis Portfolio:
**PROJECTS**: _(1)- Electronic_Store_Purchases.ipynb_, _(2)- 911_Calls.ipynb_, _(3)- NYC_Airbnb.ipynb._ <br>
**Tools**: Pandas, Matplotlib, Seaborn and NumPy.

Repository containing portfolio of data analysis projects completed by me for self learning and hobby purposes.
**Note**: Data used in the projects (accessed under data directory) is for demonstration purposes only.

## Setup:
To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br>
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html

## Background Information:
### PROJECT 1 - Electronic Store Purchases. <br>
PART A: (_Data Cleaning_). Tasks during this section include:
- STEP 1 – dropped Rows with (Column) names as their cell values.
- STEP 2 – dropped Rows with (all) NAN Values.
- STEP 3 – dropped duplicate Rows except for the (first) occurrence.
- STEP 4 – converted ['Order ID', 'Quantity Ordered', 'Price Each'] into a (numeric) Object.
- STEP 5 - converted ['Order Date'] into a (DateTime) Object, then (Split) into different columns: [Hour, Date, ..., Year].
- STEP 6 – Segregated ['Order Date'] into a Day/Night time basis.
- STEP 7 – Added Sales and City Column to the DataFrame. <br>

PART B: (_Data Exploration & Visualization_). In this section we explore (8) high-level (business) questions related to our data:
- QUESTION 1 – Top 10 (Products) for Sales?
- QUESTION 2 – Top 10 (Cities) for Sales?
- QUESTION 3 – Top 10 (Dates) for Sales, across all (Years)?
- QUESTION 4 – (Best/Worst) Month for Sales?
- QUESTION 5 – (Sales) during the Day/Night?
- QUESTION 6 – (Time) to Display Advertisements to (Maximise) likelihood of Customers buying Products?
- QUESTION 7 – (Products) which are often sold (Together)?
- QUESTION 8 – Price-to-Sales (Ratio)? Does this have any significance?
- QUESTION 9 – Correlation between the Variables?

### PROJECT 2 - 911 Calls for Montgomery County, PA. <br>
PART A: (_Data Cleaning_). Tasks during this section include:
- STEP 1 – dropped ["e"] because it's (insignificant) and also a (Dummy) Variable - (always 1)!
- STEP 2 – replaced NAN values for ["zip"] with '00000' after (realising) some countries do not use these codes.
- STEP 3 – dropped duplicate Rows except for the (first) occurrence.
- STEP 4 – converted ['timeStamp'] into a proper (DateTime) Object, then (Split) into different columns: [Hour, Date, ..., Year].
- STEP 5 – segregated ['timeStamp'] into a Day/Night time basis.

PART B: (_Data Exploration & Visualization_). In this section we explore (16) high-level questions related to our data:
- QUESTION 1 – Top 10 (Townships) for Calls?
- QUESTION 2 – Top 10 (Zipcodes) for Calls?
- QUESTION 3 – Top 10 (Stations) for Calls?
- QUESTION 4 – Top 10 (Dates) for Calls, across all (Years)?
- QUESTION 5 – Most common Reason (type) for Calls?
- QUESTION 6 – Most common (Reason) type, based on each (Day) of the Week?
- QUESTION 7 – Most common (Reason) type, based on each (Month)?
- QUESTION 8 – Most common (Reason) type, based on each (Hour)?
- QUESTION 9 – Top 10 (Incidents) reported for Calls?
- QUESTION 10 – (Frequency) of calls during Day/Night?
- QUESTION 11,12,13 – (EMS, Fire & Traffic) calls per Day, across all (Years)?
- QUESTION 14 – Heatmap of Calls for each (Day)?
- QUESTION 15 – Heatmap of Calls for each (Month)?
- QUESTION 16 – Correlation between the Variables?

### PROJECT 3 - NYC_Airbnb, (2019). <br>
PART A: (_Data Cleaning_). Tasks during this section include:
- STEP 1 – dropped ["id", "name", "host_name"] not only because they're (insignificant), but also for (ethical) reasons!
- STEP 2 - replaced NAN values for ["reviews_per_month"] with 0.
- STEP 3 - fortunately, there weren't any Duplicates in our DataFrame.
- STEP 4 - columns were already of the (correct) Types.

PART B: (_Data Exploration & Visualization_). In this section we explore 10 high-level questions related to our data:
- QUESTION 1 – Top 10 (hosts) for Listings?
- QUESTION 2 – Most (reviewed) hosts on Airbnb?
- QUESTION 3 – Most (reviewed) hosts (per-month)?
- QUESTION 4 – Top 3 (neighbourhood groups) on Airbnb?
- QUESTION 5 – Relation of (Neighbourhood groups) with category (Room type)?
- QUESTION 6 – Price distribution for each (Neighbourhood group)?
- QUESTION 7 – Price distribution for each (Room type – Private room, Entire home/apt, Shared room)?
- QUESTION 8 – Minumum nights distribution for each (Room type – Private room, Entire home/apt, Shared room)?
- QUESTION 9 – Availability in (Year) distribution for each (Room type – Private room, Entire home/apt, Shared room)?
- QUESTION 10 – Correlation between the Variables?

PART C: (Bonus).
- BONUS QUESTION – Top 25 (words) used by hosts to (name) their listings?
