# Pierce-County-Employee-Survey-Analysis
Power BI analysis of employee engagement survey responses for Pierce County, WA

Project Overview

This project analyzes the results of an employee engagement survey conducted by Pierce County, Washington. The goal of this analysis is to uncover how employees feel about their work environment, identify trends across different departments and roles, and provide actionable recommendations to leadership to help improve overall job satisfaction.

Data Preparation & Cleaning

The original dataset contained 14,725 records. To ensure the integrity of the analysis, I used Power Query to clean and transform the data:

 * Removed Duplicates: Ensured each employee response was only counted once using the Response ID.
   
 * Handled Blank/Null Values: Filtered out empty responses to maintain accurate sentiment percentages.
   
 * Standardized Text: Cleaned up question strings for better readability on the dashboard.
   
 * Final Record Count: After cleaning, the dataset was reduced to 14,575 valid, usable records.
   
Dashboard
(Note: Upload your dashboard screenshot to your GitHub repository, click on it, copy the image address, and replace the text in the brackets above with your link.)

Key Insights & Analysis

1. Which survey questions did respondents agree with or disagree with most?
   
 * Highest Agreement: Employees felt most confident about their basic job expectations and direct management. The highest "Agree & Strongly Agree" scores were for:
   Question 1: "I know what is expected of me at work."
  
 * Highest Disagreement: The biggest pain points revolved around social connection and active appreciation. The highest "Disagree & Strongly Disagree" scores were for:
   Question 6: "I have a best friend at work" (Nearly 42% negative sentiment).
   
2. Do you see any patterns or trends by department or role?
The dashboard features interactive slicers to break down sentiment by specific Departments and Roles (Director, Manager, Supervisor, Staff).

 * A common trend in engagement data is that leadership roles (Directors/Managers) often report higher overall alignment with the company's mission and purpose compared to front-line staff. Using the dashboard filters allows HR to pinpoint exactly which departments are struggling with recognition or job clarity and which are thriving.
   
3. Actionable Recommendations for Improvement
Based on the data, I recommend that the county leadership focus on two main initiatives:

 * Implement a Consistent Recognition Program: Since a large portion of the staff feels underappreciated, department heads should be trained and encouraged to provide weekly shout-outs. This could be peer-to-peer recognition or simple, consistent feedback from direct supervisors.
   
 * Foster Team Connection: The low score for having a "best friend at work" shows a lack of social cohesion. The county should organize cross-departmental workshops, casual team lunches, or team-building events to help employees build genuine relationships beyond their daily tasks.
   
Tools Used
 * Microsoft Power BI: Data visualization, DAX measure creation, and interactive dashboard design.
   
 * Power Query: Data extraction, cleaning, unpivoting, and transformation.

