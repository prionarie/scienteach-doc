# ScienTeach: Educational Performance Analysis and Decision Support System

ScienTeach is a web-based decision support system for General Science senior high school teachers at San Ildefonso National High School (SINHS). It helps identify and address students' learning gaps by analyzing class record data and generating instructional recommendations, including class-level actions and downloadable activities. This system was developed as a **Capstone Project** in partial fulfillment of the requirements for the Bachelor of Science in Information Technology program.

**Website:** [www.scienteach.tech](https://www.scienteach.tech)

![ScienTeach-SINHS Landing Page](/screenshots/landingpage.png)

## 1. Key Features

### 1.1. E-Class Record

![E-Class Record](/screenshots/eclassrecord.png)

A fully functional template that replicates the official e-class record administered by DepEd. Teachers will only need to copy and paste data from their spreadsheet file, and the template will mirror the calculations for their weighted and transmuted grades. They can also use 'Remedial Mode' to input the students' scores on remedial exams and calculate their improvement score.

Other replicated forms include the Table of Specifications and Item Analysis forms; both tools support planning summative tests and term examinations. Like the e-class record, teachers will only need to copy and paste existing data, and the form will calculate the needed information.

### 1.2. Score-to-Learning Competency Mapping

The key module that bridges student scores with accurate performance analysis is the Most Essential Learning Competency (MELC) mapping tool. When you paste scores into an activity column, a modal appears with a checklist of learning competencies (MELCs). After you check and save, the MELCs link to the scores in that activity column. Columns with mapped MELCs are highlighted in light blue and are applied to all other sections automatically.

![Score-MELC Mapping](/screenshots/scoremapping.png)

### 1.3. Performance Analysis and Recommendations

Performance Analysis is calculated per activity in the e-class record. Results are divided into three main sections: Class Performance Summary, Individual Performance Summary, and Recommendations. 
- Class Performance Summary consists of the students' average, highest, and lowest scores and the class's mastery level categories according to reaching the 75% mastery threshold.
- Individual Performance Summary consists of each student's scores and mastery levels.
- Recommendations classify intervention levels according to the range of learning gaps and the scope of students with identified learning gaps. Intervention levels have corresponding suggested actions. For written works and performance tasks, recommendations are intended for the class's next meeting. For summative tests and term examinations, recommendations are intended for preparing students for remedial exams.

![Performance Analysis](/screenshots/analysis.png)

### 1.4. Decision Support

As a Decision Support System, it tracks student performance in real time. It accumulates scores and maps them to MELCs within the current academic term. For each selected section, it displays the top 10 MELCs with the lowest scores, along with a button to view and download supplementary learning activity sheets.

![Decision Support](/screenshots/dss.png)

### 1.5. Term Reports

Term reports are created when an e-class record is marked as complete. This summarizes the class's academic performance by overall grades, highest-performing MELCs, the number of students that needed remediation, and the average post-remedial exam improvement score.

![Term Reports](/screenshots/reports.png)

## 2. Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python, Flask (framework), NumPy & Pandas (data analysis) |
| **Database** | MySQL |
| **Hosting** | TiDB, Railway |

## 3. Role and Contributions

**Role:** Project Manager / Backend Developer
- Led the project and managed the system's development alongside the project timeline, from client needs assessment until final deployment, under Agile development methodology.
- Authored the system requirements specification (SRS) document, managing and integrating ongoing revisions and feedback from both the client and Capstone panelists.
- Designed the technical architectural diagrams to map out the system's structural components and data flow.
- Developed and implemented the algorithms and rulesets for mapping student scores to learning competencies, performance analysis, and equivalent instructional recommendations according to student performance levels
- Monitored and validated the system's alignment with requirements, including accuracy of MELC mapping and retrieval, data analysis' statistical results, and generated recommendations during development and testing

## 4. Challenges and Solutions

Our primary challenge was adapting our project and system to the most recent requirements set by the renewed Department of Education (DepEd) Strengthened Senior High School (SHSS) curriculum. Mid-development, we changed the scope of our project and system to deliver the system within the timeframe of our Capstone course. From this experience, we balanced coordination with our stakeholders and respected their schedules. 

This predicament, however, led us to identify systematic flaws in our initial application, and we further refined our system's alignment with user requirements with minimal user friction and added workload. Additionally, we restructured our database and added features that allow the system to adapt to future changes set by DepEd. We defined these changes by comparing our project's previous and current requirements.

## 5. Recommendations

The system currently supports senior high school education under the K-12 curriculum in the Philippines. Future adaptations may align its grade computation, assessment tools, frameworks, and learning competency requirements with private schools or the curricular system of the school that may benefit from it.

In addition, this system may utilize generative AI to create instructional recommendations trained on DepEd-issued learning resources and accurately tailor learning competency requirements with suggested actions and supplementary materials.  Likewise, the project can be upgraded with agentic AI to address incremental learning gaps and continuously integrate these insights into the lesson planning process.

---

**Reflections:**

I am very grateful for having selected, developed, and defended this Capstone Project. It greatly increased my confidence and skills in requirements specification, programming, system design, and project management. Applying what I learned in my academic discipline through production-grade development while working with a client and deploying to a real environment solidified my passion for software engineering and pursuing it as a career!
