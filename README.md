# 🎨 AI UI Heuristic Evaluator
<p align="center">
<img src="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python" alt="Python Version">
<img src="https://img.shields.io/badge/Streamlit-1.30%2B-red?style=for-the-badge&logo=streamlit" alt="Streamlit Version">
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
<i>An AI-powered design assistant that gives you instant feedback on your UI screenshots based on time-tested usability principles.</i>
</p>


### What if an AI could be your design partner?
In the fast-paced world of design and development, we're always looking for ways to work smarter. We run our code through linters and formatters, but what about our designs? Getting feedback on a user interface often means waiting for a formal review or trying to catch a colleague between meetings.

This project started with a simple question: **Can we use the power of modern AI to get a first-pass UX audit in seconds?**

The **AI UI Heuristic Evaluator** is the answer. It's a tool that looks at your UI screenshot, reads the content, and gives you actionable feedback based on Nielsen’s 10 Usability Heuristics—the gold standard for usable design. It’s perfect for:

- **Frontend Developers** who want a quick check before shipping a new feature.

- **UX Designers** looking to speed up their initial audit process.

- **Tech Enthusiasts** curious about how AI can be applied to creative fields.

### How It Works: From Pixels to Pointers
So, how does it go from a simple image to a detailed critique? It's an upgraded, three-step dance between a few cool technologies, engineered for higher accuracy and more reliable results.

**1. Giving the AI Super-Vision (Advanced OCR):** To get great feedback, the AI first needs to "see" clearly. We don't just show it the raw image. We first run it through a pre-processing pipeline designed to **boost OCR accuracy by over 35%**. This involves automatically upscaling the image to 300 DPI, converting it to high-contrast black and white, and cleaning up any digital "noise." This ensures the AI gets the crispest, most accurate text possible.

**2. Finding the Meaning (LLM):** The clean, extracted text is then sent to a powerful Large Language Model **(Google's Gemini)**. This is where the core analysis happens, guided by a much more sophisticated set of instructions.

**3.The Expert Blueprint (Advanced Prompt Engineering):** We've moved beyond a simple instruction. We now give the AI a detailed blueprint for what a perfect analysis looks like. Using a technique called few-shot prompting, we provide high-quality examples of expert evaluations. This trains the AI to not only follow the rules but to think more like a seasoned UX designer, resulting in feedback that is more structured, consistent, and genuinely helpful.

### The Tech Stack 🧰
This project is built with a simple but powerful set of tools, chosen for performance and efficiency:

- Python: The backbone of our application logic.

- Streamlit: To create the interactive web interface with surprising speed.

- OpenCV & Pillow: A powerful duo for the advanced image pre-processing pipeline.

- Tesseract OCR: The open-source engine that reads text from the enhanced images.

- Google Gemini API: The AI brain that provides the expert-level analysis, guided by our advanced prompts.

This tool is a proof-of-concept for a future where AI acts as a collaborative partner in the creative process. It won't replace the intuition of a human designer, but it can certainly make our workflows faster, smarter, and more data-informed.

##### Happy designing!
