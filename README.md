# UX-Heuristics-AI
AI-powered tool that evaluates UI screenshots using Nielsen’s UX heuristics via LLMs.
# 🎨 AI UI Enhancer – UX Heuristics Evaluator 🤖

An AI-powered tool that evaluates UI screenshots using **Nielsen’s 10 Usability Heuristics**, combining **OCR**, **Prompt Engineering**, and **LLMs**. Designed for UX designers, frontend developers, and tech enthusiasts exploring the potential of AI in usability evaluation.

## 🌟 Overview

The AI UI Enhancer is a hybrid design-tech project that uses **Generative AI** to assess the quality of user interfaces based on industry-standard UX heuristics. It aims to automate the early-stage UX audit process, providing **actionable feedback** and suggestions to improve user experience.

This tool is ideal for:
- 🚀 Rapid UI/UX iterations
- 🧠 Learning how LLMs can support design decisions
- 🛠 Building your own AI design utilities

## 🔍 How It Works

1. **Upload a UI screenshot**
2. **Extract visible text** using Tesseract OCR
3. **Send extracted context** to OpenAI GPT with custom-crafted prompts
4. **Receive heuristic-based feedback**, covering:
   - Visibility of system status
   - Match between system & real world
   - User control and freedom
   - Consistency and standards
     

## 🎯 Key Features

| Feature                            | Status     |
|------------------------------------|------------|
| Upload & display UI screenshots    | ✅ Done     |
| OCR-based text extraction          | ✅ Done     |
| Prompt-engineered GPT evaluation   | ✅ Done     |
| Streamlit UI for interaction       | ✅ Done     |

## 💡 Motivation

While UI tools are becoming smarter, **usability reviews** often remain manual and time-consuming. This project explores how AI — especially **LLMs + prompt engineering** — can support designers in performing faster, smarter UX evaluations.

Inspired by the intersection of:
- UX design principles (Nielsen’s heuristics)
- Prompt engineering
- OpenAI and Streamlit
- Real-world designer pain points

## 🧰 Tech Stack

- `Python` – backend logic
- `Streamlit` – frontend interface
- `Tesseract OCR` – text extraction from images
- `Pillow` – image processing
- `OpenAI API (GPT-4o)` – UX analysis
