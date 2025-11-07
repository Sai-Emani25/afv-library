# Agentforce Vibes Library

AI prompts and rules library for Agentforce Vibes development, content creation, and workflow automation.

## 📚 About

This repository contains curated prompts and system rules designed specifically for Agentforce Vibes projects. It includes templates for coding, content creation, documentation, and AI-assisted workflows.

## 🗂️ Structure

```
afv-library/
├── prompts/              # AI prompts organized by use case
│   ├── coding/           # Development and programming prompts
│   │   ├── debug.md
│   │   ├── refactor.md
│   │   └── documentation.md
│   ├── content/          # Content creation prompts
│   │   ├── blog-post.md
│   │   ├── social-media.md
│   │   └── marketing-copy.md
│   ├── development/       # Salesforce-specific prompts
│   │   ├── apex-helper.md
│   │   ├── flow-builder.md
│   │   └── admin-tasks.md
│   └── general/          # General-purpose prompts
│       ├── brainstorm.md
│       └── planning.md
└── rules/                # System rules for Agentforce Vibes
    ├── cursor/           # Cursor IDE configuration rules
    │   ├── coding-standards.md
    │   └── project-setup.md
    ├── cline/            # Cline agent rules
    │   └── development-workflow.md
    └── general/          # Universal AI guidelines
        └── best-practices.md
```

## 🚀 Quick Start

### Using with VS Code Extension

Coming soon!

### Manual Usage

Browse the repository and copy/paste any prompt or rule directly into your Agenforce Vibes.

## 📝 Prompt Format

All prompts use YAML frontmatter for metadata:

```markdown
---
name: Clear Prompt Name
description: Brief explanation of what this prompt does
tags: category, use-case, tool
---

Your prompt content goes here.
Include placeholders like [INSERT CODE] where users should add their own content.
```

### Example Prompt

**File:** `prompts/coding/debug.md`

```markdown
---
name: Debug Helper
description: Analyze and fix code issues
tags: coding, debugging, troubleshooting
---

Please help me debug this code:

**Code:**
[Paste your code here]

**Error:**
[Paste error message here]

**Expected behavior:**
[Describe what should happen]

Analyze the issue and provide:
1. Root cause explanation
2. Step-by-step fix
3. Prevention tips for the future
```

## 🎯 Use Cases

### For Developers
- **Code Review** - Automated code quality checks
- **Debugging** - Systematic error analysis
- **Documentation** - Generate comprehensive docs
- **Refactoring** - Modernize and optimize code

### For Content Creators
- **Blog Posts** - Structure and draft articles
- **Social Media** - Create engaging posts
- **Marketing Copy** - Generate compelling content
- **Email Templates** - Professional communication

### For Salesforce
- **Apex Development** - Best practices and patterns
- **Flow Builder** - Visual workflow assistance
- **Admin Tasks** - Configuration guidance
- **Data Management** - ETL and data quality

## 📂 Categories Guide

### Prompts

| Category | Purpose | Examples |
|----------|---------|----------|
| **coding** | Development tasks | Debug, refactor, document, test |
| **content** | Content creation | Blog posts, social media, emails |
| **salesforce** | Salesforce-specific | Apex, Flows, Admin, LWC |
| **general** | Versatile prompts | Brainstorm, plan, analyze |

### Rules

| Category | Purpose | Target Tool |
|----------|---------|-------------|
| **vibes** | IDE behavior | Cursor IDE |
| **cline** | Agent guidelines | Cline |
| **general** | Universal standards | Any AI tool |

## ✨ Creating New Prompts

1. **Choose the right category** based on use case
2. **Create a descriptive filename** (use kebab-case: `my-prompt.md`)
3. **Add frontmatter** with name, description, and tags
4. **Write clear instructions** with placeholders for user input
5. **Test the prompt** before committing
6. **Commit with message**: `Add [prompt name] for [use case]`

### Naming Conventions

- Use lowercase with hyphens: `code-review-helper.md`
- Be descriptive: `salesforce-apex-debug.md` not `debug.md`
- Include context: `blog-post-outline.md` not `outline.md`

## 🔧 Best Practices

### Writing Effective Prompts

- ✅ **Be specific** - Clear instructions yield better results
- ✅ **Use structure** - Numbered lists and sections help
- ✅ **Add context** - Explain what you want and why
- ✅ **Include examples** - Show expected output format
- ✅ **Test thoroughly** - Verify prompts work as intended

### Organizing Rules

- ✅ **One rule per file** - Keep rules focused and modular
- ✅ **Use clear names** - Describe what the rule enforces
- ✅ **Document purpose** - Explain why the rule exists
- ✅ **Keep updated** - Review and refine regularly
- ✅ **Version control** - Track changes over time

## 🔄 Maintenance

### Updating Prompts

To update an existing prompt:
1. Edit the `.md` file
2. Update the description if behavior changed
3. Test the updated prompt
4. Commit with clear message: `Update [prompt]: [what changed]`

### Adding New Categories

To add a new category:
1. Create a new folder in `prompts/` or `rules/`
2. Add a `README.md` explaining the category
3. Add initial prompts/rules
4. Update this main README with the category

## 🤝 Contributing

### For Team Members

1. Clone the repository
2. Create a feature branch: `git checkout -b add-new-prompt`
3. Add your prompt/rule following the format
4. Test thoroughly
5. Create a pull request with description

### Feedback

Found an issue or have a suggestion?
- Open an issue in GitHub
- Suggest improvements via pull request
- Share feedback in team channels
