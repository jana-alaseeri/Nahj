# Nahj
.
> ⚠️ The pipeline uses Google Drive paths (`/content/drive/MyDrive/allam_mcq_project`). Run on Google Colab with Drive mounted. See setup instructions below.

---

## 🚀 How to Run

1. Open `app.ipynb` in Google Colab
2. Set runtime to **T4 GPU** → Runtime > Change runtime type > T4 GPU
3. Run the last cell — the app auto-downloads the fine-tuned adapter from Hugging Face
4. Click the Gradio link that appears
5. Upload a PDF, define your CLOs, and generate your quiz

---

## 🤗 Model on Hugging Face

Fine-tuned LoRA adapter publicly available at:
**[jana-alaseeri/Nahj-mcq-pt1](https://huggingface.co/jana-alaseeri/Nahj-mcq-pt1)**

---

## 📊 Dataset

- 700+ manually collected slide-question-answer triplets
- Covers: Data Structures · Compiler Construction
- Augmented via question rephrasing and cross-CLO negative sampling
- Split: 90% train / 10% validation

---

## 👥 Team

| Role | Name |
|---|---|
| Product Owner | King Abdulaziz University — Deanship of E-Learning |
| Scrum Master & Developer | Jana Al-Aseeri |
| Developer | Noor |
| Developer | Raghad |
| Developer | Sadeem |
| Developer | Jumana |

---

## 📅 Sprint 1 Timeline

| Phase | Tasks | Duration |
|---|---|---|
| Phase 0 | Data Collection & Environment Setup | Apr 27 – 29 |
| Phase 1 | Data Cleaning, EDA, Preprocessing, Augmentation, Preparation | Apr 30 – May 10 |
| Phase 2 | Transfer Learning & Fine-Tuning | May 13 – 22 |
| Phase 3 | RAG Pipeline & Evaluation | May 23 – Jun 1 |
| Phase 4 | Gradio Deployment | Jun 2 – 4 |

**Total: Ideation to live deployment in under 6 weeks.**

---

## 📄 License

This project was developed as part of an academic initiative at King Abdulaziz University.
