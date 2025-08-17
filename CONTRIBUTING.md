# Contributing to AnimeVerse 🎌

Thank you for your interest in contributing to AnimeVerse! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Reporting Bugs
- Use the GitHub issue tracker
- Provide detailed information about the bug
- Include steps to reproduce the issue
- Mention your browser and operating system

### Suggesting Features
- Open a new issue with the "enhancement" label
- Describe the feature in detail
- Explain why this feature would be useful
- Provide examples if possible

### Code Contributions
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test your changes thoroughly
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## 📋 Development Guidelines

### Code Style
- Use consistent indentation (2 spaces)
- Follow existing naming conventions
- Add comments for complex logic
- Keep functions small and focused

### HTML Guidelines
- Use semantic HTML elements
- Ensure proper accessibility
- Validate HTML structure
- Use descriptive class names

### CSS Guidelines
- Use CSS custom properties for theming
- Follow BEM methodology for class naming
- Keep styles modular and reusable
- Optimize for performance

### JavaScript Guidelines
- Use modern ES6+ features
- Write clean, readable code
- Add error handling
- Comment complex functions

## 🎨 Adding New Anime Pages

To add a new anime page:

1. Create a new HTML file (e.g., `new-anime.html`)
2. Follow the existing page structure
3. Use the base CSS and JavaScript files
4. Add custom styles in a `<style>` tag
5. Include anime-specific animations and effects
6. Update the navigation links
7. Add the page to the README

### Page Structure Template
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Name - AnimeVerse</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Custom styles for this anime */
    </style>
</head>
<body>
    <!-- Floating Icons -->
    <div class="floating-icons">
        <!-- Add relevant emojis -->
    </div>

    <!-- Navigation -->
    <!-- Hero Section -->
    <!-- Content Sections -->
    <!-- Footer -->
    
    <script src="script.js"></script>
    <script>
        // Anime-specific JavaScript
    </script>
</body>
</html>
```

## 🧪 Testing

Before submitting changes:
- Test on different browsers (Chrome, Firefox, Safari, Edge)
- Test on mobile devices
- Check for responsive design issues
- Verify all animations work correctly
- Test all interactive elements

## 📝 Commit Messages

Use clear, descriptive commit messages:
- Use present tense ("Add feature" not "Added feature")
- Use imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests after the first line

## 🏷️ Issue Labels

- `bug` - Something isn't working
- `enhancement` - New feature or request
- `documentation` - Improvements or additions to documentation
- `good first issue` - Good for newcomers
- `help wanted` - Extra attention is needed

## 📞 Getting Help

If you need help:
- Check existing issues and pull requests
- Ask questions in the issue tracker
- Be respectful and patient

## 🎯 Project Goals

- Create beautiful, responsive anime websites
- Provide smooth animations and interactions
- Maintain consistent design across pages
- Ensure accessibility and performance
- Keep code clean and maintainable

Thank you for contributing to AnimeVerse! 🌟 