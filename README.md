Project Title: Cloud-Native AI Resume Analyzer & Job Matcher

Description:
A Flask web application that analyzes resumes using NLP and matches them to job descriptions based on semantic similarity.

Tech Stack:
Flask, BERT, spaCy, AWS EC2, MongoDB

Features:

Semantic similarity scoring using BERT embeddings

Async API for resume submission and job matching

Web interface for uploading resumes and viewing matched jobs

Installation:

git clone <repo-link>
cd resume-analyzer
pip install -r requirements.txt


Usage:

python app.py
# Visit http://localhost:5000


Future Work:

Include multi-language resume parsing

Add skill gap analysis and job recommendation ranking
