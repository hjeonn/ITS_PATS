# ITS_PATS
PATS: Pedagogically Adaptive Tutoring System

🧠 Introduction
The Pedagogically Adaptive Tutoring System (PATS) is designed to generate adaptive tutoring responses by integrating student traits—such as personality dimensions and mastery levels—into the response generation process. This system leverages state-of-the-art language models to deliver personalized feedback and support during tutoring sessions.

The system evaluates its performance using established linguistic metrics, including BLEU, BERTScore, and DialogRPT, across datasets like CIMA and TSCC.

PATS_project/
    ├── main.py                        # Main execution script
    ├── model_loader.py                # Model loading and initialization
    ├── trait_classifier.py            # Student trait classification
    ├── strategy_selector.py           # Teaching strategy selection
    ├── response_generator.py          # Response generation with LLMs
    ├── evaluator.py                   # Evaluation of generated responses
    ├── utils.py                       # Utility functions (saving, loading)
    ├── config.py                      # Configuration settings
    └── README.md                      # Project documentation


