title: AI Medical Diagnostic Chatbot – viswam.ai Report
emoji: 🧠
colorFrom: indigo
colorTo: blue
sdk: Streamlit
app_file: app.py
pinned: false
---

# 🧠 AI Medical Diagnosis Assistant – viswam.ai Open-Source Challenge Report


## Team Name: AI Medivision

## Team Members:

Member 1: [manibyra] – Frontend & user Growth

Member 2: [gorileshailaja] – AI Integration & Documentation

Member 3: [pooja25] – Testing & Optimization

Member 4: [akhilbudige] – Streamlit Integration & Community Engagement

Member 5: [nayan_2069] – Backend & Optimization

# Application Overview

## Project Title: AI Medical Diagnosis Assistant
https://huggingface.co/spaces/Pooja-2025/ai-medical-diagnosis-assistant

### Problem Statement: 
Many individuals in rural or underserved areas lack access to quick and basic medical advice. Our AI Medical Diagnosis Assistant offers a simple interface where users can describe their symptoms and receive instant, preliminary medical guidance in their local language.


### Minimum Viable Product (MVP):
A lightweight, multilingual Streamlit-based chatbot that accepts user symptoms via text input and provides possible diagnoses or suggestions, using an offline-first, open-source AI backend.

### Offline-First Strategy:
The app uses local caching, minimized external calls, and lightweight ML models to function in low-bandwidth environments.

# 🚀 Features

- 🧾 Multi-turn symptom collection and questioning
- 🤖 Dynamic question generation
- ✅ Smart condition detection (Suspected / Possible)
- 📁 Session tracking and input logging
- 🗣️ Voice input support (planned)
- 🧑‍⚕️ Suggested condition with basic medicine/doctors (planned)
- 🎨 User-friendly frontend 
- 🤖 Translation of 5 different Langugaes i.e Telugu , Hindi , English , Tamil, Kannada , Bangali

# AI Integration Details

- Utilized an open-source NLP model for symptom-to-diagnosis matching.

- Integrated a rule-based engine and Infermedica-like dataset for safe, general-purpose medical predictions.

- All AI components are lightweight and run client-side or through efficient backend APIs to ensure offline compatibility.

## 📂 Project Structure


├── app.py                 
├── templates/
│   └── index.html 
│   ├── css/
│   └── js/
├── data/
│   └── conditions.json    
├── logs/
│   └── user_logs.csv    
├── requirements.txt
├── Dockerfile
├── .huggingface.yml
├── README.md
├── REPORT.md
├── CONTRIBUTING.md
├── CHANGELOG.md
└── LICENSE

# Technical Architecture & Development

Frontend: Streamlit UI
Backend: Python + rule-based & NLP diagnosis logic
Deployment: Hugging Face Spaces with Docker

#### Key Features:

- Multilingual symptom input support
- Basic suggestions and health triaging
- Offline-first design using session cache and model preloading

# User Testing & Feedback

### FeedBack Link:
https://docs.google.com/spreadsheets/d/15oDv5QK3g_YceaVuPrrtPSVuJW07ZQVRPpzMj2PXnvk/edit?usp=sharing

### Methodology

- 10 testers from local communities and student circles

- Tasks: Enter symptoms, evaluate diagnosis, use in native language

- Feedback collected via Google Forms and in-app feedback button

- Insights & Iterations

- Added simplified language toggle based on tester confusion

- Improved diagnosis clarity and removed medical jargon

- Enhanced caching after reports of slow load in low network areas

# Project Lifecycle & Roadmap

## Week 1: Rapid Development Sprint

Set up repo & Streamlit scaffold

Implemented core diagnosis logic

Integrated offline AI model and multilingual UI

Deployed MVP on Hugging Face Spaces

### Deliverables:
Functional MVP
Offline-first optimization

## Week 2: Beta Testing & Iteration Cycle
### Test Recruitment:

Local students

Telegram health groups

### Feedback Collection:

In-app form

Interviews via phone (for poor internet testers)

### Iterations:

Bug fixes for local language rendering

Streamlined question flow to reduce drop-off

## Weeks 3-4: User Acquisition & Corpus Growth Campaign

### Target Audience:

-> Students in Tier-2 cities
-> Women in health WhatsApp groups
-> Farmers & elderly with limited access to    clinics

### Growth Strategy:

Posters in local languages

Memes on health topics

Demo sessions in colleges

### Execution:

Shared app in 20+ local groups

Created 5 social media reels

### Metrics:

150+ unique users

470+ symptom submissions

4.6/5 avg. user satisfaction (survey)

D. Post-Internship Vision & Sustainability Plan

### Major Future Features:

Voice input & speech recognition

Integration with Swasthya Bharat health APIs

Visual symptom uploader

### Community Building:

Local health ambassadors

Campus promoters in health colleges

### Demo Video links
https://drive.google.com/file/d/1qw9dKuiscMjVuvTJX4KCHT9jBjH1zwFX/view?usp=sharing

### Scaling Data Collection:

Incentivized user sharing

Campaigns targeting vernacular influencers

### Sustainability:

Open-source contributor model

NGO and health startup collaborations

# Submission Details

- **Challenge**: viswam.ai 4-week Open Source AI Challenge
- **Domain**: Healthcare / Medical AI
- **App**: Streamlit web application
- **Deployed on**: Hugging Face Spaces using Docker in the streamlit template
- **GitLab Repo**: https://code.swecha.org/Manibyra/ai-medical-bot.git
