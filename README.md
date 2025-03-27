# Customer-Center-Performance-Report

![GitHub](https://img.shields.io/badge/GitHub-VenkataSaiRam-black?style=flat-square&logo=github&logoColor=white)

## Overview

This project features a comprehensive Customer Call Center Perfomance Dashboard created using Power BI. The dashboard designed to analyze and visualize the performance metrics of a call center. It provides insights on calls received, answered, and customer satisfaction levels

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)

## Features

- **Total Calls Overview**: Displays the total number of calls received and answered.
- **Monthly Call Statistics**: Visualizes call data segmented by month.
- **Agent Performance Metrics**: Calculates and displays the average speed of answer and other statistics for each agent.
- **Customer Satisfaction Tracking**: Visualizes the flow of customer satisfaction regarding call resolution.
- **Topic Wise Resolution**: Breaks down the resolution metrics by different topics.

**Dashboard Components**
1. Key Metrics:
- Number of Agents: 8
- Total Calls Received: 5000
- Total Answered Calls: 4054
- Average Speed of Answer: 54.75 seconds
- Average Talk Duration: 2.63 minutes
- Overall Customer Satisfaction: 3.40/5

2. Total Calls by Month:
- Visual representation of calls received for January, February, and March.

3. Customer Satisfaction Flow:
- Flowchart indicating answered calls and resolutions, providing an at-a-glance view of customer satisfaction.

4. Agent Performance Report:
Detailed statistics for each agent including:
- Total calls received
- Answered calls percentage
- Overall customer satisfaction rating
- Average talk duration
- Resolved call percentage

## Installation

To view the Call Center Dashboard, follow these steps:

Clone the repository:
   git clone https://github.com/Venkatasr665/Customer-Center-Performance-Report.git

## Usage

1. Open the Dashboard:
- Launch Power BI Desktop.
- Open the Call Center Dashboard file (Customer Service Report.pbix) from the cloned repository.

2. Explore the Dashboard:
- The dashboard consists of multiple pages. Use the tabs at the bottom to navigate between different views.

3. Interact with Visualizations:
- Hover over charts and graphs to view tooltips that provide additional information.
- Click on different elements (e.g., bars in a bar chart) to filter the data displayed in other visualizations on the dashboard.

5. Use Filters and Slicers:
- On the right side of the dashboard, you will find slicers for filtering data by agents
- Select or deselect options in the slicers to dynamically update the visualizations based on your selections.

## DataSource

The data used in this Call Center Perfomance Dashboard was created in an Excel file (Call-Center-Dataset.xlsx). Below are the details regarding the data:

  - File Format: Excel (.xls or .xlsx)
  - File Name: Call-Center-Dataset.xlsx

### *Data Structure*:
The Excel sheet includes columns such as:
- Call ID : A unique identifier for each call, allowing for easy tracking and referencing of interactions.
- Agents: The name or identifier of the agent who handled the call. This helps in evaluating individual agent performance.
- Date: The date when the call was received. Important for analyzing trends over time.
- Time: The specific time the call took place. Useful for identifying peak call times.
- Topic: The subject or category of the call. Topics help in analyzing which issues are most frequently addressed.
- Answered: Indicates if the call was answered (Y) or not (N). Crucial for measuring response rates.
- Resolved: Confirms whether the issue was resolved during the call. This helps assess the effectiveness of the call.
- Speed of Answer in Sec: The time taken from when the call was received to when it was answered, measured in seconds. Important for evaluating responsiveness.
- Average talk duration: The average length of conversations for answered calls, providing insight into the complexity of the issues addressed.
- Satisfaction Rate: A numerical rating reflecting customer satisfaction after the call. Often measured on a scale (e.g., 1 to 5) to assess overall service quality.

### *Data Creation*:
The data was taken from the forage

### *Usage in Power BI*:
The Excel file is imported into Power BI, where it is transformed and modeled to create the visualizations displayed in the dashboard. Ensure that the data model is correctly set up to reflect the visualizations accurately.


![Alt text](https://github.com/Venkatasr665/Customer-Center-Performance-Report/blob/main/Customer%20care%20center.png?raw=true)
