# HirePro – Online Recruitment Portal

Welcome to **HirePro**, a secure and intuitive platform designed to streamline the recruitment process for both recruiters and candidates.

## 🔐 A. Login Interfaces

HirePro offers two distinct login paths tailored to each user type: Recruiter and Candidate Login

### 👔 1. Recruiter Login

Recruiters can access the dashboard using their admin credentials to manage job postings, review applications, and oversee recruitment workflows.


## 🧑‍💼 Recruiter Dashboard

Once logged in, recruiters are welcomed with a personalized dashboard designed to manage interviews and candidates efficiently.


### 👋 Greeting & Profile

At the top of the interface, recruiters are greeted by name and shown their profile card, including:

- Display name and initials
- Role identification (e.g., Admin)
- Quick access to logout

### 📝 Create New Interview

Recruiters can easily set up new interviews using the form provided:

- **Interview Name** – e.g., *Senior Java Developer Interview*
- **Number of Questions** – default is 3, customizable, then it will apply randomly from our bank of questions
- **Description / Notes** – optional field for interview context

A blue **"Initialize"** button starts the interview creation process.

### 📋 Existing Interviews

Below the creation form, recruiters can view a list of previously created interviews. If none exist, a message such as *"No interviews found"* will be displayed.

This dashboard streamlines the recruitment workflow, allowing recruiters to focus on evaluating candidates and managing interview logistics with ease.

## 📄 Existing Interview List

When interviews have already been created, recruiters can view and manage them directly from the dashboard.


Each entry in the list includes:

-  **Interview Title** – e.g: *Test thử hệ thống*, *FPC*, *Testing*
-  **Interview ID** – unique identifier for each entry (e.g., `hathuha01`, `hathuha03`)
-  **Action Buttons**:
  - **Description** – view or edit interview notes
  - **Candidates** – manage assigned candidates
  - **Questions** – view or modify interview questions
  - **Export Excel** – download interview data
  - **Delete** – remove the interview from the system

This interface provides recruiters with full control over their interview pipeline, enabling efficient tracking, editing, and exporting of interview data.

## 👥 Candidate Management

By clicking the **"Candidates"** button on an interview entry, recruiters can view and manage all candidates assigned to that interview.


### 📌 Candidate Table Overview

Each candidate is listed with the following details:

- **User ID** – unique identifier for the candidate (e.g., `hathuha05_IV01`)
- **Full Name** – candidate's full name
- **Access Code** – secure code used to enter the interview
- **Average Score** – calculated based on submitted answers
- **Status** – current progress (e.g., *Submitted*, *Pending*)
- **Actions**:
  - 🟢 **Grade** – evaluate and assign scores
  - ⏳ **Waiting** – indicates pending submission
  - ❌ **Delete** – remove candidate from the list

At the top of the interface, recruiters can also click **"Add New Candidate"** to assign additional participants to the interview.

This section provides full visibility and control over candidate performance, access, and evaluation.

## ❓ Question Configuration

By clicking the **"Questions"** button on an interview entry, recruiters can view and customize the interview questions.


### 🧠 Question Setup

## Time Limit (s)
- **Purpose:** Ensures candidates can demonstrate concise thinking and time management.
- **How to set:**
  - Simple knowledge questions → 30–60 seconds
  - Analytical or problem‑solving questions → 90–120 seconds
  - Case studies or role‑play scenarios → 180–300 seconds
- **Tip:** Always communicate the time limit clearly before the candidate begins.
- **Example:**  
  - "You have 60 seconds to explain how you would handle a difficult customer."  
  - "In 120 seconds, analyze the pros and cons of remote work."

## Question Content
- **Purpose:** Aligns the question with the skills you want to evaluate.
- **How to set:**
  - **Technical knowledge:** Test subject‑matter expertise.  
  - **Situational/Case study:** Simulate real‑world challenges.  
  - **Behaviour:** Explore past experiences and actions.  
  - **Creative/Logical:** Assess innovative thinking and reasoning.  
- **Tip:** Keep questions clear, specific, and avoid vague. Provide context if needed.
- **Example:**  
  - "Explain the difference between Agile and Waterfall project management."  
  - "If you were a team leader, how would you handle a project delay of two days?"  
  - "Describe a time when you had to persuade a colleague to change their approach."

