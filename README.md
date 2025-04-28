# 📖 Organisation `.github` Repository

## Purpose

This repository provides organisation-wide GitHub templates, including:

- 🐛 **Issue templates**: Standardise bug reports and feature requests.
- 📋 **Pull request templates**: Ensure consistent and clear code review submissions.

These templates help maintain clarity, traceability, and code quality across all projects within the organisation.

---

<details>
<summary><strong>🚀 Engineer Setup: Commit Hygiene</strong></summary>

### Why?

To enforce clean and structured Git commit messages across all repositories, all engineers must configure their Git to use the shared `.gitmessage` template.

This ensures each commit clearly states:
- **What changed**
- **Why it changed**

---

### Setup Instructions

1. Clone or download this `.github` repository.

2. Configure your Git to use the provided `.gitmessage`:

    ```bash
    git config --global commit.template .\.gitmessage
    ```

    *(Note: If your path to `.gitmessage` differs, adjust accordingly.)*

3. When committing, use:

    ```bash
    git commit
    ```

    *(without `-m`) to open the pre-filled template.*

---

</details>

---
