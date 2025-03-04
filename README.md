# Gamelytics: Mobile Analytics Challenge \U0001F3AE\U0001F4CA

[**Link of Kaggle Project**](https://www.kaggle.com/datasets/debs2x/gamelytics-mobile-analytics-challenge/code)

Unlock key insights into player behavior, optimize game metrics, and make data-driven decisions!

---

## **Description**

Welcome to the **Gamelytics: Mobile Analytics Challenge**, a real-world-inspired dataset designed for data enthusiasts eager to dive deep into mobile game analytics. This dataset challenges you to analyze player behavior, evaluate A/B test results, and develop metrics for assessing game event performance.

---

## **Project Context & Tasks**

### **Task 1: Retention Analysis**

- **Objective:** Calculate the daily retention rate of players, starting from their registration date.
- **Data Sources:**
  - `reg_data.csv`: Contains user registration timestamps (`reg_ts`) and unique user IDs (`uid`).
  - `auth_data.csv`: Contains user login timestamps (`auth_ts`) and unique user IDs (`uid`).
- **Challenge:** Develop a Python function to calculate retention, allowing you to test its performance on both the complete dataset and smaller samples.

---

### **Task 2: A/B Testing for Promotional Offers**

- **Objective:** Identify the best-performing promotional offer set by comparing key revenue metrics.
- **Context:**
  - The test group has a **5% higher ARPU** than the control group.
  - In the control group, **1928 users** out of **202,103** are paying customers.
  - In the test group, **1805 users** out of **202,667** are paying customers.
- **Data Sources:**
  - `ab_test.csv`: Includes `user_id`, `revenue`, and `testgroup` columns.
- **Challenge:** Decide which offer set performs best, and determine the appropriate metrics for a robust evaluation.

---

### **Task 3: Event Performance Evaluation in "Plants & Gardens"**

- **Objective:** Develop metrics to assess the success of a time-limited in-game event where players can earn unique rewards.
- **Context:**
  - Players complete levels to win exclusive items, bonuses, or coins.
  - In a variation, players may be penalized (sent back levels) after failed attempts.
- **Challenge:** Define how metrics should change under the penalty variation and identify KPIs for evaluating event success.

---

## **Dataset Information**

The provided data is split into three files, each detailing a specific aspect of the application. Here's a breakdown:

### **1. User Registration Data (`reg_data.csv`)**
- **Records:** 1,000,000
- **Columns:**
  - `reg_ts`: Registration time (Unix time, `int64`)
  - `uid`: Unique user ID (`int64`)
- **Memory Usage:** 15.3 MB
- **Description:** This dataset contains user registration timestamps and IDs. It is clean and contains no missing data.

### **2. User Activity Data (`auth_data.csv`)**
- **Records:** 9,601,013
- **Columns:**
  - `auth_ts`: Login time (Unix time, `int64`)
  - `uid`: Unique user ID (`int64`)
- **Memory Usage:** 146.5 MB
- **Description:** This dataset captures user login timestamps and IDs. It is clean and contains no missing data.

### **3. A/B Testing Data (`ab_test.csv`)**
- **Records:** 404,770
- **Columns:**
  - `user_id`: Unique user ID (`int64`)
  - `revenue`: Revenue (`int64`)
  - `testgroup`: Test group (`object`)
- **Memory Usage:** ~9.3 MB
- **Description:** This dataset provides insights into A/B test results, including revenue and group allocation for each user. It is clean and ready for analysis.

---

## **Inspiration & Benefits**

- **Real-World Relevance:** Inspired by actual challenges in mobile gaming analytics, this dataset lets you solve meaningful problems.
- **Diverse Data Types:** Work with registration logs, activity timestamps, and experimental results to gain a holistic understanding of mobile game data.
- **Skill Building:** Perfect for those honing skills in retention analysis, A/B testing, and event-based performance evaluation.
- **Community Driven:** Built to inspire collaboration and innovation in the data analytics community.

Whether you’re a beginner or an expert, this dataset offers an engaging challenge to sharpen your analytical skills and drive actionable insights. **Happy analyzing!** \U0001F389\U0001F4C8
