# boolean-algebra-and-k-map🧮 Digital Logic Toolkit v3

An interactive, all-in-one web tool designed to help students master boolean algebra and digital logic design. Solve problems, visualize circuit diagrams, learn with interactive quizzes, and study for exams with this easy-to-use toolkit.

No installation required! Just open the single HTML file in your browser.
✨ Features

This toolkit is packed into a single, self-contained HTML file and provides a suite of powerful utilities for both solving problems and learning concepts.
1. 📝 Boolean Expression Analyzer

    Truth Table Generator: Automatically create a detailed truth table for any valid boolean expression.

    Dual Form Simplification: Instantly find the simplified Sum-of-Products (SOP) and Product-of-Sums (POS) forms of your expression.

    Step-by-Step Simplification Guide: See a detailed, four-step breakdown of how the expression was simplified using the Quine-McCluskey method, from finding minterms to selecting the final essential prime implicants.

    Flexible Input: Supports standard boolean operators (+ for OR, * for AND, ' for NOT) and parentheses for grouping.

2. ⚡ Logic Circuit Visualizer

    Automatic Diagram Generation: Enter any boolean expression in the toolkit and instantly see a clean, visual representation of the corresponding logic circuit.

    Standard Gate Symbols: Uses standard graphical symbols for AND, OR, and NOT gates.

    Clear Layout: Intelligently arranges gates and wires for maximum readability.

3. 🔢 Interactive K-Map Solver

    SOP & POS Modes: Solve Karnaugh Maps for 2, 3, or 4 variables by grouping 1s (for SOP) or 0s (for POS).

    Real-time Simplification: The simplified expression is generated instantly as you click to build your groups.

    Step-by-Step Grouping Guide: Displays a clear breakdown of the groups found and the resulting term for each, explaining how the final answer was derived.

4. 🧠 Core Concepts & Interactive Quiz

    Learning Hub: Collapsible sections provide concise explanations of fundamental concepts, including SOP vs. POS, De Morgan's Theorems, and Boolean postulates.

    Test Your Knowledge: A "Quiz" tab with interactive multiple-choice questions to test your understanding of key topics.

    Instant Feedback: Get immediate feedback on your answers and track your score.

🎯 Motivation

This tool was created to be a practical study aid for students in introductory courses like "Elements of Computing." Instead of juggling different calculators and textbooks, this toolkit provides a single, interactive platform to:

    Check homework answers for assignments on boolean algebra and logic simplification.

    Understand the process of simplification, not just the final answer.

    Visualize complex concepts like logic circuits and K-Maps in an intuitive way.

    Actively learn and test your knowledge with an integrated quiz.

    Study core principles required for exams in a quick-reference format.

🛠️ Tech Stack

This project is intentionally simple and accessible:

    HTML: For the overall structure.

    Tailwind CSS: For modern and responsive styling, loaded via CDN.

    Vanilla JavaScript: For all the logic, including expression parsing, Quine-McCluskey simplification, K-map solving, SVG circuit generation, and quiz functionality.

The entire application is contained within a single .html file, making it incredibly portable and easy to use.
🚀 How to Use

Getting started is as simple as it gets:

    Download: Clone this repository or simply download the digital_logic_toolkit.html file.

    Open: Open the digital_logic_toolkit.html file in any modern web browser (like Chrome, Firefox, or Edge).

    Start Learning! No servers, no dependencies, no build steps.

🔮 Future Improvements

    [ ] More complex circuit layout algorithms for larger expressions.

    [ ] An expanded quiz bank with more challenging questions.

Feel free to fork this project, suggest features, or contribute!
