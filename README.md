````mdx
# Nia AI Documentation

Welcome to the Nia AI documentation repository! This repository contains the official documentation for Nia AI, powered by [Mintlify](https://mintlify.com/).

<Note>
Before contributing, please read this document carefully to understand our documentation standards and contribution process.
</Note>

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/your-org/nia-docs

# Install Mintlify CLI
npm i -g mintlify

# Start development server
mintlify dev
````

## 🛠 Development

### Prerequisites

* Node.js 18 or higher

* Git

* A code editor (we recommend VS Code with MDX extension)

### Local Development

1. Start the development server:

```bash
mintlify dev
```

1. Visit `http://localhost:3000` to preview changes

2. Make changes to `.mdx` files and see them live-reload

### Environment Setup

For VS Code users, we recommend installing these extensions:

* MDX

* Prettier

* Tailwind CSS IntelliSense

## 📝 Writing Guidelines

### Document Structure

Each document should follow this structure:

```mdx
---
title: 'Document Title'
description: 'A brief description of the content'
---

## Overview

Brief introduction to the topic.

## Main Content

Your primary content sections.

## Related
- Link to related doc 1
- Link to related doc 2
```

### Component Usage

Use Mintlify components to enhance documentation:

```mdx
<Tabs>
  <Tab title="Example 1">
    Content for example 1
  </Tab>
  <Tab title="Example 2">
    Content for example 2
  </Tab>
</Tabs>

<Steps>
  <Step title="First Step">
    Instructions for first step
  </Step>
</Steps>

<Card>
  Important information here
</Card>
```

### Code Examples

* Use syntax highlighting

* Include comments

* Keep examples concise

* Test all code examples

```typescript
// Good example
const client = new NiaAI({
  apiKey: process.env.NIA_API_KEY // Load from environment
});

// Bad example
const client = new NiaAI("your-api-key-here");
```

## 🤝 Contributing

### Contribution Process

1. **Fork & Clone**```bash
   git clone https://github.com/your-username/nia-docs
   ```

2. **Create Branch**```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**

   * Follow the writing guidelines

   * Test locally

   * Ensure all links work

4. **Submit PR**

   * Fill out the PR template

   * Reference any related issues

   * Add screenshots if applicable

### Pull Request Guidelines

* Use a clear, descriptive title

* Include before/after screenshots for visual changes

* Update table of contents if needed

* Ensure all tests pass

### Issue Guidelines

When creating an issue, use our templates and include:

* Clear description of the problem

* Steps to reproduce

* Expected vs actual behavior

* Screenshots if applicable

* Environment details

## 🔍 Quality Checks

Before submitting:

* [ ] Run `mintlify check` to validate links

* [ ] Test all code examples

* [ ] Verify all images load

* [ ] Check mobile responsiveness

* [ ] Spell-check content

## 📚 Style Guide

### Writing Style

* Use active voice

* Be concise

* Include examples

* Use consistent terminology

### Formatting

* Use proper heading hierarchy

* Include descriptive alt text for images

* Use consistent spacing

* Follow MDX best practices

### Code Style

* Use TypeScript for code examples

* Include type definitions

* Follow ESLint rules

* Use consistent formatting

## 🚨 Common Issues

<AccordionGroup>
  <Accordion title="Images Not Loading">
    * Verify image path is correct

    * Check file permissions

    * Ensure image is committed
  </Accordion>

  <Accordion title="Development Server Issues">
    * Clear cache: `mintlify clear`

    * Restart server

    * Check Node.js version
  </Accordion>
</AccordionGroup>

## 🔄 Version Control

* Main branch: production documentation

* Development branch: staging documentation

* Feature branches: new content/features

## 📦 Deployment

Deployment happens automatically when changes are merged to main:

1. PR is merged to main

2. GitHub Actions builds documentation

3. Mintlify deploys to production

## 🎯 Best Practices

### Documentation

* Keep content up to date

* Use consistent terminology

* Include practical examples

* Link related content

### Components

* Use appropriate components

* Don't overuse callouts

* Keep tabs focused

* Use steps for processes

### Navigation

* Logical content hierarchy

* Clear section names

* Consistent navigation structure

* Proper cross-linking

## 📞 Support

* Join our [Discord](https://discord.gg/yCkHSpsTm2)

* Create an issue

* Email: [founders@nozomio.com](mailto:founders@nozomio.com)

## 📄 License

This documentation is licensed under [MIT License](LICENSE).

## 🙏 Acknowledgments

* Mintlify team for the documentation platform

* All contributors to the documentation

* Nia AI team for review and support

***