# 🤖 Generative AI Experiments

<p align="center">
  Exploring the power of Generative AI with Python and Hugging Face.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" alt="Python"/>
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-orange?logo=googlecolab" alt="Google Colab"/>
  <img src="https://img.shields.io/badge/AI-Generative%20AI-purple" alt="Generative AI"/>
  <img src="https://img.shields.io/badge/Status-Learning%20Project-green" alt="Learning Project"/>
</p>

---

## 📌 About the Project

Welcome to **Generative AI Experiments**! 🚀

This repository contains three practical experiments that demonstrate how AI can generate audio, write code, and predict missing words using pretrained models.

## 📚 Table of Contents

- [🎯 Objectives](#-objectives)
- [🧪 Experiments](#-experiments)
- [🛠️ Technologies Used](#️-technologies-used)
- [⚙️ Installation](#️-installation)
- [▶️ How to Run](#️-how-to-run)
- [📖 Learning Outcomes](#-learning-outcomes)

## 🎯 Objectives

- 🔊 Convert text into speech.
- 💻 Generate code from natural-language prompts.
- 📝 Predict missing words using a pretrained Transformer.
- 🧠 Understand practical applications of Generative AI.

## 🧪 Experiments

<details>
<summary><strong>🔊 Experiment 1: Audio Generation Using gTTS</strong></summary>

### Description
Converts user-entered text into speech using Google Text-to-Speech.

**Libraries:** `gTTS`, `IPython`

**Workflow:**

User Input → Text-to-Speech Conversion → MP3 File → Audio Playback

**Key concepts:**
- Text-to-Speech (TTS)
- Audio file generation
- English speech synthesis

</details>

<details>
<summary><strong>💻 Experiment 2: Code Generation Using Salesforce CodeGen</strong></summary>

### Description
Generates programming code from a natural-language prompt using the pretrained `Salesforce/codegen-350M-mono` model.

**Library:** `transformers`

**Workflow:**

Code Prompt → CodeGen Model → Generated Code

**Key concepts:**
- Prompt engineering
- Pretrained language models
- AI-assisted programming

**Note:** Always test generated code before using it.

</details>

<details>
<summary><strong>📝 Experiment 3: Fill-Mask Text Prediction</strong></summary>

### Description
Predicts possible missing words in a sentence using a pretrained Transformer model.

**Library:** `transformers`

**Example input:**

`The man went to the <mask>.`

**Workflow:**

Sentence with Missing Word → Transformer Model → Candidate Predictions

**Key concepts:**
- Natural Language Processing (NLP)
- Contextual word prediction
- Masked language modeling

</details>

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Cloud notebook environment |
| gTTS | Text-to-speech generation |
| IPython | Audio playback in notebooks |
| Hugging Face Transformers | Access pretrained models |
| Salesforce CodeGen | Code generation |

## ⚙️ Installation

Install the required packages in Google Colab:

```bash
pip install gtts transformers
```

For notebook audio playback:

```bash
pip install IPython
```

## ▶️ How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab.
3. Install the required packages.
4. Run each experiment's cells in order.
5. Enter text or prompts where requested.
6. Observe the generated audio, code, and word predictions.

## 📖 Learning Outcomes

After completing these experiments, you will understand:

- How text can be converted into speech.
- How pretrained AI models generate code.
- How Transformers predict missing words.
- How Python libraries simplify Generative AI tasks.

## 🌟 Future Improvements

- Add text-to-speech support for more languages.
- Build a simple web interface for the experiments.
- Add more code-generation prompts and test cases.
- Explore other NLP and Generative AI models.

## 👩‍💻 Author

**Generative AI Learner**

Created for educational and practical learning purposes.

---

<p align="center">
  ⭐ If you find this project useful, consider starring the repository!
</p>
