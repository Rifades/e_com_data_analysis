E-commerce Customer Purchase Analysis
Project Overview
This project provides a comprehensive data analysis of a simulated e-commerce customer purchase dataset. The goal is to extract meaningful insights from the data to answer key business questions and inform strategic decisions, such as identifying the most valuable customers, understanding purchasing trends, and optimizing marketing campaigns.
The analysis is performed using Python, with a focus on core data science libraries like Pandas for data manipulation, and Matplotlib and Seaborn for data visualization.
Key Questions Explored
* Data Cleaning and Preparation: What steps are needed to clean and prepare the dataset for analysis?
* Customer Demographics: What are the age and gender distributions of the customer base?
* Purchase Trends: When are customers most active? What are the most popular items?
* Revenue & Value: Who are the top-spending customers? What is the average order value?
* Geographic Analysis: Where are the customers located?
Dataset Description
The dataset is a fictional CSV file named ecom_purchases.csv, containing approximately 30,000 entries. It includes the following fields:
* email: Unique identifier for each customer.
* age: Age of the customer.
* gender: Gender of the customer.
* country: Country of the customer's residence.
* item_id: Unique identifier for the purchased item.
* item_price: Price of the purchased item.
* purchase_date: The date of the purchase.
* weekday: The day of the week the purchase was made.
Analysis and Findings
The analysis notebook, Cust_Purch_Data_Exercise.ipynb, guides the user through the entire process, from data loading to deriving insights. Key findings include:
* Most Active Purchase Day: The data shows that Saturday and Wednesday are the days with the highest number of purchases. This information is crucial for planning marketing activities and resource allocation.
* Top 5 Customers by Purchase Count: The analysis identified the top five customers who made the most individual purchases, providing a list of high-volume buyers.
* Most Common Item Purchases: The top five most frequently purchased items were identified, which can help in inventory management and promotional strategies.
* Revenue Analysis: The total revenue, average purchase price, and other key financial metrics were calculated to assess the business's overall performance.
Technologies and Libraries Used
* Python: The core programming language for the project.
* Pandas: Essential for data loading, cleaning, and manipulation.
* Matplotlib: Used for creating static visualizations to represent data insights.
* Seaborn: A powerful library built on Matplotlib, used for creating more aesthetically pleasing statistical graphics.
How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Python installed. It is recommended to use a virtual environment.
3. Install the required libraries using the requirements.txt file:
4. pip install -r requirements.txt

5. Open the Cust_Purch_Data_Exercise.ipynb notebook in Jupyter or a similar environment (e.g., VS Code).
6. Run the cells in the notebook sequentially to see the full data analysis process and the resulting insights.

