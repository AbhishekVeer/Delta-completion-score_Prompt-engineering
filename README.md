# Delta-completion-score_Prompt-engineering

**Prompt Engineering - calculating data completion score**

This repository contains a Python script for calculating the Delta Completion Score (DCS) for students based on their completion rates across various prompts and tasks. The calculation dynamically selects the appropriate column for each student, ensuring accurate and personalized scores.

📝 Project Overview

The dataset consists of:

**Prompt Details:** Each student works on prompts with specific completion rates.

**Student Performance:** Completion rates are recorded for each student across different prompts.

**DCS Calculation:** Delta Completion Score is calculated as the difference between the student's completion rate for their corresponding prompt and the average completion rate for the row.

## Core Features:

**Dynamic Column Matching:** Each row dynamically selects the appropriate student column based on the Student Name field.

**Custom DCS Calculation:** Computes DCS = (Student's Completion Rate - AVG), where AVG is the average completion rate across all students for the row.

**Output:** The processed dataset, including DCS, is saved to a new Excel file.
