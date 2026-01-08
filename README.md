# ITS-PATS
**PATS: Pedagogically Adaptive Tutoring System**

## 🧠 Overview

The Pedagogically Adaptive Tutoring System (PATS) is a research prototype for generating pedagogically adaptive tutoring responses using large language models.
The system first infers a student’s learning profile from dialogue history and then selects an appropriate teaching strategy using a rule-based pedagogical engine.
This strategy is injected into the language model via prompting, enabling the tutor to respond in a way that better reflects human instructional behavior.

## 📄 Reference

If you use or refer to this work, please cite the corresponding paper (to be released).

## 🔧 Project Structure
```text
.
├── main.py           # Execution entry point and prompt assembly  
├── analysis.py       # Student trait prediction and strategy mapping logic  
├── models.py         # Model loading (API/Local) and inference wrappers  
├── evaluation.py     # Metrics (ROUGE, BERTScore, DialogRPT)  
├── data_loader.py    # Dataset parsing for CIMA and TSCC formats  
├── config.py         # API keys and hyperparameters  
└── utils.py          # Logging and result serialization  


