# AI-promt-toolkit
A prompt engineering toolkit demonstrating design, testing, and optimization techniques on LLMs – achieves 20-30% accuracy improvement in e-commerce sentiment analysis using Groq's Llama-3.3-70B.
# AI Prompt Toolkit – Prompt Engineering Demo

🚀 **Live Demo of Prompt Design, Testing & Optimization** 🚀

This repository showcases practical **prompt engineering** skills for Large Language Models (LLMs). Built as a lightweight Python toolkit, it demonstrates how iterative prompt refinement can significantly improve model performance – without changing the underlying LLM.

### Key Highlights
- **Real-World Task**: Sentiment classification on e-commerce customer reviews (ties to business analytics & NLP).
- **Base Zero-Shot Prompt**: ~80% accuracy.
- **Optimized Prompt** (with role-playing + chain-of-thought): **95–100% accuracy** → **15–30% improvement**.
- **Techniques Used**:
  - Role assignment ("Act as an expert sentiment analyst")
  - Chain-of-Thought reasoning
  - Iterative testing & evaluation (accuracy + F1-score via scikit-learn)
- **Tech Stack**:
  - Groq API (ultra-fast inference with latest **llama-3.3-70b-versatile** model – 2025 current)
  - Python, pandas, scikit-learn
- **Why This Matters**: Mirrors real prompt engineering workflows – design clear prompts, test on data, optimize iteratively, and measure impact quantitatively.

Inspired by my **Tata iQ Virtual Internship in Prompt Engineering & Generative AI** (Forage) and hands-on projects like GenAI-Driven Insight Generator.

Perfect for interviews, learning, or building reliable AI solutions!

### Quick Start
1. Get free Groq API key: https://console.groq.com/keys
2. `pip install groq scikit-learn pandas`
3. Run `prompt_optimizer.py` → See live improvement!

Author: Sahil Subhash Khade  
📧 sahilkhade0707@gmail.com |

⭐ Star if you find it useful for your prompt engineering journey!
