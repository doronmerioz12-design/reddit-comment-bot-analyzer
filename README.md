# CommentAnalyzer Package

> **DISCLAIMER:** Proof-of-concept hackathon module. Demonstration and educational use only.

## 📌 Module Overview

`CommentAnalyzer` is the core Python NLP and heuristic engine for the Reddit Comment & Credibility Analyzer system.

### Key Components:
- **`orchestrator.py`**: Main coordinator combining account profiling, bot detection, and sentiment rules.
- **`analyzers/account_profiler.py`**: Account age, karma, and posting gap analyzer.
- **`analyzers/bot_network_analyzer.py`**: Astroturfing and similarity analysis.
- **`analyzers/suspicious_words.py`**: Debunking keyword detection and LLM interface.
- **`models/`**: Data models for comments, user histories, and scoring outputs.

## 📦 Package Additional Files
- **`README.md`**: Package documentation.
- **`.env.example`**: Environment variable template.
