# AI-Knowledge-Creativity
AI + Knowledge &amp; Creativity Suite (contains: AI Historian, Myth vs Fact AI, Story Continuator, Music Mood Composer)

# 🧠✨ AI + Knowledge & Creativity Suite

A collection of **AI-powered creative and educational tools**, built entirely with **free and open-source libraries**.  
Each module combines **knowledge retrieval**, **language generation**, and **creative AI** — bringing history, facts, stories, and music to life.

---

## 🚀 Features

### 1️⃣ AI Historian
**Reconstruct historical events** using verified data and text generation.  
📚 Uses: `LangChain`, `Hugging Face Transformers`, `FAISS`, `Wikipedia API`.

🧩 Key Functions:
- Builds an embedding index of real historical sources  
- Generates historical narratives from prompts  
- Cites real Wikipedia sources inline  

---

### 2️⃣ Myth vs Fact AI
**Fact-check myths or conspiracy claims** using Wikipedia search and simple NLP heuristics.  
🔍 Uses: `Wikipedia`, `Regex`, `Python NLP`.

🧩 Key Functions:
- Splits long text into individual claims  
- Searches Wikipedia for related evidence  
- Labels each claim as `likely_true`, `uncertain`, or `error`  

---

### 3️⃣ AI Story Continuator
**Continue your stories in the style of famous authors.**  
🖋️ Uses: `Transformers (GPT-Neo)`, `Torch`, `Streamlit` (optional for UI).

🧩 Key Functions:
- Takes a user’s story start  
- Generates the continuation  
- Optionally adapts style from sample author texts  

---

### 4️⃣ AI Music Mood Composer
**Turn mood or text into original MIDI melodies.**  
🎶 Uses: `Transformers`, `PrettyMIDI`, `Torch`.

🧩 Key Functions:
- Detects sentiment from text  
- Selects musical scale (major/minor)  
- Generates and saves `.mid` melody  

---

## 🛠️ Installation (Colab Recommended)

You can run the entire suite for free on **Google Colab** (no local setup needed).  
Each module includes its own Colab-ready notebook version.

Or install locally:

```bash
git clone https://github.com/MEROO1010/AI-Knowledge-Creativity-Suite.git
cd AI-Knowledge-Creativity-Suite
pip install -r requirements.txt

