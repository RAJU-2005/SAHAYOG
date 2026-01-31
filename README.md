# 🌾 SAHAYOG  
### A Fair, Voice-First Employment Access System for Rural India

> **Hackathon Project | Team CodeX**  
> *Fair work. Simple access. Human dignity.*

---

## 📌 Problem Statement

India spends billions of rupees on rural employment schemes such as **MGNREGA** and the proposed **VB–G RAM G Act**, which legally guarantee wage employment to rural households.  
Despite strong policy intent, the system fails on the ground.

### Key Failures
1. **Bias & Corruption**  
   Job allocation is often controlled by local middlemen instead of being based on real need.

2. **The Digital Wall**  
   Most rural workers cannot read, do not own smartphones, and lack stable internet access.

3. **The Dead-End Trap**  
   Workers perform the same manual jobs for years with no skill growth, income mobility, or hope.

---

## 🎯 Project Goal

Design a system that:
- Connects rural workers to government jobs **without middlemen**
- Works **without reading or smartphones**
- Ensures **fair, explainable, and auditable job allocation**
- Treats workers as humans, not records

---

## 🧠 Solution Overview

**SAHAYOG** is a modular system built around three core pillars:

---

## 1️⃣ Fairness Engine (Fixing Allocation)

An automated, rule-based engine that assigns jobs **based on need and policy rules**, not influence.

### Features
- Priority scoring using:
  - Household income
  - Number of dependents
  - Days since last job
  - Widow / single-parent status
  - Disability and vulnerability flags
- Prevents duplicate or illegal job card usage
- Generates a **Proof of Fairness Log** explaining:
  - Why Person A got work
  - Why Person B did not

> Every decision is auditable and explainable.

---

## 2️⃣ Voice-First Interface (Fixing Access)

Built for **non-literate users with basic phones**.

### How It Works
- Worker places a phone call (IVR)
- Asks in local language:  
  *“Is there work for me this week?”*
- Receives an **audio response**, not text

### Designed for Rural Constraints
- Works on 2G / low bandwidth
- No smartphone or app required
- Supports Indian languages (Kannada, Hindi, etc.)

---

## 3️⃣ Growth & Hope Tracker (Fixing Stagnation)

Moves workers beyond survival-only labor.

### Capabilities
- Tracks work history and repetition
- Detects skill stagnation
- Recommends free government upskilling programs
- Flags high-stress households based on:
  - Repeated payment delays
  - Drop in attendance
  - Frequent complaints

> Enables timely human intervention and restores dignity.

---

## 🏗️ System Architecture (High Level)

Worker (Basic Phone)
↓
Voice Call (IVR)
↓
Voice Processing Layer
↓
Fairness Engine
↓
Allocation + Fairness Log
↓
Audio Response to Worker

---

## 📊 Data Philosophy

This system works with **imperfect and incomplete data**, reflecting real-world public systems.

For every data field, we ask:
- Why is this data needed?
- What real-world condition does it represent?
- What bias arises if it is missing or misused?

### Example Data Fields
- Job Card ID  
- Household Income  
- Number of Dependents  
- Days Worked  
- Days Since Last Job  
- Vulnerability Indicators  

---

## ⚖️ Explainability & Accountability

- No black-box AI
- Rule-based, deterministic decisions
- All allocations produce a readable fairness log
- Decisions can be reviewed by:
  - Workers
  - Officials
  - Social auditors

---

## 🌍 Impact

### Target Beneficiaries
- Widows and single-earner families
- Elderly workers
- Zero-income rural households

### System-Level Impact
- Reduces corruption incentives
- Improves trust in government schemes
- Supports mental well-being
- Encourages skill mobility and long-term growth

---

## 🔮 Future Scope

- Add more fairness rules as policies evolve
- Expand language support
- Enable skill training enrollment via voice
- Apply system to other welfare schemes
- Detect rule drift and exclusion patterns

---

## 🧪 Project Status

- Fairness logic designed ✅  
- Voice-first flow prototyped ✅  
- Realistic datasets simulated ✅  
- Pilot-scale deployment ready 🚧  

---

## 🤝 Team

**Team Name:** CodeX  
**Project:** SAHAYOG  
**Hackathon:** Vidyashilp University – Overnight Hackathon  

---

## 📜 License

This project is built for **social good and public systems innovation**.  
Open for academic, research, and non-commercial use.
