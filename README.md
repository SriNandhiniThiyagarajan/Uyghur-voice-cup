# Uyghur-voice-cup
Uyghur ASR built using the Wav2Vec2 XLS-R pretrained model — full pipeline including preprocessing, transcription, romanization, CER evaluation, and Kaggle submission generation.

# Uyghur Automatic Speech Recognition (ASR) using Wav2Vec2 XLS-R

This project focuses on building an Automatic Speech Recognition (ASR) pipeline for the Uyghur language using the pretrained Wav2Vec2 XLS-R model from Hugging Face.  
I worked on the full workflow — audio preprocessing, dataset preparation, transcription generation, and post-processing (Arabic → Latin romanization).  
The system was evaluated using Character Error Rate (CER), and the final submission file was generated for Kaggle.

---

## 🛠 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB)
![HuggingFace](https://img.shields.io/badge/HuggingFace-ffcc00)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c)
![Wav2Vec2](https://img.shields.io/badge/Wav2Vec2-XLS--R-blue)
![Kaggle](https://img.shields.io/badge/Kaggle-Submission-success)

---

## 📌 Project Highlights
- Built an end-to-end Uyghur speech-to-text transcription pipeline  
- Preprocessed 23+ hours of speech dataset  
- Used **Wav2Vec2 XLS-R pretrained model** with **CTC decoding**  
- Post-processed outputs with Arabic → Latin romanization  
- Generated `submission.csv` for Kaggle leaderboard

**Leaderboard score:** `0.29064 CER`

---

## 📂 Repository Structure
