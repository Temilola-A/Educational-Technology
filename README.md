# Educational Technology Analysis Report

### Introduction 

This dataset shows the operational performance of an educational technology platform that connects student with teachers for online classes. This report aims to extract insights regarding platform usage, language preferences, feedback trends, and engagement patterns, helping stakeholders make informed decisions to improve user experience and service delivery.

### Objective

The objective of this analysis is to:
-	Understand platform usage trends over time.
-	Evaluate student and tutor engagement metrics.
-	Identify peak usage times for resource optimization.
-	Highlight areas of improvement based on feedback.
-	Provide actionable recommendations for enhancing platform performance and meeting user expectations.

###	Problem Statement

The educational technology platform faces challenges in maintaining high completion rates and ensuring a seamless experience for students and teachers. The key issues include:
-	High number of terminated requests
-	Feedback indicating connectivity and session-related concerns.
-	Imbalanced demand across languages and time slots.
The goal is to identify root causes and optimize platform usage while improving satisfaction levels.

### Data Source and collection

#### Data Source
The data used for this analysis was collected from an online educational technology platform where teachers connect with students for online classes. This platform facilitates class requests, teaching sessions, and feedback collection.

#### Data Collection
This dataset comprises information on:
- Daily requests made by made by students
-	Completion and termination rates for classes.
-	Hourly trends of class requests and completions.
-	Feedback from students and teachers regarding class quality and platform usability.
-	Data related to requests grouped by subject, Language, and student level.
The data was accessed and downloaded in its raw form directly from the platform’s internal system. It includes records spanning a specific time period (May, 2022).

