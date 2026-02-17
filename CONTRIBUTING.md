# Contributing to ag11.dev

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing to this project.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion:

1. Check if the issue already exists in [GitHub Issues](https://github.com/andreagriffiths11/ag11-landing/issues)
2. If not, create a new issue with:
   - A clear, descriptive title
   - Detailed description of the bug or suggestion
   - Steps to reproduce (for bugs)
   - Screenshots or GIFs if applicable
   - Your environment details (browser, OS, device)

### Submitting Changes

1. **Fork the repository** to your GitHub account
2. **Create a feature branch** from `master`:
   ```bash
   git checkout -b feature/your-feature-name
   # or for bug fixes:
   git checkout -b bugfix/issue-description
   ```
3. **Make your changes** following the style guidelines below
4. **Test your changes** across different browsers and devices
5. **Commit with clear messages**:
   ```bash
   git commit -m "Add feature: description" -m "Longer description if needed"
   ```
6. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request** with:
   - Clear title and description
   - Reference to related issues (if any)
   - Screenshots of visual changes

## Style Guidelines

### HTML/CSS/JavaScript

- Use Tailwind CSS classes for styling
- Keep JavaScript organized and commented for complex logic
- Use semantic HTML elements
- Ensure accessibility with proper ARIA labels and alt text
- Test on mobile devices (the site is mobile-first)

### Code Formatting

- Use 2-space indentation
- Keep lines reasonably short (readable on standard editors)
- Add comments for non-obvious logic
- Use descriptive variable and function names

## Development Workflow

### Testing Locally

```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js
npx http-server
```

Then visit `http://localhost:8000`

### Browsers to Test

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Mobile Safari (iOS)
- Chrome Mobile (Android)

## Pull Request Process

1. Ensure your PR addresses a specific issue or adds a clear improvement
2. Include screenshots or GIFs for visual changes
3. Update README.md if you're adding new features
4. Keep commits atomic and well-messaged
5. Be responsive to feedback and review comments
6. Once approved, your PR will be merged by a maintainer

## Code of Conduct

Please be respectful and constructive in all interactions. We're building a welcoming community!

## Questions?

Feel free to open an issue with the `question` label, or reach out via:
- Twitter: [@acolombiadev](https://twitter.com/acolombiadev)
- Email: [andrea@mainbranch.dev](mailto:andrea@mainbranch.dev)

Thank you for contributing! 🎉
