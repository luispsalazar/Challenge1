#  Kickstarting with Excel (Challenge # 1)

## Project Overview

Data has been provided for different fundraiser campaigns, in an Excel worksheet. In order to easily analyze the information, some simplification and visualization (tables, plots) will be required.

The "Theater Outcome by Launch Date", and the "Outcomes Based on Goals" will be analyzed in this exercise.

### Purpose

Use Microsoft Excel capabilities, including built-in functions, to analyze the outcomes of two campaigns.

* Pivot Tables are used to summarize the information, filtering just the required data to be studied
* A Line Plot is also used to visually identify trends and changes of outcomes vs time or ranges. This is really hard to do in a table format
* COUNTIFS is also used to present the data in "ranges", this is equivalent to the Histogram, but in a Table, instead of a plot

## Analysis and Challenges

### 1. Analysis of Outcomes Based on Launch Date

The Theater category was filtered out using a Pivot Table, and from here, a Plot was prepared. The successful, failed and canceled campaigns were displayed vs time (in months).

Looking at the plot, **May** is the month with the highest number of successful campaigns. But when the trendline is added, the trend is a reduction of success as the year goes on; around 20 successful campaigns less comparing December with January.

![Plot with trendlines](Resources\Theater_Outcomes_vs_Launch_trendline.png)

The failed and cancelled campaings remain somehow flat throughout the year. This is confirmed by the trendlines.

### 2. Analysis of Outcomes Based on Goals

### 3. Challenges and Difficulties Encountered

Showing the months in section 1 took some time. The Date Created had to be selected, and then Excel recognizes this parameter as "time", giving the option of selecting years, quarters or months. This was not obvious at the beginning.

Also in section 1, it was requested to sort the columns in descending order. As usual, Excel's right click was the way to "sort" the columns as desired.

In section 2, the instructions were followed, but when I "verified" the totals, it was not right. Whenever I use excel, I "verify" the totals using a second method (adding the totals in a different way or place). The projects from 4999 to 5000 are not accounted for, and the same is valid for all the rest of the ranges. I made the decision to exclude 5000 in the previuos range and include this value in the following range. When I did this for all the ranges, the verification showed that all the projects were accounted for.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
