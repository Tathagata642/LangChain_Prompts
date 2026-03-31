# LangChain Prompts

A collection of LangChain prompt engineering examples using OpenAI models, demonstrating PromptTemplate usage and a Streamlit-based research paper summarization tool.

## Projects

### 1. Research Paper Summarizer (`prompt_ui.py`)
An interactive Streamlit web app that summarizes famous AI research papers in your preferred style and length.

**Papers supported:**
- Attention Is All You Need
- BERT: Pre-training of Deep Bidirectional Transformers
- GPT-3: Language Models are Few-Shot Learners
- Diffusion Models Beat GANs on Image Synthesis

**Options:**
- **Style:** Beginner-Friendly, Technical, Code-Oriented, Mathematical
- **Length:** Short, Medium, Long

### 2. Prompt Template Builder (`template.json` generator)
Creates and saves a reusable PromptTemplate for research paper summarization to a `template.json` file, which is loaded by the Streamlit app.

### 3. Basic PromptTemplate Example
A simple demo showing how to greet a person in 5 languages using LangChain's `PromptTemplate` and OpenAI.
