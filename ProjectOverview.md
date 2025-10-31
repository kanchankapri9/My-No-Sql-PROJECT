# MongoDB NoSQL Project

## Overview

This project was developed under the guidance of **IBM Faculty** during my **BCA (Data Science & AI)** program.  
It demonstrates the **practical use of MongoDB**, a leading NoSQL database, to manage and analyze educational data involving students, faculty, courses, and activities.

The project covers the complete MongoDB workflow — from **data storage and filtering** to **advanced analytics** using **aggregation pipelines** and **joins with `$lookup`**.

---

## Collections Overview

| Collection | Description |
|-------------|-------------|
| **students** | Stores student details, attendance, skills, and activities. |
| **faculty** | Contains faculty details and the courses they teach. |
| **courses** | Includes course information such as title, credits, and ID. |
| **enrollments** | Connects students to courses along with marks obtained. |
| **activities** | Stores records of extracurricular events and participation. |

---

## Project Sections

| Section | Focus Area |
|----------|-------------|
| **1. Complex Filters & Projections** | Using operators like `$gt`, `$all`, and `$size` for advanced filtering. |
| **2. Joins & Aggregations** | Combining collections using `$lookup` and summarizing data. |
| **3. Grouping, Sorting & Limiting** | Ranking and filtering aggregated results. |
| **4. CRUD Operations** | Performing insert, update, and delete operations with conditions. |
| **5. Array & Operator Usage** | Working with arrays using `$and`, `$ne`, and `$all`. |
| **6. Subdocuments & Nested Conditions** | Filtering documents with nested fields. |
| **7. Advanced Aggregation** | Implementing multi-level `$lookup` and `$group` for detailed analytics. |

---

## Query Outcomes and Insights

| Query | Description | Outcome / Insight |
|--------|--------------|------------------|
| **Q1** | Students with >85% attendance skilled in MongoDB and Python | Identifies consistent and multi-skilled students. |
| **Q2** | Faculty teaching more than 2 courses | Lists the most engaged faculty members. |
| **Q3** | Student names with their enrolled course titles (`$lookup`) | Displays student-course relationships. |
| **Q4** | Course title, total students, and average marks | Highlights course popularity and student performance. |
| **Q5** | Top 3 students with highest average marks | Shows top-performing students. |
| **Q6** | Department with the highest number of students | Identifies the most populated department. |
| **Q7** | Update attendance to 100% for Hackathon winners | Demonstrates mass update operations. |
| **Q8** | Delete activities before 2022 | Cleans up outdated activity records. |
| **Q9** | Upsert “Data Structures” course | Ensures integrity via conditional insert/update. |
| **Q10** | Students with Python skill but not C++ | Filters specialization-based student profiles. |
| **Q11** | Students who joined both Seminar & Hackathon | Reveals multi-event participation. |
| **Q12** | CS students scoring >80 in Web Development | Highlights top technical performers. |
| **Q13** | Faculty-wise student marks with averages | Provides detailed faculty performance analytics. |
| **Q14** | Most popular activity type | Identifies the most preferred extracurricular activity. |

---

## Key Learnings

- Practical use of **MongoDB Aggregation Pipeline**: `$lookup`, `$unwind`, `$group`, `$project`, `$sort`, `$limit`  
- Hands-on experience with **CRUD** and **conditional operations**  
- Application of **array and logical operators** for flexible querying  
- Implementing **joins in a NoSQL context**, simulating relational behavior  
- Extracting **actionable analytics** from semi-structured data  

---

## Insights Gained

- Identified top-performing students and departments using performance metrics  
- Analyzed faculty workloads and course distributions  
- Discovered trends in student participation and extracurricular interests  
- Demonstrated MongoDB’s efficiency in managing and querying semi-structured academic data  

---

## Technology Stack

| Component | Details |
|------------|----------|
| **Database** | MongoDB |
| **Environment** | MongoDB Compass / Mongo Shell |
| **Language** | Mongo Shell Queries |
| **Data Format** | JSON Documents |

---

## Project Structure

