# Contributing & Collaboration Guidelines

Thank you for your interest in contributing to **pero1999ita.github.io**! This document outlines our collaboration workflow, code quality expectations, and community standards for the portfolio of **PERO1999** (GitHub: [@PERO1999ita](https://github.com/PERO1999ita)).

---

## Code of Conduct

All contributors, collaborators, and community members are expected to maintain a constructive, respectful, and professional environment across all issues, pull requests, and discussions.

---

## Development Setup

The repository is built as a zero-dependency static application:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/PERO1999ita/pero1999ita.github.io.git
   cd pero1999ita.github.io
   ```
2. **Run locally**:
   - Use VS Code Live Server, or Python's built-in HTTP server:
     ```bash
     python -m http.server 8000
     ```
   - Open `http://localhost:8000` in your web browser.

---

## Contribution Workflow

### 1. Reporting Bugs & Proposing Features
- Review open and closed issues before submitting a new one.
- Provide descriptive issue titles and include steps to reproduce, affected devices, browser engines, and console output.

### 2. Pull Request Standards
1. Create a focused branch off `main`:
   ```bash
   git checkout -b feat/add-new-section
   ```
2. Follow commit message conventions (Conventional Commits):
   - `feat:` New features, sections, or UI enhancements
   - `fix:` Bug fixes, layout adjustments, or broken link repairs
   - `docs:` Documentation improvements (README, SECURITY, etc.)
   - `style:` Formatting or CSS refinements without semantic logic changes
   - `perf:` Performance or asset optimizations
3. Submit a Pull Request targeting `main` with a clear explanation of what changed and why.

---

## Code Standards & Quality Checklist

Before submitting a Pull Request, verify the following:

- [ ] **Dual-Theme Compatibility**: All components must support both `[data-theme="dark"]` and `[data-theme="light"]` using CSS variables (`--bg-primary`, `--text-primary`, `--glass-bg`, etc.).
- [ ] **Zero Inline Styles**: Use classes defined within `<style>` or dedicated stylesheet tokens.
- [ ] **Security Compliance**: Any link opening in a new tab (`target="_blank"`) **must** include `rel="noopener noreferrer"`.
- [ ] **Responsive Design**: Test layouts on both desktop and mobile viewports (`<968px`) with zero horizontal overflow.
- [ ] **Semantic Markup**: Maintain accessible HTML5 semantic hierarchy (`<aside>`, `<nav>`, `<main>`, `<section>`, `<article>`).
- [ ] **Vanilla Architecture**: Keep the codebase lean and dependency-free (no external npm bundles or CDN frameworks unless strictly approved).

---

## Collaboration & Inquiries

For project partnerships, custom plugin architecture, or server infrastructure queries:
- **Discord Hub**: [discord.bedcraftmc.eu](https://discord.bedcraftmc.eu/) — Contact **PERO1999** (`pero1999`)
- **GitHub Profile**: [@PERO1999ita](https://github.com/PERO1999ita)
