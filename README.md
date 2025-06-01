# The Persuasive Memescape: Understanding Effectiveness and Societal Implications of Internet Memes

This dataset is developed for understanding **persuasiveness**, **persuasive polarity**, and **linguistic rhetorical devices** in internet memes. It supports three tasks across different levels of semantic and rhetorical analysis.

---

## 📁 Dataset Folder Structure
- **Image Folder Name**: Kindly reach us at AI-NLP-ML Lab, IIT Patna, India  or Gitanjali Kumari, E-mail: gitanjali_2021cs03@iitp.ac.in
- **Dataset File**: `Persuasion _train_set.csv`, `Persuasion _test_set.csv`

## 🧠 Tasks Overview

### **Task 1: Binary Persuasiveness Classification**
- **Objective**: Classify memes as either:
  - `Persuasive`
  - `Non-persuasive`
- **Train Distribution**: Persuasive (4800), Non-persuasive (2818)
- **Test Distribution**: Persuasive (1200), Non-persuasive (717)

---

### **Task 2: Fine-Grained Persuasive Polarity**
- **Objective**: Assign one of 5 polarity levels to persuasive memes:
  - `Positively persuasive`
  - `Slightly Positively persuasive`
  - `Neutral`
  - `Slightly Negatively persuasive`
  - `Negatively persuasive`
- **Train Distribution**:
  - Positively persuasive: 1982
  - Slightly Positively persuasive: 99
  - Neutral: 75
  - Slightly Negatively persuasive: 978
  - Negatively persuasive: 1261
- **Test Distribution**:
  - Positively persuasive: 483
  - Slightly Positively persuasive: 31
  - Neutral: 45
  - Slightly Negatively persuasive: 226
  - Negatively persuasive: 340

---

### **Task 3: Rhetorical Device Detection**
- **Objective**: Detect rhetorical techniques used in persuasive memes.
- **Categories**:
  - Metaphors
  - Hyperboles
  - Personification
  - Alliteration
  - Irony
  - Analogies
  - Puns and Wordplay
  - Satire
  - Invective
- **Train Counts**:
  - Metaphors: 29
  - Hyperboles: 466
  - Personification: 122
  - Alliteration: 42
  - Irony: 1238
  - Analogies: 275
  - Puns_and_wordplay: 263
  - Satire: 1268
  - Invective: 324
- **Test Counts**:
  - Metaphors: 5
  - Hyperboles: 118
  - Personification: 21
  - Alliteration: 7
  - Irony: 297
  - Analogies: 72
  - Puns_and_wordplay: 73
  - Satire: 306
  - Invective: 83

---

## 💻 Associated Code
- File: `persuasion_model.ipynb`  

---

## 📜 Citation
Kumari, G., Adak, C., Ekbal, A. (2024). Mu2STS: A Multitask Multimodal Sarcasm-Humor-Differential Teacher-Student Model for Sarcastic Meme Detection. In: Goharian, N., et al. Advances in Information Retrieval. ECIR 2024. Lecture Notes in Computer Science, vol 14610. Springer, Cham. https://doi.org/10.1007/978-3-031-56063-7_2
---
