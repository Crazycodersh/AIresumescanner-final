Here’s a GitHub description for your application based on the details you provided:


AI Resume screeing system

This project is a AI Resume screeing system built with Python 3.11, utilizing modern libraries and tools for text processing, machine learning, and web development. The application aims to provide an interactive, scalable, and efficient system for comparing resumes with job descriptions, offering precise match scores based on Natural Language Processing (NLP) and machine learning techniques.

Key Features
	•	Web Interface: Developed with Streamlit to create a clean and interactive frontend for users to upload resumes and job descriptions.
	•	Text Processing: Utilizes NLTK for essential NLP tasks such as tokenization, named entity recognition (NER), and text preprocessing.
	•	Document Parsing: Supports PDF (using PyPDF2) and DOCX (using python-docx) document extraction for easy resume and job description input.
	•	Machine Learning: Implements Scikit-learn for TF-IDF vectorization, cosine similarity calculations, and resume-job description matching.
	•	Efficient Processing: Uses NumPy for optimized numerical operations and data processing.
	•	Containerization & Deployment: The application is containerized and deployed on Replit, making it easily accessible via a web browser.
	•	Professional UI: Custom CSS styling ensures a modern, user-friendly interface for seamless user experience.

Architecture
	•	Modular Design: The application follows a modular architecture with distinct components for:
	•	Document Processing
	•	NLP Analysis
	•	Machine Learning (TF-IDF and Cosine Similarity)
	•	Resume Ranking and Scoring
	•	Scalable and Maintainable: Designed with maintainability in mind, making it easy to update and extend with new features.

Installation

To run this project locally:

1.Clone the repository:
git remote add origin https://github.com/Crazycodersh/AIresumescanner-final.git
git branch -M main
git push -u origin main


2.Create and activate a virtual environment:
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3.Install the required dependencies:
pip install -r requirements.txt


4.Run the application:
streamlit run app.py



Technologies Used
	•	Python 3.11
	•	Streamlit
	•	NLTK
	•	PyPDF2
	•	python-docx
	•	Scikit-learn
	•	NumPy
	•	Custom CSS
	•	Docker (for containerization)

