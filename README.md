---
title: AEGIS
emoji: 🚀
colorFrom: blue
colorTo: indigo
sdk: streamlit # Or gradio / docker depending on your app
app_file: app.py
pinned: false
---

# AEGIS — Antibiotic Safety Assistant

**Adversarial Engine for Guardian Intelligence in Safe-prescribing**

AEGIS is a multi-agent AI system that analyzes antibiotic prescription safety using a LangGraph pipeline with specialized clinical agents:

- **Appropriateness Agent** — verifies antibiotic indication
- **Contraindication Agent** — checks allergies and drug interactions  
- **Dosing Agent** — computes weight/age-adjusted dosing
- **Safety Gate** — enforces hard clinical safety bounds
- **Counsellor Agent** — generates patient-friendly safety advice

> ⚠️ **Medical Disclaimer**: AEGIS does not replace a licensed medical professional. Always consult a qualified physician or pharmacist.
## Live Demo
Check out the live web application on Hugging Face Spaces here: https://huggingface.co/spaces/BismahJaved/AEGIS
## Environment Variables

Set `GROQ_API_KEY` in your Space's **Settings → Variables and secrets** to enable the live AI pipeline. Without it, the app runs in rule-based simulation mode.
