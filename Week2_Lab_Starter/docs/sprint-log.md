# Sprint Log

## Sprint 1

**Sprint Goal:** By the end of this sprint, user stories will have acceptance criteria linked to numbered requirements, and the README will outline the project structure and roadmap.

### Tasks
- #1: Add acceptance criteria to each user story
- #2: Number the requirements and link each story to one
- #3: Add structure and roadmap to the README

### Sprint Review
- **Completed:**
  - Issue #1: Added acceptance criteria to each user story (closed via PR #1).
  - Issue #2: Numbered requirements (FR1–FR5, NFR1–NFR5) and linked each user story to its corresponding requirement (closed via PR #2).
  - Issue #3: Added repository structure, document links, and roadmap to the root README.md (closed via PR #3).
- **Incomplete:** None. All planned tasks were completed and merged into main.

### Retrospective
- **What went well:** Using feature branches with PR descriptions (`Closes #issue`) smoothly managed our board automation and kept the commit history organized.
- **What was difficult:** Managing nested starter directories and handling merge sync errors when local untracked files conflicted with remote changes.
- **What we will change next time:** Always pull the latest `main` branch before spawning new feature branches, and confirm working directory status with `git status` before committing.