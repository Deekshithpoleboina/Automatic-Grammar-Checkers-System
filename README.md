# Automatic-Grammar-Checkers-System

**CorrectLy** is an intelligent, NLP-powered spelling and grammar correction tool. It processes raw English text and returns a corrected version with improved grammar, punctuation, and sentence structure. Built entirely in Python, CorrectLy uses a collection of rule-based and statistical algorithms alongside modern NLP libraries to deliver accurate and real-time suggestions.

---

## 🚀 Features

- Accepts raw text or uploaded `.docx` files.
- Provides real-time spelling and grammar corrections.
- Fixes:
  - Verb forms based on sentence tense.
  - Subject–verb and preposition–noun agreement.
  - Sentence structure and article usage.
- Outputs corrected version with:
  - Total number of errors.
  - Type-wise error statistics.
  - Side-by-side comparison table (original vs corrected sentence).

---

## 🧠 NLP Libraries Used

CorrectLy leverages several Python libraries for natural language understanding and correction:

| Library         | Purpose                                                                 |
|----------------|-------------------------------------------------------------------------|
| **SpaCy**       | Sentence splitting, POS tagging, dependency parsing                     |
| **NLTK**        | Tokenization, corpus handling, sentence tree visualization              |
| **language_tool_python** | Grammar and spelling correction suggestions                         |
| **Pattern**     | Verb conjugation based on person, number, mood, and tense               |
| **SymSpell / Sympound** | Fast spelling correction using dictionary-based distance matching     |
| **NumPy**       | Internal data storage and light numerical calculations                  |

---

## 🧪 Correction Algorithms

CorrectLy applies a sequence of rule-based and data-driven corrections using the above tools:

| Example Correction Type         | Before                                  | After                                   |
|--------------------------------|------------------------------------------|------------------------------------------|
| **Spelling Correction**         | `what are yuo doign in hte collrge`      | `What are you doing in the college?`     |
| **Verb Form Correction**        | `He is play in the garden.`              | `He is playing in the garden.`           |
| **Tense Agreement**             | `Harry has been watched movie.`          | `Harry has been watching a movie.`       |
| **Preposition Correction**      | `The children are sitting on the room.`  | `The children are sitting in the room.`  |
| **Article Usage**              | `I am looking at boy.`                   | `I am looking at the boy.`               |

---

## ⚙️ Getting Started

### 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/CorrectLy.git
   cd CorrectLy