### Data Format
The dataset was provided in a spreadsheet format (Excel), [download here](https://microsoft.com) ,containing key columns such as:
-	Date: The date the requests occurred.
-	Status: The number of class held and terminated requests.
-	Language: The language associated with the request (e.g., English, Mandarin, Swahili).
-	Feedback: Ratings or comments from students and teachers.
-	Hour: The time of the day the request was made.

### Data Reliability
The dataset was presumed reliable as it originated from the platform’s internal systems. However, to ensure accuracy and completeness, a thorough data preparation and cleaning process was carried out to address potential inconsistencies or missing values.

### Data preparation and Cleaning

#### Steps Taken:
#### Data Cleaning:
-	Removed duplicate entries and erroneous records (missing timestamps).
-	Standardized formats for date-time fields and language names.
  
#### Data Aggregation:
-	Summarized data by daily, hourly, and categorical attributes for trend analysis.
-	Created calculated metrics such as completion rates and request percentages.

#### Validation:
-	Cross-verified data consistency across total counts, sums, and averages to ensure accurate visualization.
  
#### Visualization:
- Used Excel for dashboards, incorporating slicers for dynamic filtering and trend observation.

### Analysis and Insights

#### Overview of the Dataset
The dataset contains records of class requests and interactions on the platform. It includes the following key columns:
-	Request Number: A unique identifier for each class request.
-	Date and Time: The date and specific time the request was made.
-	Status: Indicates whether a request was completed or terminated. 
-	Student ID and Teacher ID: Unique identifiers for the involved student and teacher.
-	Teacher Name: The first and last name of the teacher assigned to the class.
-	Feedback: Ratings and comments provided by both students and teachers regarding the session.
-	Conversation SID: A unique identifier for the interaction, useful for tracking issues or replays.

#### Key Metrics and Insights

The following insights were derived after analyzing the dataset:

#### 1.	Request Volume Analysis
-	Total Requests: A total of 12500 requests were made.
-	Hourly Trends: The majority of requests were made between 6PM and 9PM, with the lowest volume between 12AM and 5AM.
-	Daily Analysis: The highest number of requests occurred 6th of May 2022.

#### 2.	Status Insights
-	Completed vs. Terminated:
-	Completed Requests: 67.22% of all requests were successfully completed.
-	Terminated Requests: 32.78% of requests were terminated before completion.

#### 3.	Students and Teacher Participation

-	Student Insights: Unique student IDs indicate that 3194 students used the platform, with the average of 2 requests per day.
-	Teacher insights: Unique teachers handled the requests. Teacher Nelson had the highest engagement classes. 

#### 4.	Feedback Analysis
-	Student Feedback: 33.7% rated the sessions positively, with common praise being, (“they loved it”, “connection was good”).
Negative feedback, (e.g., connection issues, session was too short) accounted for 7.78%
-	Teacher Feedback:  50.54% of teachers provided positive feedback about student engagement, while 8.32% noted challenges like (poor connection, student was difficult).

#### 5.	Overall Platform Efficiency
-	Request Completion Rate: The platform, maintained a [67.22%] completion rate, highlighting its effectiveness but leaving room for improvement.
-	Feedback Loop: The collection of detailed feedback from both students and teachers is a strength, enabling actionable improvements.

 ### Business Decisions and Recommendations
1.	Language Teaching Revenue Analysis
-	Question: Which language teaching brought in more revenue?
-	Analysis: Based on the “Request by Language” and “Status by Subject/Language” charts, English and French have the highest requests and completions.
-	Recommendation: These languages are likely generating the most revenue. Management should continue supporting these popular languages and consider expanding resources for English and French classes if needed.

2.	Marketing Focus for Revenue Growth
- Question: Which language teaching should management do more marketing on to bring more revenue?
-	Analysis: Spanish and Mandarin have lower request numbers compared to other languages like English and French.
-	Recommendation: Marketing efforts should focus on promoting Spanish and Mandarin to increase engagement and revenue potential.

3.	Teacher Performance Evaluation
-	Question: Which language teachers are performing better?
-	Analysis: The “Number of classes taken per Tutor” chart highlights that teacher like Nelson and Dapo have consistently high class counts, indicating strong performance and engagement.
-	Recommendation: Recognize high-performing teachers, potentially offering incentives or acknowledgements and use their methods as benchmarks for training other teachers.

4.	Student Level for Acquisition Efforts
-	Question: Which level of student should management channel acquisition efforts towards next month?
-	Analysis: Senior-level students represent 61% of total requests, suggesting higher interest at this level.
-	Recommendation: Acquisition efforts should be targeted at Senior-level students to meet the existing demand and maximize engagement.

5.	Student Level for Retention Campaigns 
-	Question: Which level should management focus retention campaigns to improve retention rates?
-	Analysis: Junior classes make up a smaller portion of requests (39%), indicating potential for improvement.
-	Recommendation: Retention campaigns should focus on Junior-level students, as increasing their engagement could help balance demand across levels.

6.	Recognition of Best Teacher of the Month
-	Question: Which teacher should be awarded as “Best Teacher of the Month” on the company’s Instagram page to recognize performance and motivate other teachers.

7.	Investment in Overnight Tutors
-	Question: Should the company invest in overnight tutors?
-	Analysis: The “Count of hour classes was held & Hour Students requested teachers” chart indicates low demand between 1AM and 5AM.
-	Recommendation: No immediate investment in overnight tutors is needed, as demand during these hours is low.

8.	Weekend Effect on Product Usage
-	Questions: How do weekends (Saturday and Sunday) affects product usage?
-	Analysis: The “Total Request per Day” trend suggests a potential decrease in activity on weekends.
-	Recommendation: Management could optimize staffing and resources based on weekday vs. weekend promotions could be tested to increase weekend engagement.

9.	Improving Completion Rate and Reducing Terminated Requests
-	Questions: What should be done to increase the completion rate and reduce terminated requests?
-	Analysis: The “Daily trends for total request, classes, and terminated request” chart shows variations in completion and termination rates.

### Appendix

Below is the Dashboard 1

![image](https://github.com/user-attachments/assets/16636a30-3be9-4e0c-b832-ecf6630cb11e)

Dashboard 2

![image](https://github.com/user-attachments/assets/98f15c9f-cbc8-4651-8125-72ff2f740558)

Dashboard 3

![image](https://github.com/user-attachments/assets/c6a888e9-b96e-489d-bdb7-eca71292ca74)


Here are the screenshots of key sections from the dashboard:

![image](https://github.com/user-attachments/assets/a03c5cdb-49d6-4808-af11-e35d7b1d4bee)

Chart1: Showing daily trends for total request, classes and terminated 


![image](https://github.com/user-attachments/assets/6d79437c-c098-4c64-9341-e19147fe50b0)

Chart2: Showing Request by Language

![image](https://github.com/user-attachments/assets/f114bcc8-9775-41bd-8409-a351676275d2)

Chart3: Showing the period of the day request came in most

![image](https://github.com/user-attachments/assets/06777278-40ef-482b-943b-b9636632b22b)

Chart4: Showing number of classes taken per tutor











  
  






