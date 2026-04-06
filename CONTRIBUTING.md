# Contributing to Novum Systems Projects

This document defines the standard workflow and engineering practices for all repositories within the Novum Systems organization.

These guidelines are designed to ensure consistency, maintainability, and scalability across all projects.

---

## 1. Overview

All work within this organization follows a structured lifecycle:

Issue → Planning → Implementation → Review → Merge

Every change should be traceable, intentional, and aligned with project goals.

---

## 2. Work Intake (Issues)

All work must begin with an issue.

### Issue Types

Use the appropriate template:

- Bug → unexpected behavior or defects
- Feature → new functionality
- Task → internal development work
- Question → clarification or discussion

### Requirements

- Issues must be clearly described
- Include context and expected outcomes
- Apply relevant labels (priority, system domain, etc.)

---

## 3. Workflow Lifecycle

Each issue moves through defined stages:

- Backlog → not yet prioritised
- Ready → approved for work
- In Progress → actively being worked on
- Review → awaiting validation
- Done → completed and merged

Work should not skip stages.

---

## 4. Branching Strategy

All work must be done in separate branches.

### Branch Naming Convention

Type/short-desription


Examples:

- feature/user-authentication
- bug/fix-login-error
- task/refactor-api-layer

### Rules

- Do NOT commit directly to main
- Keep branches focused and short-lived
- Sync with main regularly if needed

---

## 5. Pull Request Process

All changes must be submitted via Pull Requests.

### Requirements

- PR must reference an issue
- PR must clearly describe what was changed
- PR should be scoped to a single concern

### Checklist

- [ ] Code builds successfully
- [ ] No obvious errors or regressions
- [ ] Follows project structure
- [ ] Relevant documentation updated (if needed)

---

## 6. Code Standards

All code should follow these principles:

### General

- Keep code readable and maintainable
- Avoid unnecessary complexity
- Prefer clarity over cleverness

### Structure

- Follow existing project architecture
- Keep modules loosely coupled
- Maintain separation of concerns

### Naming

- Use clear, descriptive names
- Avoid abbreviations unless standard

---

## 7. Project Structure Expectations

Each repository should maintain:

- Clear folder structure
- Separation between core logic and supporting systems
- A `/docs` directory for documentation (when applicable)

---

## 8. Documentation

Documentation should be updated when:

- Adding new features
- Changing system behavior
- Introducing new patterns

Documentation should be:

- Clear and concise
- Structured and navigable

---

## 9. Communication

- Keep discussions focused and constructive
- Use issues for decisions and tracking
- Avoid undocumented changes

---

## 10. Enforcement

These guidelines apply to all contributions.

Non-compliant contributions may be rejected or require revision before merging.