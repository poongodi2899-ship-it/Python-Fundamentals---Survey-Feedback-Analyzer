# 🎫Customer Support Ticket Analyzer Using Python Fundamentals
## 📖 Project Overview
Customer support is an essential part of every business because it helps maintain customer satisfaction and improve service quality. Every day, organizations receive numerous customer support tickets regarding technical problems, service requests, complaints, and feedback. Manually analyzing these tickets can be time-consuming and may lead to missing important insights.

The Customer Support Ticket Analyzer project was developed using Python to automate the process of organizing, cleaning, and analyzing customer support ticket data. The project demonstrates how Python programming concepts such as dictionaries, lists, loops, functions, conditional statements, string manipulation, and sets can be applied to solve a real-world business problem.

The system stores customer ticket information, cleans the issue descriptions, performs keyword-based analysis, calculates summary statistics, and generates meaningful insights that can help organizations understand customer concerns and improve support services.


## 🎯 Project Objectives

The primary objectives of this project are:

- To understand how Python dictionaries and lists can be used to organize structured data.
- To allow users to add new customer support tickets dynamically.
- To perform data cleaning for consistent and accurate text analysis.
- To analyze issue descriptions using keyword-based searching.
- To generate useful business insights from customer support data.
- To improve programming skills by implementing loops, functions, conditionals, and string operations.

## 📂 Dataset Description
The project begins with a predefined dataset containing customer support tickets. Each ticket includes the following information:

- Ticket Number
- Customer Name
- Issue Description
- Priority Level (High, Medium, Low)

The ticket information is stored using a dictionary of lists, which allows easy access, updating, and analysis of data.

## ⚙️ Implementation Steps

### 📌 Step 1 – Loading Customer Ticket Data

The first step involved loading the predefined customer ticket dataset into Python.

The ticket information was stored using a dictionary containing four lists:

- Ticket Number
- Customer Name
- Issue Description
- Priority

The complete ticket information was displayed in a readable format using loops.

This step helped in understanding how structured data can be stored and accessed efficiently using Python data structures.

### ➕ Step 2 – Adding New Customer Tickets

The program allows users to enter additional customer tickets dynamically.

The user is asked to enter:

- Customer Name
- Issue Description
- Priority Level

The ticket number is generated automatically, starting from Ticket Number 11.

Priority validation was also implemented to ensure that only the following values are accepted:

- High
- Medium
- Low

If the user enters an invalid priority, the program asks again until a valid value is entered.

This feature makes the program flexible and suitable for handling future customer tickets.

### 🧹 Step 3 – Data Cleaning
Customer issue descriptions often contain unnecessary punctuation marks, extra spaces, uppercase letters, or inconsistent words.

To improve the quality of analysis, the following cleaning operations were performed:

- Converted all text into lowercase.
- Removed punctuation marks such as commas, periods, exclamation marks, question marks, and hyphens.
- Removed leading and trailing spaces.
- Replaced multiple spaces with a single space.
- Replaced shorthand words such as "ok" with "okay".

After cleaning, the issue descriptions became standardized, making keyword analysis more accurate and reliable.


### 🔍 Step 4 – Keyword Analysis
A user-defined Python function was created to count the occurrence of specific keywords within customer issue descriptions.

The function performs:

- Case-insensitive searching.
- Counting the number of tickets containing a given keyword.

The following keywords were analyzed:

- Poor
- Good
- Slow
- Excellent

This analysis helps identify frequently mentioned customer experiences and common service-related issues.

For example:

- Multiple occurrences of "slow" indicate performance-related problems.
- "Poor" reflects customer dissatisfaction.
- "Excellent" and "Good" indicate positive customer experiences.

Such analysis can assist customer support teams in identifying recurring issues and improving service quality.


### 📊 Step 5 – Summary Statistics
Several summary statistics were generated from the cleaned dataset.

### Priority Analysis

The program calculated the total number of:

- High Priority Tickets
- Medium Priority Tickets
- Low Priority Tickets

This analysis helps organizations understand the urgency of customer issues and allocate resources effectively.

### Longest Issue Description

The program identified the ticket containing the highest number of words in its issue description.

The following information was displayed:

- Ticket Number
- Customer Name
- Cleaned Issue Description
- Total Word Count

This helps identify tickets that contain detailed customer feedback, which may require additional attention.

### Unique Word Extraction

The project extracted every unique word from all cleaned issue descriptions using a Python set.

The program displayed:

- Total number of unique words.
- Alphabetically sorted list of unique words.

This provides a better understanding of the vocabulary used by customers while describing their issues.

## 💡 Key Findings
The project produced several important findings:

- Customer support tickets were successfully organized and managed using Python dictionaries.
- New tickets could be added dynamically with automatic ticket numbering.
- Data cleaning significantly improved text consistency.
- Keyword analysis identified frequently occurring customer concerns.
- Priority analysis helped classify tickets according to urgency.
- Long issue descriptions provided detailed customer feedback.
- Unique word extraction helped understand commonly used customer vocabulary.

These findings demonstrate how Python can transform raw customer data into meaningful business information.

## 🚀 Business Benefits
The Customer Support Ticket Analyzer offers several business advantages:

- Faster analysis of customer support tickets.
- Better understanding of customer satisfaction.
- Easy identification of recurring issues.
- Improved decision-making based on ticket priorities.
- Reduced manual effort through automation.
- Better service planning using customer feedback analysis.

## 🛠️ Python Concepts Used
The project successfully implemented several Python concepts, including:

- Variables
- Lists
- Dictionaries
- User Input
- Loops (for loop)
- Conditional Statements (if-else)
- Functions
- String Methods
- List Operations
- Set Operations
- Data Validation
- Word Counting
- Basic Data Analysis

These concepts were combined to build a complete customer support ticket analysis system.

## ✅ Conclusion
The Customer Support Ticket Analyzer project was successfully completed using Python programming. The project demonstrated how real-world customer support data can be stored, cleaned, analyzed, and summarized efficiently.

Throughout the project, important Python concepts such as dictionaries, lists, loops, functions, conditional statements, string manipulation, and set operations were applied effectively. The project also highlighted the importance of data cleaning before performing text analysis.

Overall, this project provided valuable practical experience in Python programming and basic data analytics. It also demonstrated how businesses can use simple analytical techniques to understand customer feedback, improve support services, prioritize critical issues, and make informed business decisions.

The successful completion of this project strengthened both programming skills and analytical thinking, making it a useful foundation for future data analytics and customer service analysis projects.
