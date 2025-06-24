# 🎓 AI Course Generator from Videos — SensAI'25 Hackathon

⏱️ **30 Hours. Zero Sleep. Just Code, Coffee & Curiosity.**

This project was built by **Team CODE CRAFTERS** during **SensAI'25**, a 30-hour hackathon hosted by HyperVerge and our college. Out of 66 teams, 36 were shortlisted — and we were proud to tackle a challenging real-world problem for course creators.

---

## 🧩 **Problem Statement**

> **"AI Assistant for Course Creators — Automatically Generate Courses from Videos."**

Our goal: convert lengthy educational videos into structured, engaging online courses — complete with:
- 📜 Transcripts
- 📚 Modules & Lessons
- ✅ Quizzes

---

## 🚀 **What We Built**

✅ Upload `.mp4` videos or YouTube links  
✅ Audio transcription pipeline using **OpenAI Whisper** (tuned for best speed-quality)  
✅ NLP preprocessing to extract meaningful content  
✅ Auto-create course structure: **Course → Modules → Lessons → Quizzes**

---

## 🖼️ **Going Beyond Audio: Visual Processing**

Videos show more than they say. We:
- Implemented **Scene Segmentation** to extract keyframes  
- Analyzed keyframes with **GPT-4 Turbo Vision** to summarize slides, titles, and code snippets  
- Combined audio + visual summaries into rich, multimodal course content

Tested with real videos — our system correctly detected keyframes and generated concise summaries.

---

## ⚡ **Integrated into SensAI Platform**

All pipelines were plugged into the SensAI platform for a seamless experience.

Though we didn’t advance to the final rounds, we:
- Debugged backend glitches
- Swapped models on the fly
- Pulled an all-nighter together!

A truly rewarding hackathon experience for the whole team.

---

## 🙌 **Credits**

**Team CODE CRAFTERS**  
- Hemadiksitha K M  
- Varun Shankar G

Big thanks to HyperVerge, our college, placement faculty, and student coordinators for the opportunity!

---

## 📁 **Folder Structure**

AI-course-generator/
├── sensai-ai.zip # Backend pipeline
├── sensai-frontend.zip # Frontend UI
├── .gitignore
├── README.md