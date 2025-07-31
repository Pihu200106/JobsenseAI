JobSense-AI: Career Planner Powered by Real Job Data

JobSense-AI is an open-source project designed to help students and professionals make informed, data-driven career decisions. It scrapes real job listings, extracts required skills using NLP, compares them with user skills or resumes, identifies gaps, and provides personalized learning suggestions.


---

Why JobSense-AI?

Many learners struggle to align their skills with current industry demands. JobSense-AI bridges that gap by analyzing real job data and guiding users on how to become job-ready with targeted upskilling recommendations.


---

Features

Scrapes job listings from job platforms using Python

Extracts skills and tools using NLP techniques (spaCy/BERT)

Accepts user skill lists or resumes as input

Performs resume-skill gap analysis

Recommends learning paths based on job trends

Displays insights through interactive dashboards



---

Use Cases

Students planning their careers

Professionals switching domains

Colleges providing data-backed career guidance

Resume benchmarking and personalized feedback



---

Tech Stack

Python

Pandas, NumPy, Scikit-learn

NLP: spaCy, BERT

Web Scraping: BeautifulSoup

Dashboards: Streamlit

Visualization: Plotly, Matplotlib



---

Project Structure

JobSense-AI/
│
├── scraper/             # Scripts to scrape job listings
├── nlp/                 # Skill extraction using NLP
├── analysis/            # Resume-skill gap analysis and suggestions
├── dashboards/          # Streamlit dashboards and visualizations
├── data/                # Sample resumes and job listings
├── requirements.txt     # Python dependencies
└── README.md            # Project overview


---

Getting Started

1. Clone the repository:



git clone https://github.com/yourusername/jobsense-ai.git
cd jobsense-ai

2. Install dependencies:



pip install -r requirements.txt

3. Run the app:



streamlit run dashboards/app.py


---

Contribution Guide

This project was built from scratch to help individuals become truly job-ready using data and AI.

Ways to Contribute:

Improve scraping for more platforms

Add resume parsing support (PDF/DOCX)

Enhance skill gap logic with ML

Build domain-specific dashboards (e.g., Data Science, Marketing)

Help in UI/UX improvements or bug fixes


Start by forking the repo, creating a new branch, and submitting a pull request.


---

License

MIT License. You are free to use, modify, and distribute this project with credit.
