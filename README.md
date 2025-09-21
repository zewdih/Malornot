# Malornot 🛡️

**Malornot** is an AI security agent that intercepts user queries and dynamically applies protections — malicious input detection, PII scrubbing, and anomaly detection — before passing them to a Large Language Model (LLM).  

Built in just **6 hours** at the MCP AI Agents Hackathon (Sep 2025).  

---

## 🚀 Inspiration
As enterprises adopt LLMs, they’re forced to juggle a patchwork of tools for moderation, compliance, and threat detection. These tools are powerful but rarely “talk” to each other, leaving gaps in safety.  
Malornot was designed to solve this: an orchestration agent that decides in real-time which protections to run, creating a smarter, safer security layer for LLMs.  

---

## 🔧 What It Does
- Intercepts every user query before it reaches the model  
- Dynamically decides which protections to apply:  
  - 🚫 **Malicious input detection**  
  - 🔒 **PII scrubbing**  
  - ⚠️ **Anomaly detection**  
- Routes inputs through the right security tools and forwards only safe content to the LLM  
- Provides a **flexible orchestration flow** instead of a rigid one-size-fits-all pipeline  

---

## 🏗️ Architecture
User Input → Analyzer → Decision Engine → Protection Tools → LLM
---

## 🛠️ Tech Stack
- **Anthropic Claude** – base LLM  
- **Dify** – orchestration and flow design  
- **LlamaIndex** – structured data routing  
- **Minimax** – API integration  
- **Qodo** – security tooling  

---

## 🎥 Demo
- 🔗 [Live Demo](https://v0-modern-ai-chatbot-interface-tem-seven-xi.vercel.app)  
- 🔗 [Devpost Submission](https://devpost.com/software/malornot)  

---

## 📚 Challenges & Learnings
- Building a **dynamic orchestration agent** instead of a rigid pipeline  
- Balancing **security, speed, and accuracy** within hackathon time limits  
- Rapid collaboration and testing under 6 hours  

---

## 🔮 Future Work
- Add **multimodal protections** (image, audio, video inputs)  
- Create **observability dashboards** to show triggered protections  
- Expand compliance and security coverage  

---

## 👥 Contributors
- **Zewdi Herring** – Agent flow design, orchestration, and demo build  
- Wendi Yin – AI integrations  
- Pulkit Garg – Development & testing  
- [Add teammates here if needed]  

---
