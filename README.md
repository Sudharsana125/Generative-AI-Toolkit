# Generative AI Experiments

A practical exploration of Generative AI using Python, pretrained language models, and text-to-speech technology.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white" alt="Google Colab"/>
  <img src="https://img.shields.io/badge/AI-Generative%20AI-7C3AED" alt="Generative AI"/>
  <img src="https://img.shields.io/badge/Status-Educational%20Project-2E8B57" alt="Educational Project"/>
</p>

## Overview

This repository demonstrates three Generative AI and Natural Language Processing experiments:

- **Audio Generation:** Convert text into speech using Google Text-to-Speech (gTTS).
- **Code Generation:** Generate programming code from natural-language prompts using Salesforce CodeGen.
- **Fill-Mask Prediction:** Predict missing words in a sentence using a pretrained Transformer model.

## Experiments

<details>
<summary><strong>01. Audio Generation Using gTTS</strong></summary>

**Objective:** Convert user-provided text into spoken audio.

**Technologies:** Python, gTTS, IPython

**Workflow:**

Text Input → Speech Synthesis → MP3 File → Audio Playback

**Key features:**
- Accepts text from the user.
- Generates English speech.
- Saves the output as an MP3 file.
- Plays the generated audio in Google Colab.

</details>

<details>
<summary><strong>02. Code Generation Using Salesforce CodeGen</strong></summary>

**Objective:** Generate source code from a natural-language instruction.

**Model:** `Salesforce/codegen-350M-mono`

**Technology:** Hugging Face Transformers

**Workflow:**

Natural-Language Prompt → CodeGen Model → Generated Code

**Key features:**
- Accepts programming instructions as prompts.
- Generates a code sequence using a pretrained model.
- Displays the generated output for review.

*Note: Generated code should be reviewed and tested before use.*

</details>

<details>
<summary><strong>03. Fill-Mask Text Prediction**

</strong></summary>

**Objective:** Predict possible missing words based on sentence context.

**Technology:** Hugging Face Transformers

**Example input:**

`The man went to the <mask>.`

**Workflow:**

Masked Sentence → Transformer Model → Candidate Words and Scores

**Key features:**
- Predicts possible replacements for a mask token.
- Ranks candidate words using model scores.
- Demonstrates contextual language understanding.

</details>

## Technology Stack

| Technology | Application |
|---|---|
| Python | Core programming language |
| Google Colab | Experiment execution |
| gTTS | Text-to-speech conversion |
| IPython | Audio playback |
| Hugging Face Transformers | Pretrained model pipelines |
| Salesforce CodeGen | Code generation |

## Getting Started

### Prerequisites

- A Google account to access Google Colab
- Basic Python knowledge
- An internet connection for package installation and online model or speech services

### Installation

Install the required libraries in a Google Colab cell:

```python
!pip install gtts transformers
```

For notebook audio playback, IPython is generally already available in Colab. If needed:

```python
!pip install IPython
```

### Execution

1. Open the experiment notebook in Google Colab.
2. Install the required dependencies.
3. Run the cells in sequence.
4. Enter text or prompts when requested.
5. Observe the generated audio, code, or prediction results.

## Learning Outcomes

This project provides practical exposure to:

- Text-to-speech generation
- Prompt-based code generation
- Transformer-based masked language modeling
- Using pretrained models through Python libraries
- Building and evaluating simple Generative AI workflows

## Future Enhancements

- Support for additional languages in audio generation
- A unified interface for all three experiments
- Automated testing of generated code
- Exploration of additional pretrained NLP models

## Author

Developed as an educational project to explore practical applications of Generative AI.

## License

This repository is intended for educational purposes. Refer to the respective model and library licenses before redistributing or using their outputs commercially.
