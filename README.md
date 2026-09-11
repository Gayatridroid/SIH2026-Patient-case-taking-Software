# AI AYUCASE AI – Patient Case-Taking Software

An AI-powered clinical case-taking platform designed to streamline Outpatient Department (OPD) workflows across India. The system conversationally captures patient medical history in multiple Indic languages, digitizes physical records, and generates structured clinical summaries linked with ABHA standards before the doctor’s consultation.

---

## 📌 Project Overview
* **Hackathon:** Smart India Hackathon 2026
* **Problem Statement ID:** 26047
* **Problem Statement Title:** Patient Case-Taking Software[cite: 1]
* **Theme:** Smart Automation[cite: 1]
* **Category:** Software[cite: 1]
* **Team Name:** Bharat Innovators (Team ID: 63)[cite: 1]

---

## 🚨 The Problem
* Indian OPD doctors get only **2–5 minutes per patient**, leaving minimal time for thorough clinical history-taking—which dictates 70–80% of accurate diagnoses[cite: 1].
* Patients arrive with scattered, unorganized paper records that waste critical consultation minutes[cite: 1].
* Language barriers and complex medical terminology hinder quick, accurate triage[cite: 1].

---

## 💡 The Solution
**AI AYUCASE AI** automates patient intake via conversational voice and text AI[cite: 1]:
* **Multilingual Voice Intake:** Supports 10+ Indic languages (Hindi, Tamil, Telugu, Bengali, Marathi, etc.) for intuitive voice case-taking[cite: 1].
* **Document Digitization:** Extracts clinical entities and past medical history from uploaded prescriptions and lab reports using OCR[cite: 1].
* **Structured Clinical Summaries:** Converts unorganized patient narratives into structured clinical timelines and Electronic Health Record (EHR) notes[cite: 1].
* **Doctor-in-the-Loop:** Doctors review, edit, and approve auto-generated summaries in under 30 seconds before committing them to the patient's record[cite: 1].
* **OPD Efficiency:** Reduces doctor consultation preparation time by over **60%**[cite: 1].

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (PWA-ready for OPD kiosks and mobile devices)[cite: 1]
* **Backend:** Python (Flask Framework)[cite: 1]
* **Database:** PostgreSQL with native `JSONB` for dynamic clinical intake schemas[cite: 1]
* **AI & NLP Engine:** Speech-to-Text (Indic speech models), NLP entity extraction (UMLS/SNOMED-aligned), and OCR[cite: 1]
* **Security:** End-to-end data encryption (AES-256 / TLS 1.3) with Role-Based Access Control (RBAC)[cite: 1]

---

## 🔄 System Workflow

[Patient Voice/Text Input] ──► [Speech-to-Text] ──► [NLP Intake Engine]
                                                           │
[Past Prescription / Slip] ──► [OCR Engine] ───────────────┘
                                                           │
                                                           ▼    
                                                [PostgreSQL JSONB Storage]
                                                           │
                                                           ▼
                                               [Doctor Review Dashboard]
                                                           │
                                              (Doctor Edit & Verification)
                                                           │
                                                           ▼
                                               [Standardized EHR / ABHA]  
