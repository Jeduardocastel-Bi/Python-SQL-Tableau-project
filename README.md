# 🍉 A/B Test: Online International Store

## 📖 Project Description  
You have been tasked with analyzing an A/B test conducted by an international online store. The previous analysts started the experiment but abandoned it mid-project (to start a watermelon farm in Brazil). They left behind only the technical specifications and the expected test outcomes.  

### Technical Description:  
- **Test Name**: `recommender_system_test`  
- **Groups**: A (control), B (new payment funnel)  
- **Launch Date**: 2020-12-07  
- **Cutoff Date for New Users**: 2020-12-21  
- **End Date**: 2021-01-01  
- **Audience**: 15% of new users from the EU region  
- **Purpose**: Test the impact of an improved recommendation system  
- **Expected Outcome**:  
  - Within 14 days of registration, users in the test group should show improved conversion rates across these events:  
    - **Product Page Views** (`product_page`)  
    - **Adding Items to Cart** (`product_card`)  
    - **Purchases** (`purchase`)  
  - A minimum of **10% increase** at each stage of the funnel (`product_page → product_card → purchase`).  
- **Target Participants**: 6,000  

---

## 🛠️ Key Features  
1. **Exploratory Data Analysis**: Initial insights and patterns in the dataset.  
2. **Data Cleaning and Manipulation**: Ensure data is ready for analysis.  
3. **Outlier Detection**: Identify and handle anomalies.  
4. **Event Funnel Analysis**: Examine customer conversions at different stages of the funnel.  
5. **Sample Distribution Analysis**: Evaluate the distribution and balance of test samples.  
6. **A/B Test Results**: Statistical analysis of test outcomes using hypothesis testing.  

---

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Data Manipulation**: Pandas  
- **Visualization**: Matplotlib, Seaborn  
- **Statistical Testing**: SciPy, Stats  

---

## 📈 Skills Developed  
- Data Cleaning and Preparation  
- Funnel Event Analysis  
- A/B Testing  
- Hypothesis Testing  
- Data Visualization  

---

🔗 **Link to the Project**:

__________________________________________________________________

# 🛠️ SQL Queries with PostgreSQL Database Connection  

## 📖 Project Description  
The coronavirus pandemic took the world by surprise, drastically altering daily routines. City dwellers no longer spent their free time in cafes or malls; instead, more people stayed home and turned to reading. This trend caught the attention of startups eager to develop new applications for book lovers.  

You have been provided with a database from one such service. It contains data about books, publishers, authors, customer ratings, and book reviews. This information will be used to generate queries about the most popular books, relevant publishers, and top authors.  

---

## 🛠️ Key Features  
1. **Database Connection**: Establish a connection with a PostgreSQL database.  
2. **Table Exploration**: Create a function to inspect database tables.  
3. **Data Display**: Create a function to show query results using Pandas.  
4. **SQL Queries**:  
   - Identify books published after January 1, 2000.  
   - Determine the number of user reviews and the average rating for each book.  
   - Find the publisher with the most books, filtering for books with over 50 pages.  
   - Identify the author with the highest average book rating.  
   - Calculate the average number of text reviews among users who rated more than 50 books.  

---

## 🛠️ Technologies Used  
- **Programming Language**: SQL  
- **Data Preparation**: SQL  
- **DBMS**: PostgreSQL  
- **Data Manipulation**: Pandas  

---

## 📈 Skills Developed  
- Connecting to a PostgreSQL database  
- Data extraction and transformation  
- Writing advanced SQL queries  
- Implementing subqueries  
- Using Python to display query results  

---

🔗 **Link to the Project**:

_______________________________________________________________________

# 📞 Telecommunications: Identifying Ineffective Operators

## 📖 Project Description  
The virtual phone service CallMeMaybe is developing a new feature to provide supervisors with information about the least effective operators. An operator is considered ineffective if they have a high number of lost incoming calls (both internal and external) and a long wait time for incoming calls. Additionally, if an operator is supposed to make outgoing calls but has made very few, that is also a sign of inefficiency.

The datasets contain information on the use of the CallMeMaybe service. Its clients are organizations that need to distribute large volumes of incoming calls among several operators or make outgoing calls through their operators. Operators can also make internal calls to communicate with each other.

---

## 🛠️ Key Features  
- **Exploratory Data Analysis (EDA)**: Focused on identifying missing values, duplicates, and outliers.  
- **Missing Data Calculation**: Analyze the weight of missing values in the datasets.  
- **Data Enrichment**: Added columns with data separated by months, weeks, and days.  
- **Call Distribution**:  
  - Incoming and outgoing calls by day, week, and month.  
  - Incoming and outgoing calls by operator.  
- **Operator Performance Metrics**:  
  - Calculate the number of incoming and outgoing calls per operator.  
  - Calculate the operator inefficiency index.  
  - Identify operators by plan type.  
  - Calculate relevant metrics by plan type.  
  - Identify ineffective operators by plan.  
- **Statistical Hypothesis Testing**:  
  - Comparison between wait times for different plans.  
    - Null Hypothesis: There are no significant differences between wait times for different plans.  
    - Alternative Hypothesis: There are significant differences (at least one) between wait times for different plans.  
  - Comparison between the average wait times of the most and least effective operators.  
    - Null Hypothesis: There are no significant differences in the average wait time between the most and least effective operators.  
    - Alternative Hypothesis: There are significant differences in the average wait time between the most and least effective operators.  
  - Comparison between the average wait times of operators with more and fewer lost calls.  
    - Null Hypothesis: There are no significant differences in average wait time between operators with more and fewer lost calls.  
    - Alternative Hypothesis: There are significant differences in average wait time between operators with more and fewer lost calls.

---

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Data Cleaning and Manipulation**: Pandas  
- **Data Visualization**: Matplotlib, Seaborn  
- **Statistical Hypothesis Testing**: SciPy, Stats  

---

## 📈 Skills Developed  
- Data cleaning and preparation  
- Data visualization  
- Event funnel analysis  
- A/B testing  
- Hypothesis testing  

---

🔗 **Link to the Project**: 