## Grading Criteria
- **Purpose:** Provides consistency and fairness in evaluation.
- **How to set:**
  - Define a scoring scale (e.g., 1–5, 1–10 or 1-100).  
  - Break down into measurable criteria:
    - **Content accuracy:** Is the answer correct and relevant?  
    - **Logical flow:** Is the reasoning clear and structured?  
    - **Detail:** Are examples or evidence provided?  
    - **Soft skills:** Confidence, communication, tone.  
    - **Time management:** Did they stay within the limit?  

This section allows recruiters to design thoughtful, time-bound questions with clear evaluation standards, ensuring consistency and fairness in candidate assessment.

## 🔍 Candidate Detail View

When you click on a candidate in the list, the system will display a detailed view similar to the image below. This view includes:

- **USER ID** – Unique identifier for the candidate  
- **FULL NAME** – Candidate’s full name  
- **ACCESS CODE** – Code used to access the interview  
- **AVG SCORE** – Average score based on graded questions  
- **STATUS** – Submission status (e.g., Submitted, Pending)  
- **ACTIONS** – Available actions such as Grade, Delete, or Waiting  

This interface allows interviewers to manage candidate progress, review submissions, and assign scores efficiently.

## 📝 Grading Interface

When you click **Grade** on a candidate, the system will open the grading interface.

This view includes:
- The **video** that was recorded during the interview
- The candidate’s **response transcript**
- The **automated score** generated by AI
- An **AI-generated comment** explaining the score
- A field to **manually adjust the score** and add your own comment
- A **Save Score** button to confirm your evaluation

⚠️ **Note:** The AI provides an automatic score and feedback based on the candidate’s answer. However, you can change the score and comment if you believe the AI made a mistake or missed important context. This ensures flexibility and fairness in the evaluation process.

## 📤 Export Interview Results

By clicking the **"Export Excel"** button on an interview entry, recruiters can download a spreadsheet containing candidate performance data.


### 📁 Export Details

- The system generates an `.xlsx` file named after the interview (e.g., `Test thử câu hỏi _result.xlsx`)
- The file includes:
  - Candidate list
  - Component scores
  - Total scores
- The file is saved locally and can be opened or located via system prompts

This feature allows recruiters to archive, analyze, or share interview results efficiently using standard spreadsheet tools.

### 🎯 2. Candidate Login

Candidates enter the waiting room using their unique username and access code, ensuring a smooth and secure entry into the recruitment process.

These dual interfaces ensure a personalized experience from the very first interaction.


### 📝 Assessment Interface
After successful login, the candidate is redirected to the assessment dashboard:
 
- 📄 Test title and total number of questions are shown.  
- 📌 Instructions for the test are listed.  
- ▶️ Click **Start Assessment** to begin the test.  
- 🔒 A **Logout** option is available to exit the session.  

### 🎥 Device Check

Before the assessment begins, candidates must complete a quick device check:

- 📷 **Camera Status**: The system verifies that the webcam is functioning properly.  
- 🎙️ **Microphone Check**: Candidates should ensure their microphone is connected and working.  
- ✅ A confirmation message will appear: **"Camera ready. You can start now."**  
- ▶️ Click **READY, START NOW** to proceed to the test environment.

> This step ensures a smooth experience during video-monitored assessments.

### 🧠 Test-Taking Interface

Once the device check is complete, candidates enter the live assessment environment:

- 📋 **Question Navigation Panel**: Located on the left, showing progress through all questions (e.g., Question 1 to Question 4).
- ⏱️ **Timer**: Displayed at the top right to track remaining time for each question.
- 🎥 **Video Feed Area**: At central, there is a box show webcam recording during the test.
- ✅ **Finish Answer Button**: Click to submit your response for the current question.
- 👤 Candidate ID is shown at the bottom left (e.g., `phamthuyanh01_UV01`).

> This interface ensures structured navigation and time management during the assessment.

### 📤 Answer Submission

After completing a question, the system automatically begins the submission process:

- 🔄 A loading message appears: **"Submitting Answer... Please do not close the browser."**
- ⏳ This ensures the response is securely uploaded and recorded.
- 🚫 Candidates must avoid refreshing or closing the browser during this step.
- ✅ Once submitted, the question status updates to **"Done"** in the progress panel.

> This step confirms that each answer is successfully saved before moving to the next question.

### 🎉 Interview Completion

After all questions have been answered and submitted, the system displays a confirmation screen:

- 🎊 A celebratory message appears: **"Interview Completed!"**
- ✅ This indicates that the candidate has successfully finished the entire assessment.
- 🔘 Click **Close Window** to exit the session.










