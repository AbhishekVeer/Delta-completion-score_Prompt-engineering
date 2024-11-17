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

rompt	Completion	Student Name	Student_1	Student_2	Student_3	Student_4	Student_5	Student_6	Student_7	Average	Justified Keywords	Delta Completion Score	RANK
Prompt_1	I would define beautiful girl who has a bright...	Student_1	0.7	0.70	0.8	0.7	0.7	0.6	0.6	0.685714	bright, smile, personality, confident, character	0.014286	4
Prompt_1	She has a warm smile that lights up her face, ...	Student_2	0.7	0.65	0.7	0.8	0.9	0.7	0.7	0.735714	Empathy, Intelligence, Colour	-0.085714	6
