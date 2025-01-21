# 🚀 Agents for Smarter Job Hunting 🚀

Welcome to the **Job Hunter Agents** repository! This project leverages the power of Large Language Models (LLMs) and APIs to streamline the job-hunting process, making it smarter and more efficient. Designed for individuals looking to save time while exploring opportunities, this system combines intelligent job searching with interview preparation.

---

## 🌟 Features
This project uses two agents and CrewAI framework to manage them
1. **Job Search Agent**:
   - Utilizes the **Adzuna API** to find job opportunities based on your desired role and location.
   - Fetches key job details, including title, company, location, description, and job URL.
   - Outputs concise and relevant results for up to five job openings to maintain speed and efficiency.

2. **Interview Preparation Agent**:
   - Generates tailored interview questions based on job roles and descriptions.
   - Focuses on the skills and requirements needed for the positions found.

3. **Seamless Integration**:
   - Built on the powerful **LLaMA 3.1 70B model** from GroqCloud API for enhanced language understanding.
   - Modular design using CrewAI to manage agents and tasks.

---

## 🛠️ How It Works
1. **Search for Jobs**:
   - The Job Search Agent uses the Adzuna API to find jobs matching your criteria.
   - Example input: `{ "role": "Data Scientist", "location": "New York", "num_results": 5 }`.
   - The results are saved to a text file (`job_info.txt`).

2. **Prepare for Interviews**:
   - The Interview Preparation Agent analyzes job descriptions to create tailored questions.
   - Outputs are saved to another text file (`interview_questions.txt`).

3. **Execution**:
   - Run both agents through a CrewAI pipeline to automate the end-to-end process.

---

## 🚀 Getting Started
### Prerequisites
- Python 3.9+
- CrewAI library
- GroqCloud and Adzuna API keys

## 🛠️ Future Enhancements
- **Resume Matching**: Upload your resume for personalized job recommendations.
- **Skill Insights**: Get suggestions to improve your resume based on job requirements.
- **Broader API Integration**: Support for additional job search APIs.
- **Interactive Web Interface**: Build a front-end to make the process user-friendly.

---

## 🌐 Resources
- [GroqCloud API](https://lnkd.in/e2b3PStv) – Free API key for LLaMA models.
- [Adzuna API](https://lnkd.in/eVbMDfuG) – Free job search API.
- [Google Colab Notebook](https://lnkd.in/ejpgP9Ti) – Explore and experiment with the project.

