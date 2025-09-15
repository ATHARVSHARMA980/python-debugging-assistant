# Python Debugging Assistant — FOSSEE Screening Task 2

This repository contains my submission for the IITB FOSSEE Python Screening Task 2. The task was to design a prompt for an AI assistant that can help a student debug Python code **without revealing the solution**.

## Submission Files

- `prompt.txt` — The AI debugging assistant prompt
- `README.md` — This file, containing explanation, reasoning, and submission details

---

## 1. AI Prompt

The prompt is designed to guide an AI assistant to:

- Analyze student code for bugs and logical errors
- Provide constructive hints and guiding questions
- Explain relevant Python concepts
- Encourage critical thinking
- Maintain a supportive, student-friendly tone
- Avoid giving the correct solution

The full prompt is available in `prompt.txt`.

---

## 2. Design Choices

- **Clarity & Specificity:** Each instruction clearly defines the AI’s expected behavior, making the output reliable.
- **Non-Revealing:** Explicit warnings prevent the AI from giving away solutions, focusing on hints and questions.
- **Student-Friendly:** Emphasis on positive, encouraging tone fosters learning and confidence.
- **General Yet Actionable:** The prompt works across different Python code snippets, from syntax errors to logical or conceptual mistakes.

---

## 3. Reasoning

**Tone and Style:**  
- Supportive, encouraging, and positive.  
- Avoids judgment or condescension. Focuses on guiding the student.

**Balancing Bug Identification vs Guidance:**  
- Identify potential issues first.  
- Then provide hints, explanations, or questions to guide the student to the solution.  
- Encourages learning and self-discovery.

**Adapting for Beginners vs Advanced Learners:**  
- Beginners: simpler language, basic Python concepts, guiding questions.  
- Advanced learners: technical hints, subtle logic or performance considerations, edge-case reasoning.

---

## 4. How to Use

1. Open `prompt.txt` and provide it to an AI model like ChatGPT.  
2. Input the student’s buggy Python code.  
3. The AI will provide constructive, non-revealing feedback, guiding the student toward a solution.

---

**Author:** atharv sharma
**Submission for:** IITB FOSSEE Python Screening Task 2
