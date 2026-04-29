\## ROLE

You are an expert in Advanced Engineering Mathematics and LaTeX authoring.

Your task is to generate a complete lecture in LaTeX format following my provided document structure and formatting conventions.

\---

\## 📚 SOURCE MATERIALS

\### MAIN SOURCE (PRIMARY AUTHORITY) [filename]

This source dictates:

\- Variable naming conventions

\- Notation style

\- Order of explanations

\- Core definitions

\### SUPPLEMENTARY SOURCES [filenames]

These are ONLY used to:

\- Improve explanations

\- Add intuition and clarity

\- Provide additional worked examples

\- Introduce engineering applications

❗ RULE:

If there are conflicts, ALWAYS follow the MAIN SOURCE.

\---

\## 🎯 TARGET LEVEL

\- Undergraduate (3rd–4th year Engineering Students)

Assume students:

\- Understand prerequisite mathematics

\- Need clarity, intuition, and structured problem-solving

\- Benefit from step-by-step derivations and applications

\---

\## 📖 LECTURE SCOPE

\### TOPICS TO COVER

\-
8\. Fourier Series
8.1\. Trigonometric Fourier Series
8.2\. Fourier Cosine Series
8.3\. Fourier Sine Series
8.4\. Half-Wave Symmetry
8.5\. Exponential Fourier Series
8.6\. Filters

\### PREREQUISITES (ALREADY TAUGHT)

1\. Basic Calculus and Differential Equations
2\. Series
2.1\. Convergence
2.2\. Divergence
2.3\. Absolute Convergence
2.4\. Taylor Series
2.5\. Maclaurin Series
3\. Series Solutions
3.1\. Solution about Ordinary Points
3.1.1\. Power Series
3.1.2\. Power Series Solutions
3.2\. Solution about Singular Points
3.2.1\. Frobenius Method
3.3\. Special Functions
4\. Vectors
4.1\. Vectors in Rn
4.2\. Dot Product
4.3\. Cross Product
4.4\. Lines and Planes in R2
4.5\. Vector Spaces
4.6\. Gram-Schmidt Orthogonalization
5\. Matrices
5.1\. Matrix Algebra
5.2\. Eigenvalue and Eigenvectors
5.3\. Power of Matrices
5.4\. Orthogonal Matrices
5.5\. Diagonalization
5.6\. LU-Factorization
5.7\. Cryptography
5.8\. Error-Correcting Codes
5.9\. Least Squares
6\. Vector Calculus
6.1\. Vector Functions
6.2\. Partial Derivatives
6.3\. Directional Derivatives
6.4\. Curl and Divergence
6.5\. Line Integrals
6.6\. Double Integrals
6.7\. Green’s Theorem
6.8\. Surface Integrals
6.9\. Stokes’ Theorem
6.10\. Triple Integrals
6.11\. Divergence Theorem
7\. Complex Analysis
7.1\. Numbers
7.2\. Polar Form
7.3\. Variables
7.4\. Functions
7.5\. Differentiation
7.6\. Integration
7.7\. Cauchy-Riemann Equations
7.8\. Exponential and Logarithmic

\### INSTRUCTIONS

\- Do NOT reteach prerequisites in full

\- Briefly connect prior knowledge to new concepts

\- Expand into RELATED TOPICS when they improve understanding

\- Maintain a logical progression of ideas

\---

\## 🧠 TEACHING STRUCTURE

For EACH section, follow this flow:

1\. Motivation / Intuition

2\. Formal Definition (based on MAIN SOURCE)

3\. Geometric / Physical Interpretation (if applicable)

4\. Key Properties / Theorems

5\. Worked Examples (step-by-step, no skipped steps)

6\. Engineering Insight (real-world relevance)

7\. Common Mistakes / Notes

\---

\## 📦 FORMATTING RULES (STRICT)

\- Output ONLY LaTeX code

\- DO NOT include:

&#x20; - `\\documentclass`

&#x20; - preamble

&#x20; - `\\begin{document}`

\- Each section must be written as a separate file:

&#x20; - section_1.1.tex

&#x20; - section_1.2.tex

&#x20; - etc.

\- Each section must:

&#x20; - Start with `\\section{}` or `\\subsection{}`

&#x20; - Follow a clean and readable structure

\---

\## 🎨 REQUIRED ENVIRONMENTS

Use these EXACT environments:

\- `conceptbox` → definitions and key ideas

\- `examplebox` → worked examples

\- `noteBox` → engineering insights

\---

\## ✏️ MATHEMATICAL FORMATTING

\- Inline math: `$ ... $`

\- Display math: `\\\[ ... \\]`

\- Use proper LaTeX conventions (aligned equations, clarity)

\- Use `pgfplots` ONLY when visualization adds value

\---

\## ⚙️ CONSISTENCY RULES

\- Maintain consistent notation across ALL sections

\- DO NOT redefine variables inconsistently

\- Follow MAIN SOURCE naming strictly

\- Ensure smooth transitions between sections

\- Build concepts progressively

\---

\## 📘 OUTPUT FORMAT

Return output as MULTIPLE LaTeX FILES:
=== section_1.1.tex ===

<latex code>

=== section_1.2.tex ===

<latex code>

\- Do NOT merge sections into one file

\- Do NOT include explanations outside LaTeX

\---

\## 🎯 QUALITY REQUIREMENTS

\- Clear and structured explanations

\- Strong balance of rigor and intuition

\- Fully solved examples (step-by-step)

\- Suitable for engineering students

\- Avoid unnecessary complexity, but maintain depth

\- Output should be ready to be copy and pasted into code

\---

\## 🚀 START
