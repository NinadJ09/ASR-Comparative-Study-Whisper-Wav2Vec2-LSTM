# A Comparative Evaluation of Deep Learning Models for Automatic Speech Recognition  
### Investigating the Performance, Fairness, and Deployability of Whisper, Wav2Vec 2.0, and LSTM Architectures  
**Author:** Ninad Shrikant Joshi  
**Institution:** CCT College Dublin  
**Degree:** MSc in Data Analytics  
**Submission Date:** September 2025  

---

## 📌 Overview  
This repository contains the full research, code scripts, evaluation results, and documentation for my MSc thesis titled:

**“A Comparative Evaluation of Deep Learning Models for Automatic Speech Recognition: Investigating the Performance, Fairness, and Deployability of Whisper, Wav2Vec 2.0, and LSTM Architectures.”**

The project provides a systematic comparison of modern ASR systems—OpenAI Whisper, Facebook AI Research Wav2Vec 2.0, and a classical LSTM-based ASR model—evaluated under identical conditions across:

- Word & Character Error Rate (WER/CER)
- Fairness across gender & accent subgroups
- Robustness under noise
- Deployability on consumer-grade hardware (M1 Pro)

---

## 📊 Key Contributions  
- 📈 **Benchmark comparison** on LibriSpeech & Common Voice  
- 🎤 **Fairness analysis** (gender & accent)  
- 🔊 **Robustness testing** with SNR-based noise augmentation  
- 🚀 **Deployability & RTF profiling** on CPU-only hardware  
- 🧪 **Jupyter notebooks** for reproducible experiments  
- 📄 Full **MSc Thesis PDF** included  

---

## 🛠️ Tech Stack  
- Python 3.10  
- PyTorch  
- HuggingFace Transformers  
- Torchaudio  
- Librosa  
- NumPy  
- OpenAI Whisper  
- Wav2Vec 2.0 (facebook/wav2vec2-base-960h)  

---

## 📂 Repository Structure  

📁 ASR-Comparative-Study-Whisper-Wav2Vec2-LSTM
│
├── 📄 Thesis.pdf
├── 🗂️ notebooks/
│ ├── whisper_evaluation.ipynb
│ ├── wav2vec2_evaluation.ipynb
│ ├── lstm_baseline.ipynb
│ ├── noise_robustness_tests.ipynb
│ └── fairness_analysis.ipynb
│
├── 🗂️ scripts/
│ ├── preprocess.py
│ ├── infer_whisper.py
│ ├── infer_wav2vec2.py
│ └── noise_augmentation.py
│
├── 🗂️ results/
│ ├── common_voice/
│ ├── librispeech/
│ └── robustness/
│
├── 🗂️ plots/
│ ├── wer_cer_curves.png
│ ├── fairness_comparison.png
│ └── noise_effects.png
│
└── README.md
