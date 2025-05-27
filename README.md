# Automatic-Grammar-Checkers-System

# ✅ CorrectLy - The English Text Corrector

**CorrectLy** is an intelligent NLP-powered spelling and grammar correction tool. It accepts raw text or `.docx` files, and returns corrected versions with improved grammar, punctuation, and structure. Built using Python and Flask, CorrectLy leverages a suite of Natural Language Processing libraries to detect and fix errors in real time.

---

## 🌟 Features

- Corrects:
  - Spelling mistakes
  - Verb tense issues
  - Subject–verb agreement
  - Preposition misuse
  - Sentence structure anomalies
- Accepts both raw text and formatted `.docx` files
- Outputs:
  - Corrected version
  - Type-wise error summary
  - Comparison table of original vs corrected sentences

---

## 🧠 Technologies Used

CorrectLy makes extensive use of the following Python NLP libraries:

| Library                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **SpaCy**              | POS tagging, sentence splitting, dependency parsing                         |
| **NLTK**               | Tokenization, tree visualization, corpus handling                           |
| **language_tool_python** | Grammar and punctuation suggestions                                         |
| **Pattern**            | Verb conjugation based on tense and mood                                    |
| **SymSpell / Sympound**| Dictionary-based spelling correction                                         |
| **NumPy**              | Lightweight data handling for metrics and mapping                           |
| **Flask**              | Backend server for the web application                                      |

---

## ⚙️ Correction Algorithms

The following types of corrections are implemented through modular rule-based or hybrid approaches:

| Error Type                  | Example Input                             | Corrected Output                         |
|----------------------------|-------------------------------------------|------------------------------------------|
| **Spelling Correction**     | `what are yuo doign in hte collrge`       | `What are you doing in the college?`     |
| **Verb Tense Correction**   | `He is play in the garden.`               | `He is playing in the garden.`           |
| **Verb Agreement**          | `Harry has been watched movie.`           | `Harry has been watching a movie.`       |
| **Preposition Correction**  | `The children are sitting on the room.`   | `The children are sitting in the room.`  |
| **Article Usage**           | `I am looking at boy.`                    | `I am looking at the boy.`               |

---

## 🚀 Getting Started

### 📦 Installation

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/CorrectLy.git
cd CorrectLy
