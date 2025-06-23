# Task3- Dashboard Development

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SEHER SANGHANI

*INTERN ID*: CT08DL515

*DOMAIN*: DATA ANALYSIS

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

Investor Preferences & Behavior Dashboard

A comprehensive Power BI dashboard project that analyzes investor demographics, behavior, preferences, and investment styles based on a structured dataset. This README covers every detail about how the dashboard was conceptualized, designed, and built using Microsoft Power BI, making it suitable for learning, reference, or collaboration.

Table of Contents

Introduction

Project Objective

Dataset Description

Tools Used

Data Preparation

Power BI Workflow

Visuals Created

KPI Cards

Slicers and Filters

Dashboard Layout

Design and Aesthetics

Insights and Interpretation

Export and Sharing

Future Improvements

Conclusion

Introduction

This Power BI dashboard project is designed to analyze the preferences and behaviors of retail investors. Using a survey-based dataset, the dashboard visually explores various aspects such as demographics, preferred investment options, frequency of monitoring investments, expected returns, and sources of investment knowledge.

The project is ideal for data analysts, finance students, or business intelligence professionals looking to understand how to work with survey data and develop effective visual storytelling through dashboards.

Project Objective

The main goals of this project are:

To analyze demographic information of investors.

To understand investment habits and preferences.

To determine how investors monitor and manage their portfolios.

To gain insights into savings goals and investment durations.

To present all findings in an interactive, user-friendly Power BI dashboard.

Dataset Description

The dataset used for this project contains responses from 40 individual investors. Key columns include:

gender: Male or Female

age: Numeric age

Investment_Avenues: Yes or No (whether the respondent invests)

Various columns indicating preference ratings (1-7) for different investment types like:

Mutual_Funds

Equity_Market

Debentures

Government_Bonds

Fixed_Deposits

PPF

Gold

Stock_Marktet

Investment behavior factors:

Duration

Invest_Monitor

Expect

Source

Savings Objectives

A cleaned and processed version of the dataset (InvestorDashboard_Cleaned.csv) is used in Power BI.

Tools Used

Microsoft Power BI Desktop: For creating the dashboard

Excel: Preliminary cleaning and formatting

Python (Pandas): For transforming the dataset into clean format (optional)

Power Query Editor: For data shaping inside Power BI

Data Preparation

The raw dataset required some preprocessing to make it suitable for visualization. Steps included:

Removing Empty/Null Rows: Ensured there were no incomplete entries.

Age Binning: Converted numeric age into categories (<20, 21-30, etc.) using Power Query and pandas.

Renaming Columns: Simplified column names for clarity in Power BI.

Normalization of Text: Ensured consistent casing and removed typos.

Saved as Clean CSV: Used for import in Power BI as InvestorDashboard_Cleaned.csv.

Power BI Workflow

The following workflow was followed inside Power BI:

Importing Data: The cleaned CSV file was loaded.

Data Model: Since the data was single-table, no relationships were needed.

Creating Measures: Some DAX measures were created for KPI cards (average age, percent investing).

Visual Creation: Multiple types of visuals were created.

Aesthetic Customization: Color palette, fonts, and spacing were aligned for professionalism.

Slicers and Filters: Added to enhance interactivity.

Final Touches: Added titles, headers, and layout alignment.

Visuals Created

1. Pie Chart: Gender Distribution

Field: gender

Purpose: Show the demographic split between male and female investors.

2. Donut Chart: Investment Duration

Field: Duration

Purpose: How long investors plan to keep their investments.

3. Bar Chart: Return Expectations

Field: Expect

Purpose: Expected ROI distribution.

4. Clustered Column Chart: Investment Type Preferences by Age Group

Fields: age_group, Mutual_Funds, Gold, Fixed_Deposits, etc.

Purpose: Visualize average scores of each investment across age groups.

5. Pie Chart: Savings Objectives

Field: What are your savings objectives?

Purpose: Understand savings goals like retirement, health, education.

6. Bar Chart: Source of Financial Knowledge

Field: Source

Purpose: Where do people learn about investing?

KPI Cards

Total Investors

Field: age

Aggregation: Count

Average Age

Field: age

Aggregation: Average

% Investing

Field: Investment_Avenues

Logic: Count where Yes / Total

Top Investment Option

Logic: Highest average rating across investment types

Slicers and Filters

To allow users to interact and explore data, the following slicers were added:

Gender

Age Group

Investment_Avenues (Yes/No)

Savings Objectives

These allow dynamic filtering of visuals across the report.

Dashboard Layout

The dashboard is divided into three sections:

Header: Project title and summary

KPI Cards: Four cards at the top

Main Visuals:

Left: Demographics

Center: Preferences & Monitoring

Right: Objectives & Sources

Design and Aesthetics

Color Palette: Pastel tones, teal, gold, light grey

Fonts: Segoe UI for clarity

Card Style: Shadowed, rounded cards

Chart Arrangement: Clean grid structure (3x2)

White Space: Used generously for readability

Icons: Used near KPI cards

Insights and Interpretation

Most investors fall in the age range 21-30

High preference for Gold and Mutual Funds

Over 92% of respondents invest actively

Majority monitor their investments monthly or daily

Retirement is the most common savings goal

Most people expect 20%-30% returns

Financial knowledge is mostly sourced from Internet and Magazines

Export and Sharing

The report can be exported as PDF for presentations.

Power BI file can be published to Power BI Service.

Can also be embedded in websites or shared via GitHub.

Future Improvements

Add trend line if time-series data becomes available

Expand with more demographic features (city, education)

Enable drill-through pages for deep dives

Add AI visuals like Smart Narrative for automatic insights

Conclusion

This Power BI dashboard project illustrates how to turn a basic investor survey into meaningful insights. From designing visuals to applying interactivity, the dashboard combines technical execution with storytelling. It serves as a learning reference and a powerful tool for exploring investor behavior.
