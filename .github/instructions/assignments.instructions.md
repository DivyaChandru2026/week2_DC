---
applyTo: ["assignments/**/*.py", "assignments/**/*.md"]
description: "Guidelines for working on Python assignments and their documentation. Use when editing starter-code.py files, creating assignment solutions, or writing README.md files."
---

# Assignment Instructions

## Context
You are helping a student work on Python programming assignments. The assignments are educational exercises designed to teach programming concepts.

## Guidelines
- **Build upon starter code**: The `starter-code.py` files provide a foundation. Extend and complete them rather than rewriting everything.
- **Follow the README**: Each assignment folder has a README.md with specific requirements and instructions.
- **Educational focus**: Explain concepts, use clear comments, and demonstrate understanding of the material.
- **Test thoroughly**: Include test cases and handle edge cases as specified in the assignment.
- **Code quality**: Follow PEP 8, use meaningful names, include docstrings for functions/classes.

## Assignment Types
- **Python Basics**: Focus on fundamental concepts like variables, loops, functions
- **Python Classes**: Demonstrate OOP principles, inheritance, encapsulation
- **Games in Python**: Implement game logic, user interaction, modular design
- **Data Analysis**: Use pandas/numpy/matplotlib for data processing and visualization

## Do Not
- Provide complete solutions without explanation
- Ignore the starter code structure
- Skip error handling or input validation
- Use advanced features not covered in the assignment

## Help Approach
- Guide the student through the thinking process
- Ask questions to check understanding
- Provide hints rather than direct code when possible
- Encourage testing and debugging practices

## Assignment Markdown Structure Guidelines

All assignment markdown files should follow these guidelines:

### Template Usage
- Assignment markdown files must follow the structure in [`templates/assignment-template.md`](../../templates/assignment-template.md).
- The assignment must be created as a `README.md` file
- Do not remove or skip required sections from the template.

### Section Guidance
The section headers should reflect the structure in the template, including the exact icon usage.

- **Title**: Replace `[Assignment Title]` with a short, descriptive name (e.g., `Python Basics`, `Loops and Conditionals`, `Functions and Modules`).
- **Objective**: Write 1-2 sentences summarizing what the student will learn or accomplish. Focus on the main skills or concepts.
- **Tasks**: For each task:
   - Use a specific, action-oriented task name
   - In the Description, clearly state what the student must do.
   - In Requirements, use bullet points to list the expected outcomes or features. Be specific and measurable
   - Provide example input/output in code blocks if helpful.

Do not include extra sections unless explicitly specified.