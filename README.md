# LLM Classification Finetuning - Kaggle Competition

Proyek ini adalah partisipasi saya dalam kompetisi Kaggle untuk memprediksi preferensi manusia terhadap jawaban dari dua Large Language Model (LLM) yang berbeda.

## 🚀 Overview
Tujuannya adalah membangun classifier yang bisa menentukan apakah jawaban dari **Model A** lebih baik, **Model B** lebih baik, atau **Tie (Seri)**.

## 🛠️ Pendekatan (Strategy)
Untuk tahap awal (Baseline), saya menggunakan strategi **Word Count Heuristic**:
- Menganalisis panjang teks jawaban (response length).
- Memberikan probabilitas lebih tinggi pada jawaban yang lebih detail/panjang, karena secara statistik manusia cenderung lebih menyukai jawaban yang komprehensif.

## 📊 Dataset
Dataset berasal dari LMSYS - Chatbot Arena, berisi ribuan percakapan manusia dengan LLM (GPT-4, Claude, Llama, dll).
*Catatan: File data tidak diunggah ke repositori ini karena ukurannya yang besar (>100MB).*

## 📈 Progres
- [x] Data Cleaning & Preprocessing
- [x] Baseline Submission (Word Count Strategy)
- [ ] Next: Fine-tuning menggunakan Model Transformers (BERT/RoBERTa)
