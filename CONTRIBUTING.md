# Contributing to Undergraduate Analysis

Thank you for your interest in contributing. This project is a rigorous repository of mathematical truth. To ensure that the notes remain a reliable resource, all contributions must follow the strict standards outlined below.

## 💎 The Rigor Standard
To maintain the "First-Principles" nature of this project, every pull request must satisfy these three criteria:

1. **No "Magic" Steps**: If you are proving a theorem, do not assume the reader knows intermediate lemmas. Either prove the lemma within the text or reference a specific, previously proven section of this project.
2. **Standardized LaTeX**:
    - Use `\[ ... \]` for display math; avoid `$$...$$`.
    - Use `\mathbb{R}, \mathbb{Q}, \mathbb{N}` for number sets.
    - Define all indices (e.g., $i, j, n \in \mathbb{N}$) upon their first appearance in a proof.
3. **Language**: Use simple, explicit, and formal English. Avoid conversational fillers.

## 🚀 Workflow
1. **Fork & Branch**: Create a feature branch for your specific theorem or chapter.
2. **Atomic Commits**: Make small, logical commits (e.g., "Add proof for Bolzano-Weierstrass").
3. **Verify the Build**: Before submitting a Pull Request, ensure your code compiles locally with `lualatex`. Once pushed, check the **GitHub Actions** tab to ensure the automated build succeeds.

## ⚖️ Legal Agreement
By submitting a Pull Request, you agree that your contributions will be licensed under the project's **Apache-2.0 License**. This ensures the project remains open and accessible for both academic and commercial use.

## 📬 Reporting Issues
If you find a typo, a missing bracket in a LaTeX formula, or a logical gap in a proof, please open an **Issue** with the label `bug` or `typo`.
