Non-Technical Skills for Urology Trainees: A Double-Blinded Study Comparing ChatGPT-4 AI and Consultant Interaction
Overview
This repository contains the data and analysis code for the study titled "Non-Technical Skills for Urology Trainees—A Double-Blinded Study of ChatGPT-4 AI Benchmarking Against Consultant Interaction." The study investigates the effectiveness of AI-generated feedback (using ChatGPT-4) compared to human consultant feedback in enhancing non-technical skills (NTS) training for urology trainees.

Project Description
The study involved 27 urology trainees who participated in simulated clinical scenarios designed to assess and improve their non-technical skills. Participants interacted with both AI and human consultants in a double-blinded setup to receive feedback on their performance. The effectiveness of the feedback was evaluated through pre- and post-intervention surveys, expert evaluations, and thematic analysis of the interactions.

Data Files
data/trainee_responses.csv: Contains the pre- and post-intervention survey responses from the urology trainees.
data/expert_evaluations.csv: Contains the evaluations from the expert panel reviewing the AI and human consultant interactions.
data/transcripts/: Directory containing anonymized transcripts of the interactions between trainees and consultants (both AI and human).
Analysis Methodology
Data Preparation
Data Cleaning: Missing values were handled by excluding incomplete responses.
Encoding: Likert scale responses were encoded numerically for quantitative analysis.
Statistical Analysis
Programming Language: Python
Libraries Used:
pandas: For data manipulation and cleaning.
NumPy: For numerical computations.
SciPy: For statistical tests (Wilcoxon signed-rank test and Mann-Whitney U test).
matplotlib and seaborn: For data visualization.
Statistical Tests
Wilcoxon Signed-Rank Test: Assessed changes in participants' responses from pre- to post-intervention within the same group.
Mann-Whitney U Test: Compared post-intervention responses between the AI and human feedback groups.
Effect Sizes: Calculated using rank-biserial correlation to quantify the magnitude of observed differences.
Significance Level: A p-value of less than 0.05 was considered statistically significant.
Qualitative Analysis
An inductive thematic analysis was conducted based on Braun and Clarke's six-phase framework:

Familiarization: Reading and re-reading transcripts to become immersed in the data.
Coding: Generating initial codes to identify significant features.
Theme Development: Collating codes into potential themes.
Reviewing Themes: Refining themes to ensure they accurately reflect the data.
Defining and Naming Themes: Clearly defining each theme.
Writing Up: Producing a report with vivid examples and relating findings back to research questions.
Results Summary
Quantitative Findings
Trainee Feedback:

Significant improvements were observed in several feedback dimensions following both AI and human feedback.
AI feedback showed statistically significant changes in response length, critical thinking, and personalized feedback.
Human feedback led to significant increases in language terminology, complexity, positive reinforcement, and personalized feedback.
Expert Evaluations:

Experts found that AI could significantly augment the teaching of non-technical skills.
In dimensions like facilitating reflection and encouraging critical thinking, AI's performance was comparable to human consultants.
Qualitative Findings
AI Consultant:

Displayed a friendly and supportive demeanor.
Encouraged critical thinking and reflection.
Tended to adopt a didactic style, sometimes dominating the conversation.
Human Consultant:

Effective in prompting reflective thought and providing positive reinforcement.
Emphasized teamwork and leadership.
Varied in depth and substance of questions, with occasional limitations in discussing non-technical skills.

Contact
For questions or further information, please contact:

Principal Investigator: Dr. Matthew Pears
Email: mape2971@outlook.com
Acknowledgments
We are grateful to all participants and the expert panel for their valuable contributions. Special thanks to the support provided by the surgical boot camp and affiliated institutions.

License
This project is licensed under the MIT License - see the LICENSE file for details.
