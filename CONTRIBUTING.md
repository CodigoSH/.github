# Contributing to CodigoSH

Thank you for your interest in contributing to our projects. We maintain high standards for code quality, documentation, and architectural integrity. By participating, you agree to uphold these standards.

---

## Development Standards

To maintain consistency across all **CodigoSH** repositories, we enforce the following technical requirements:

### 1. Style & Architecture (CSS)
* **Methodology:** We prefer BEM (Block Element Modifier) or Scoped CSS Modules to prevent global scope pollution.
* **Tokens:** Use CSS Custom Properties (variables) for all design tokens (colors, spacing, typography).
* **Optimization:** Avoid deeply nested selectors; keep specificity as low as possible for better performance.

### 2. Logic & Scripting (JS)
* **Clean Code:** Write declarative, functional JavaScript. Avoid side effects in core logic.
* **Performance:** All scripts must be optimized for execution time and memory usage.
* **Documentation:** Every function or module must include JSDoc comments explaining its purpose, parameters, and return values.

---

## Contribution Process

### 1. Issue First
Before submitting a Pull Request, please **open an issue** to discuss the proposed change. This ensures your efforts align with the project's roadmap and prevents duplicate work.

### 2. Branching Strategy
* Branch from `main` or `develop` (check the specific repository's branch structure).
* Use descriptive branch names: `feat/feature-name`, `fix/bug-name`, or `docs/update-name`.

### 3. Pull Request (PR) Requirements
To be merged, a PR must meet the following criteria:
* **Passing CI:** All automated tests and GitHub Actions must pass.
* **Style Compliance:** Code must adhere to our Prettier/ESLint configurations.
* **Single Responsibility:** Keep PRs focused. If you have multiple unrelated changes, please submit separate PRs.
* **Clear Description:** Explain the *why* behind the change, not just the *what*.

---

## Code of Conduct
We expect all contributors to maintain a professional and respectful environment. Please focus on technical merit and constructive feedback.

## Questions?
If you have questions regarding the implementation of CSS/JS systems within the organization, please open a discussion in the relevant repository.

---
*Thank you for helping us build better software.*
