# Collaborative Test Prep Module

A dynamic, student-contributed repository of practice questions and explanations for standardized exams. This project enables collaborative learning, version control, and continuous improvement of test preparation materials.

## Project Goals

1. **Create a living resource** that evolves with each new class or semester.
2. **Foster collaboration** among students through peer review and collective knowledge building.
3. **Teach version control** and collaborative workflows using GitHub.
4. **Produce high-quality, curriculum-aligned** practice materials for high-stakes exams.

## Repository Structure

```
standardized-test-prep-module/
├── topics/                   # Subject-specific folders (e.g., topics/civil-war/)
├── questions/
│   ├── multiple-choice/      # Multiple-choice questions
│   └── free-response/        # Free-response questions
├── explanations/             # Detailed explanations for questions
├── guidelines/               # Contribution guidelines, style guides
└── assets/                  # Images, diagrams, etc. (optional)
```

## Contribution Guidelines

### 1. Proposing New Content
- Create a **GitHub Issue** with the label `new-question` or `content-request`.
- Include the topic, question type, and a brief description.
- Assign the issue to yourself or a team member.

### 2. Writing Questions & Explanations
- Follow the naming convention: `topic-questionID.md` (e.g., `civil-war-mc-001.md`).
- Use Markdown formatting for clarity.
- Place multiple-choice questions in `questions/multiple-choice/`.
- Place free-response questions in `questions/free-response/`.
- Place explanations in `explanations/` with matching IDs.

### 3. Submitting Changes
- Fork the repository or create a new branch.
- Add your files in the appropriate folders.
- Submit a **Pull Request** that references the original issue (e.g., "Resolves #45").
- Await review from the teacher or peer reviewers.

### 4. Review Process
- Reviewers will leave inline comments on specific lines.
- Address all feedback before requesting a merge.
- Once approved, the PR will be merged into the main branch.

## File Naming Conventions

- **Multiple-choice questions:** `topic-mc-###.md` (e.g., `algebra-mc-012.md`)
- **Free-response questions:** `topic-fr-###.md` (e.g., `physics-fr-005.md`)
- **Explanations:** `explanation-###.md` (e.g., `explanation-012.md`)

## Labels Used for Issues

- `new-question` – Proposal for a new practice question
- `content-request` – Request for explanations or additional resources
- `clarification-needed` – More details required on existing content
- `topic-*` – Specific subject area (e.g., `topic-algebra`, `topic-us-history`)
- `bug` – Error in existing content
- `enhancement` – Improvement to existing content

## Versioning & Releases

Before major exams, the repository will be packaged into a **GitHub Release** (e.g., `v1.0-midterm-review`). Each release includes a downloadable ZIP of all vetted materials up to that point.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). You are free to share and adapt the materials for non-commercial purposes, with appropriate attribution.

## Contact

For questions about the project, please open an issue or contact the teacher via the classroom platform.

---

*Happy collaborating and good luck on your exams!*