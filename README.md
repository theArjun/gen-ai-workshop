# Gen AI Workshop

## Resources

1. Visit [AI Studio](https://aistudio.google.com/) for getting Gemini API keys. Accept the terms and conditions at initial setup.
2. Visit [Gemini API](https://aistudio.google.com/apikey) for getting API keys.
3. Visit [NotebookLM](https://notebooklm.google.com/) for quering on your own docs. (RAG as service)
4. Visit [langchain](https://www.langchain.com/) for more LLM tools.
5. Visit [Google ADK](https://google.github.io/adk-docs/) for creating AI agents.
6. Visit [n8n](https://n8n.io/) for creating workflows.

## Google Colab Notebooks
1. [Use LLM Client](https://colab.research.google.com/drive/1B3-ZgX3jZpr0U4LKHouwjw2AHq2lwTMh?usp=sharing#scrollTo=6uraee0RIwdA)
2. [Make LLM Client more interactive](https://colab.research.google.com/drive/136JQOyiI0rHvjGH4HiVctBQXCZNkLS6W?usp=sharing#scrollTo=nLVtrN7wh3hg)
3. [Structured Outputs](https://colab.research.google.com/drive/1RyIQYoYnpnXSraAMBl6MMfMEL3L0yyrh?usp=sharing#scrollTo=jZtuz4flpCGF)
4. [Tool Calling](https://colab.research.google.com/drive/1_VSXsuixPu0gtCzMqfiuG6G0MwMSLASF#scrollTo=ibtOJpeEs0MT)

## References
1. [Pokhara Job Service](https://www.pokharajob.com.np/)
2. [Convert JSON to JSON Schema](https://www.liquid-technologies.com/online-json-to-schema-converter)
3. Convert [Webpage to Markdown](https://chromewebstore.google.com/detail/webpage-to-markdown/ajeinonckioeekcfanjndliandidilid)

## Plan for the workshop

This intensive bootcamp provides a rapid introduction to Generative AI, focusing on practical applications and key tools.

### Part 1: Generative AI & LLMs – The Foundation (45 minutes)

* **What is Generative AI?** Core concepts, examples, and ethical considerations.
* **Large Language Models (LLMs):** How they work, embeddings, and their potential.
* **Prompt Engineering:** Basic techniques for effective communication with LLMs.

### Part 2: Building with LLMs – Tools & Agents (45 minutes)

* **LLM Orchestration with LangChain:** Introduction to the framework and basic usage.
* **Structured Outputs:** Getting consistent data from LLMs using schemas.
* **Tool Calling:** Empowering LLMs with external functions.
* **AI Agents:** Concept of autonomous AI systems.

### Part 3: Retrieval Augmented Generation (RAG) – Core & Practical (60 minutes)

* **The Need for RAG:** Addressing LLM limitations with external knowledge.
* **RAG Architecture:** Overview of the pipeline (document loading, chunking, embedding, retrieval, generation).
* **Advanced RAG Techniques (Brief Overview):** HyDE, Step-back, and other query transformation methods.
* **Practical RAG Demo:** Example of querying a knowledge source with RAG.

### Part 4: Q&A and Next Steps (15 minutes)

* Open Q&A for all topics.
* Resources for further learning.

## Use Slidev

Slidev is a Markdown-based presentation tool for developers, allowing you to create slides using Markdown and Vue components. Here's a quick guide to get started.

### Prerequisites
- Node.js (version >= 18.0) installed on your system.

### Step 1: Create a New Slidev Project
Run the following command in your terminal to scaffold a new Slidev project:
```bash
npm init slidev@latest
```
Follow the prompts to set up your project, including the project name and package manager (e.g., npm, pnpm).

### Step 2: Install Dependencies
Navigate to your project folder and install dependencies:
```bash
cd gen-ai-workshop
npm install
```

### Step 3: Start the Development Server
Launch the Slidev development server to preview your slides:
```bash
npm run dev
```
This opens a browser window at `http://localhost:3030`, displaying your slides with live reloading.

### Step 4: Edit Your Slides
- Open the `slides.md` file in your project folder.
- Write your presentation using Markdown. Slides are separated by `---`. Example:
  ```markdown
  ---
  # Slide 1
  Welcome to Slidev!
  ---
  # Slide 2
  - Create slides with Markdown
  - Use Vue components for interactivity
  ```
- Save changes, and the browser will update automatically.
- The sections are separated in pages folder.


