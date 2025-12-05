# Contributing to Awesome AI

We welcome and appreciate all contributions to the `Awesome AI` project! This guide outlines the process for contributing, ensuring a smooth and collaborative experience for everyone. By contributing, you help us build a comprehensive resource showcasing the positive impact of Artificial Intelligence.

## Table of Contents

- [Our Mission](#our-mission)
- [How to Contribute](#how-to-contribute)
    - [Suggesting a New Project](#suggesting-a-new-project)
    - [General Contribution Workflow](#general-contribution-workflow)
- [Content Guidelines](#content-guidelines)
    - [Criteria for Inclusion](#criteria-for-inclusion)
    - [Ethical AI Considerations](#ethical-ai-considerations)
- [Style Guidelines](#style-guidelines)
    - [Markdown Formatting](#markdown-formatting)
    - [Table Structure](#table-structure)
    - [Link Formatting](#link-formatting)
- [Code of Conduct](#code-of-conduct)

## Our Mission

The `Awesome AI` project aims to be a curated list tracking the beneficial applications and uses of Artificial Intelligence that help improve lives and contribute to societal good. We seek to provide a counter-narrative to the common focus on AI's potential misuses, highlighting its transformative power for positive change across various domains.

## How to Contribute

### Suggesting a New Project

To suggest a new "Awesome AI" project, please use the GitHub Issue template for "New Project Suggestion." When submitting, ensure you provide the following information:

1.  **Project Name:** The official name of the AI project or initiative.
2.  **Summary:** A concise, one-sentence description of the project.
3.  **Detailed Impact:** A paragraph (2-4 sentences) explaining the problem the AI solves, its positive impact, and *crucially, mentioning the key AI technologies used* (e.g., "uses deep learning for image classification," "employs natural language processing").
4.  **Category:** Identify the most relevant category from our existing structure (e.g., AI for Health and Medicine, AI for Environmental Sustainability, etc.).
5.  **References/Links:** Provide comprehensive and reputable links, including:
    *   GitHub repository (if open-source)
    *   Official project website
    *   Relevant research papers (e.g., Nature, arXiv, peer-reviewed journals)
    *   Reputable news articles or blog posts (e.g., Wired, MIT Technology Review, Google AI Blog, DeepMind Blog)

### General Contribution Workflow

If you're making a direct change (e.g., adding a project, fixing a typo, updating information), please follow the standard GitHub workflow:

1.  **Fork** the `Awesome AI` repository to your GitHub account.
2.  **Clone** your forked repository to your local machine:
    ```bash
    git clone https://github.com/YOUR_USERNAME/awesome-ai.git
    ```
3.  **Create a new branch** for your changes:
    ```bash
    git checkout -b feature/add-new-project-name
    ```
    (Replace `feature/add-new-project-name` with a descriptive name for your branch.)
4.  **Make your changes** to the `README.md` file (or other relevant files).
    *   For editing Markdown, a tool like [Visual Studio Code](https://code.visualstudio.com/) is recommended.
5.  **Commit your changes** with a clear and concise commit message:
    ```bash
    git commit -m "feat: Add [Project Name] to AI for [Category]"
    ```
    (Use `fix:` for corrections, `docs:` for documentation updates, etc.)
6.  **Push your changes** to your forked repository:
    ```bash
    git push origin feature/add-new-project-name
    ```
7.  **Open a Pull Request (PR)** from your forked repository's branch to the `main` branch of the original `Awesome AI` repository. Provide a clear description of your changes in the PR.

We will review your PR as quickly as possible and provide feedback or merge your contribution.

## Content Guidelines

### Criteria for Inclusion

To be included in `Awesome AI`, a project must meet the following criteria:

*   **Demonstrable Positive Impact:** The project must clearly showcase how AI is used to solve a real-world problem and improve lives or contribute to societal good. Vague or theoretical benefits will not be sufficient.
*   **AI-Centric:** The core of the project's solution must rely on Artificial Intelligence (e.g., Machine Learning, Deep Learning, NLP, Computer Vision, Robotics).
*   **Project Maturity:** While we appreciate emerging research, preference is given to projects that are beyond the conceptual stage, ideally with a working prototype, deployment, or significant research backing.
*   **Reputable Sources:** All entries must be backed by credible references, such as official project websites, research papers, or reputable news articles.
*   **No Commercial Promotion:** This list is not for self-promotion or marketing of commercial products unless they have a clear, documented, and significant public good component.

### Ethical AI Considerations

Even for beneficial AI, ethical considerations are paramount. When suggesting a project, please consider:

*   **Fairness & Bias:** Does the AI system mitigate bias and ensure equitable outcomes for all users?
*   **Transparency & Explainability:** Is it clear how the AI system makes decisions, where possible?
*   **Accountability:** Is there a clear framework for responsibility if the AI system causes harm?
*   **Privacy & Security:** Does the project handle data responsibly and securely?

Projects with clear ethical frameworks or discussions around these points are highly valued.

## Style Guidelines

To maintain consistency and readability, please adhere to the following style guidelines:

### Markdown Formatting

*   Use Markdown for all formatting (headings, bold, italics, links, tables).
*   Ensure consistent use of `##` for sub-sections and `|` for tables.
*   Keep summaries concise and impact statements clear.

### Table Structure

*   All project entries should be added to the relevant category table in the `README.md`.
*   Follow the existing column structure: `Application/Project`, `Summary`, `Details/Impact`, `References/Links`.
*   Ensure each cell contains appropriate content and formatting.

### Link Formatting

*   Use Markdown link syntax: `[Link Text](URL)`.
*   Provide descriptive link text (e.g., `[DeepMind Blog (Accessible Intro)]` instead of just `[Link]`).
*   Ensure all links are active and point to the correct resources.

## Code of Conduct

We are committed to fostering an open and welcoming environment. All contributors are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please ensure your interactions and contributions are respectful and constructive.

Thank you for helping us build an inspiring resource for Awesome AI!