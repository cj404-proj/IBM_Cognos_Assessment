# IBM Data Analyst Capstone Project
## IBM Cognos Analytics Assessment

In this assessment, I've created a dashboard with three tabs. They are
1. Current Technology Used
2. Future Technology Used
3. Demographics

**Here is the link to the original cognos dashboard.** [Link](https://ap2.ca.analytics.ibm.com/bi/?perspective=dashboard&pathRef=.my_folders%2FAssesment&action=view&mode=dashboard&subView=model0000018f420ee5ca_00000002){:target="_blank"}

The first two tabs uses `m5_survey_data_technologies_normalised.csv` and the last tab uses `m5_survey_data_demographics.csv`.

Each tab is a 2x2 grid i.e. in each tab 4 visualizations are available.

# Current Technology Usage Dashboard

## Panel 1
- **Metric:** Top 10 LanguageWorkedWith
- **Visualization:** Bar Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Bars, Length, Color
- **Features:** Show value labels
- **Chart Title:** Top 10 Languages Worked With

## Panel 2
- **Metric:** Top 10 DatabaseWorkedWith
- **Visualization:** Column Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Bars, Length, Color
- **Features:** Show value labels
- **Chart Title:** Top 10 Databases Worked With

## Panel 3
- **Metric:** PlatformWorkedWith
- **Visualization:** Word Cloud Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Words, Size, Color
- **Chart Title:** Platform Worked With

## Panel 4
- **Metric:** Top 10 WebFrameWorkedWith
- **Visualization:** Hierarchy Bubble Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Bubbles, Size, Color
- **Chart Title:** Top 10 Web Frameworks Worked With

# Future Technology Trend Dashboard

## Panel 1
- **Metric:** Top 10 LanguageDesireNextYear
- **Visualization:** Bar Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Bars, Length, Color
- **Features:** Show value labels
- **Chart Title:** Top 10 Desired Programming Languages for Next Year

## Panel 2
- **Metric:** Top 10 DatabaseDesireNextYear
- **Visualization:** Column Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Bars, Length, Color
- **Features:** Show value labels
- **Chart Title:** Top 10 Desired Databases for Next Year

## Panel 3
- **Metric:** PlatformDesireNextYear
- **Visualization:** Tree Map Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Area hierarchy, Size, Heat
- **Features:** Contrast label color
- **Chart Title:** Desired Platforms for Next Year

## Panel 4
- **Metric:** Top 10 WebFrameDesireNextYear
- **Visualization:** Hierarchy Bubble Chart
- **Data Asset:** m5_survey_data_technologies_normalised.csv
- **Fields:** Bubbles, Size, Color
- **Chart Title:** Top 10 Desired Web Frameworks for Next Year

# Demographics Dashboard

## Panel 1
- **Metric:** Respondent Gender Distribution
- **Visualization:** Pie Chart
- **Data Asset:** m5_survey_data_demographics.csv (filtered by Gender)
- **Fields:** Segments, Size
- **Features:** Display %
- **Chart Title:** Respondent Gender Distribution

## Panel 2
- **Metric:** Respondent Count by Country
- **Visualization:** Map Chart
- **Data Asset:** m5_survey_data_demographics.csv
- **Fields:** Regions-Locations, Regions-Location color
- **Chart Title:** Respondent Count by Country

## Panel 3
- **Metric:** Respondent Age Distribution
- **Visualization:** Line Chart
- **Data Asset:** m5_survey_data_demographics.csv
- **Fields:** x-axis, y-axis
- **Features:** Show value labels, Show markers
- **Chart Title:** Respondent Age Distribution

## Panel 4
- **Metric:** Respondent Count by Gender and Education Level
- **Visualization:** Stacked Bar Chart
- **Data Asset:** m5_survey_data_demographics.csv (filtered by Gender)
- **Fields:** Bars, Length, Color
- **Features:** Show value labels
- **Chart Title:** Respondent Gender vs. Education Level
