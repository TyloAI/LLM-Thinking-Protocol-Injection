# The Performance of "Thought": An Exploratory Study on LLM Visualized Reasoning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Preprint-blue.svg)]()
[![Field](https://img.shields.io/badge/Field-AI%20Safety-red.svg)]()

> **Abstract:** Is the "thinking process" of modern LLMs a faithful log of reasoning, or a manipulable performance? This study introduces **"Protocol Injection"** to probe the authenticity of visualized reasoning in DeepSeek, Gemini, Claude, and ChatGPT. We uncover the **"Safety Arbitration Chamber"** mechanism and the risks of **"False Transparency"**.

## 📥 Download Paper
[**📄 Read the Full Paper (PDF)**](./Paper.pdf)

---

## 🚀 Key Findings (Highlights)

Our research (N=50 automated probes) reveals a "Functional Spectrum" of visualized reasoning:

1.  **Decoupling:** The "Thought" and "Answer" are logically separable.
2.  **Safety Arbitration Chamber:** In models like Claude, the thinking block is hijacked by safety layers for real-time censorship.
3.  **False Transparency:** We demonstrate a novel attack vector where "trusted" thinking processes can be manipulated to carry hidden payloads.

## 🛠️ Methodology: Protocol Injection

We define "Protocol Injection" not as a jailbreak, but as a diagnostic probe. By injecting conflicting meta-instructions, we force the model to reveal its internal hierarchy between "Performance" and "Safety".

*(Code and automated testing scripts coming soon)*

## 📖 Citation

If you find this research useful, please cite it as:

```bibtex
@misc{wu2025performance,
  title={The Performance of "Thought": An Exploratory Study on the Authenticity, Manipulability, and "False Transparency" Risks of LLM Visualized Reasoning},
  author={Wu, Yihu},
  year={2025},
  howpublished={GitHub Repository},
  url={[https://github.com/YOUR_GITHUB_USERNAME/LLM-Thinking-Protocol-Injection](https://github.com/YOUR_GITHUB_USERNAME/LLM-Thinking-Protocol-Injection)}
}
```

## 📬 Contact
TyloAI Research [https://www.tyloai.com]
