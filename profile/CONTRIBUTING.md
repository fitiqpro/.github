# Contributing to Fitiq — Developer Guidelines

Welcome to the Fitiq Dev Team! To keep our workflow smooth and codebase clean, please follow these conventions and rules strictly.

---

## Team Roles & Access

- **Developers:**  
  Have write access to feature branches, responsible for daily development tasks.
- **Reviewers:**  
  Oversee code quality and approve PRs.
- **Maintainers/Owners:**  
  Manage merges to main branches and releases.

Only developers within the team can push branches to the repository. External contributors must use forks and submit pull requests.

---

## Branch Naming Convention

To keep branches organized and meaningful, use the following naming structure based on the type of work:

| Branch Type | Prefix       | Description                          | Example                  |
|-------------|--------------|------------------------------------|--------------------------|
| Feature     | `feature/`   | New features or enhancements       | `feature/user-auth`      |
| Bugfix      | `bugfix/`    | Fixing bugs                        | `bugfix/login-error`     |
| UI/UX       | `ui/`        | UI improvements or design changes | `ui/navbar-redesign`     |
| Hotfix      | `hotfix/`    | Critical fixes for production      | `hotfix/payment-bug`     |
| Experiment  | `experiment/`| Experimental or spike branches     | `experiment/new-3d-view` |

---

## Workflow Rules

- Always branch off from the latest `develop` branch.
- Use descriptive branch names following the conventions above.
- Commit messages should be clear and concise (e.g., `fix: correct login button state`).
- Push your branch only to the repository if you are a team developer.
- Open pull requests (PRs) against the `develop` branch.
- Assign at least one reviewer before merging.
- Do **not** merge your own PRs; maintainers or assigned reviewers handle merges.
- Resolve all merge conflicts before requesting a review.
- Keep your branches up-to-date by regularly syncing with `develop`.

---

## Additional Notes

- For hotfixes in production, branch from `main` and merge back to both `main` and `develop`.
- Avoid large, monolithic PRs; break down changes into smaller, reviewable units.
- Write unit and integration tests for all new features and bug fixes.
- Document new APIs, components, or workflows in the code and repository docs.

---

Thanks for helping keep Fitiq’s codebase clean, reliable, and scalable!

---
