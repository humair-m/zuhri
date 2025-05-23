# Zuhri — Urdu G2P Dataset

**Zuhri** is a comprehensive and manually verified Urdu **Grapheme-to-Phoneme (G2P)** dataset. It is designed to aid research and development in areas such as speech synthesis, pronunciation modeling, and computational linguistics, specifically for the Urdu language.

This dataset provides accurate phoneme transcriptions and IPA representations, making it ideal for use in building high-quality TTS (Text-to-Speech), ASR (Automatic Speech Recognition), and other phonetics-related systems.

---

## 🔤 What is G2P?

Grapheme-to-Phoneme (G2P) conversion is the task of translating written text (graphemes) into spoken sounds (phonemes). G2P is crucial for generating natural-sounding speech from text and for correct pronunciation modeling in voice-driven technologies.

---

## 📁 Dataset Contents

The dataset is stored in the `data/` directory as a CSV file. Each row in the file contains the following five columns:

```
Word, Phoneme Sequence (space-separated), IPA Transcription, Verified (True/False), Frequency Rank
```

### 📋 Sample Data Preview

| Word        | Phonemes               | IPA               | Verified | Rank |
|-------------|------------------------|--------------------|----------|------|
| عائشہ       | ʕ aː ɪ ʃ ə            | /ʕaːˈɪʃə/         | True     | 1    |
| عطیہ        | ʕ ʈ iː j ə            | /ʕʈiːˈjə/         | True     | 1    |
| طور         | t̪ uː r                | /t̪uːr/            | True     | 1    |
| اردو        | ʊ r d uː              | /ʊrˈduː/           | True     | 1    |
| اللہ        | ɑ l l aː h            | /ɐlˈlɑːh/          | True     | 1    |

---

## 🎯 Applications

This dataset is useful for:

- Urdu Text-to-Speech (TTS) systems
- Automatic Speech Recognition (ASR)
- Phonetic alignment and transcription
- Linguistic and phonological research
- Speech technology applications in Urdu

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/zuhri.git
cd zuhri
```

### 2. Load the Dataset in Python

```python
import pandas as pd

# Load the Urdu G2P dataset
df = pd.read_csv("data/urdu_g2p.csv")

# Display the first few rows
print(df.head())
```

---

## 📚 Citation

If you use this dataset in your research or project, please cite it as:
```citation

**Author**: Humair Munir  
**Title**: URDU G2P  
**License**: Apache 2.0  
**Email**: humairmunirawan@gmail.com```

---

## 📜 License

This dataset is released under the **Apache License 2.0**. You are free to use, modify, and distribute it under the terms of this license. For full details, refer to the `LICENSE` file included in the repository.

---

## 🤝 Contributing

We welcome contributions from the community! You can:

- Suggest corrections or improvements in phoneme alignments
- Add more verified Urdu words
- Extend the dataset for regional dialects
- Submit pull requests for related G2P utilities or training scripts

Please open an issue to discuss your ideas before submitting a PR.

---

## 📬 Contact

For questions, collaborations, or support, feel free to reach out:

📧 **Email**: humairmunirawan@gmail.com

---

## 🧠 Acknowledgment

This dataset is part of an effort to improve linguistic tools and speech resources for underrepresented languages like Urdu. Special thanks to all contributors and the open-source community for support and feedback.

---
