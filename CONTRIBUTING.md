# Contributing to PromptForge

Thanks for your interest in contributing to PromptForge!  
This project is built for the community, and contributions of all kinds are welcome — bug reports, feature requests, documentation improvements, and code contributions.

Please read through this guide before opening an issue or submitting a pull request.

---

## 🐞 Reporting Bugs

If you find a bug, please open a **Bug Report** using the GitHub issue template.

Before submitting:
- Make sure the issue hasn’t already been reported.
- Include clear steps to reproduce the problem.
- Add screenshots or a short screen recording if possible.

When filling out the bug report, please include:

**Environment**
- OS (e.g., Windows 11, macOS Sonoma)
- Browser version (Chrome only)
- Site where the issue occurred (ChatGPT, Claude, Gemini, Perplexity)
- Extension version (found in `chrome://extensions`)
- Whether debug mode was enabled (Alt+Shift+D)

This information helps us diagnose issues quickly.

---

## 💡 Requesting Features

Have an idea that would make PromptForge better?  
Open a **Feature Request** using the GitHub template.

Please include:
- The problem your idea solves
- The solution you’d like to see
- Any alternatives you’ve considered
- Where the feature would apply (ChatGPT, Claude, Gemini, Perplexity, Options page, etc.)
- Optional mockups or examples

Feature requests help shape the roadmap.

---

## 🧩 Code Contributions

Code contributions are welcome!  
Before submitting a pull request:

1. **Open an issue first**  
   Describe the bug or feature so we can discuss the approach.

2. **Fork the repository**  
   Create a feature branch for your changes.

3. **Follow the project structure**  
   PromptForge uses a modular architecture with:
   - `content.js` for trigger detection
   - `dropdown-ui.js` for UI rendering
   - `pm-editor.js` and `pm-view-detector.js` for ProseMirror editors
   - `perplexity-adapter.js` for site-specific logic
   - `options.js` for snippet management
   - `background.js` for cross-context communication

4. **Keep changes focused**  
   One PR = one fix or feature.

5. **Test across supported sites**  
   - ChatGPT  
   - Claude  
   - Gemini  
   - Perplexity  

6. **Run linting/formatting**  
   (If applicable — this section can be updated once linting rules are added.)

7. **Document your changes**  
   Update comments, README sections, or inline docs if needed.

---

## 📦 Pull Request Guidelines

When opening a PR:

- Reference the related issue number  
- Describe the change clearly  
- Include screenshots or videos for UI changes  
- Explain any architectural decisions  
- Keep commits clean and descriptive  

PRs that are easy to review get merged faster.

---

## 📝 Documentation Contributions

Documentation improvements are always appreciated.

You can help by:
- Improving clarity in the README
- Adding examples or screenshots
- Updating onboarding instructions
- Fixing typos or formatting issues

---

## ❤️ Community & Support

If you have questions, ideas, or want to discuss something before opening an issue, feel free to use:

- GitHub Issues → Bug reports & feature requests  
- The Support page on the PromptForge website  

Thanks again for contributing — your help makes PromptForge better for everyone!
