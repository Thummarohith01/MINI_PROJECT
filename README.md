# CV / Job Description Analytics Dashboard Using Gemini API key

This project is a CV and job description analysis tool that provides insights into the relevance of a resume to a job description. It highlights missing skills, missing keywords, provides recommendations, and suggests relevant courses for improvement. It also offers a visual representation of the relevance score and generates a personalized cover letter.

## Features

1. **Resume Parsing and Analysis**
   - Uploads a resume in `.pdf`, `.txt`, `.doc`, or `.docx` format.
   - Compares the resume with the provided job description.
   - Extracts relevant skills and keywords from both documents.

2. **Relevance Score Calculation**
   - Calculates a relevance score as a percentage (0-100%).
   - Identifies missing skills and keywords in the resume compared to the job description.

3. **Course Recommendations**
   - Provides online course recommendations to improve missing skills.
   - Each course includes platform details, a brief description, difficulty level, estimated time, and a link to the course.

4. **Cover Letter Generation**
   - Generates a professional cover letter based on the resume and job description.
   - Available for candidates with a relevance score of 80% or higher.

5. **Data Visualization**
   - Creates a gauge chart representing the relevance score.
   - Displays missing skills, missing keywords, and recommendations in a user-friendly dashboard.


## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo-url.git
   cd your-repo-url
   Example Output
Relevance Score: 85%
Missing Skills: [‘Python’, ‘Machine Learning’]
Recommendations:
Focus on adding project details for machine learning.
Course Suggestions:
Skill: Python
Course: "Learn Python the Hard Way"
Platform: Coursera
Difficulty: Beginner
Duration: 4 weeks
Cover Letter: Generated based on the resume and job description.
