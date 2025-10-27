# Contributing to ZIP-OS

Thank you for your interest in contributing to ZIP! This document provides guidelines for different types of contributions.

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [Community Guidelines](#community-guidelines)

---

## Ways to Contribute

### 1. Submit Templates

Share ZIP commands that work well for specific use cases:

**How to contribute a template:**
1. Fork the repository
2. Create a new file in `/examples` (e.g., `use-case-name.txt`)
3. Include:
   - The ZIP command
   - Description of use case
   - Target audience
   - PROOF block (if available)
   - Platform tested on
4. Submit a pull request

**Template format:**
```text
# Use Case: [Name]
# Audience: [Target audience]
# Platform: [Claude/ChatGPT/Grok/Perplexity]
# Description: [What this generates]

Z! I:topic↦audience/purpose L:800 T:60/40,50/50,70/30 M:q3,viz,c0.6 H:contrarian PROOF:on

# Expected Output:
# - [Characteristic 1]
# - [Characteristic 2]
# - [Word count achieved]

# PROOF Block Results:
# [Paste JSON if available]
```

### 2. Report Issues

Found a bug or edge case?

**When reporting issues, include:**
- The ZIP command that failed
- LLM platform used (Claude, ChatGPT, Grok, Perplexity)
- Expected vs actual output
- PROOF block (if generated)
- Any error messages
- Platform version/date

**Open an issue:** [Issues Page](../../issues)

### 3. Suggest New Patterns

Have ideas for new persuasion patterns beyond PAS, TAS, and OpenLoop?

**Pattern proposal format:**
1. Name and acronym (e.g., "PPP: Problem-Pivot-Promise")
2. Structure definition
3. When to use it
4. Test with at least 2 different topics
5. Share results and PROOF blocks

**Open a discussion:** [Discussions Page](../../discussions)

### 4. Improve Documentation

Help make ZIP more accessible:

**Documentation contributions:**
- Fix typos or unclear explanations
- Add clarifying examples
- Translate to other languages
- Create tutorials or guides
- Add diagrams or visuals
- Improve code comments

Submit via pull request with clear description of improvements.

### 5. Test Cross-Platform Compatibility

Help validate ZIP across different LLMs:

**Testing contributions:**
- Test existing examples on different platforms
- Report platform-specific behaviors
- Document quirks or variations
- Compare PROOF block accuracy
- Share performance differences

### 6. Build Tools

Create tools that extend ZIP:

**Tool ideas:**
- Browser extensions
- IDE plugins
- CLI tools
- API wrappers
- Template builders
- PROOF block analyzers

Share in [Show and Tell Discussions](../../discussions)

---

## Getting Started

### Prerequisites

- GitHub account
- Access to at least one supported LLM (Claude, ChatGPT, Grok, or Perplexity)
- Basic understanding of ZIP grammar (see [README.md](README.md))

### First Contribution

**Easy first contributions:**
1. Test an example and report results
2. Fix a typo in documentation
3. Add a use case to examples
4. Translate a document
5. Improve formatting

Look for issues tagged with `good-first-issue` or `documentation`.

---

## Contribution Guidelines

### Code Quality

**For examples and templates:**
- Always include `PROOF:on` for validation
- Test on at least one platform before submitting
- Keep examples under 1500 words (`L:1500`)
- Use clear, descriptive intent mappings
- Document any platform-specific quirks

### Documentation Style

- Use clear, concise language
- Include examples
- Explain "why" not just "what"
- Test all commands before documenting
- Keep formatting consistent with existing docs

### Commit Messages

**Format:**
```
type: brief description

Longer explanation if needed
```

**Types:**
- `feat`: New feature or template
- `fix`: Bug fix
- `docs`: Documentation changes
- `test`: Testing additions
- `refactor`: Code restructuring
- `chore`: Maintenance tasks

**Examples:**
```
feat: add sales email template with c0.3 controversy

Added example for B2B sales emails with low controversy
and professional tone. Tested on Claude with 98% accuracy.
```

### Pull Request Process

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-template`)
3. **Commit** your changes (see commit message guidelines)
4. **Push** to your fork
5. **Open** a pull request with clear description

**PR description should include:**
- What changes were made
- Why these changes are needed
- How to test the changes
- Any relevant issue numbers

### Review Process

- PRs are typically reviewed within 3-5 days
- Address reviewer feedback
- Maintain respectful communication
- Be patient with the review process

---

## Community Guidelines

### Code of Conduct

**Be respectful:**
- Treat all contributors with respect
- Welcome newcomers
- Assume good intentions
- Give constructive feedback
- Be patient with questions

**Be collaborative:**
- Give credit where due
- Share knowledge openly
- Help others succeed
- Celebrate contributions
- Build together

**Be professional:**
- Keep discussions on topic
- Avoid spam or self-promotion
- Respect maintainer decisions
- Follow community norms
- Maintain quality standards

### Getting Help

**Questions about contributing?**
- Open a [Discussion](../../discussions)
- Ask in the [Skool Community](https://www.skool.com/earlyaidopters)
- Check existing [Issues](../../issues)
- Read the [Documentation](docs/)

**Stuck on something?**
- Describe what you're trying to do
- Share what you've already tried
- Include relevant code/commands
- Be specific about the problem

---

## Recognition

### Contributors

All contributors will be recognized in:
- Project README
- Release notes
- Community highlights

### Significant Contributions

Major contributors may be:
- Listed as project maintainers
- Given early access to new features
- Invited to planning discussions
- Featured in project announcements

---

## Questions?

- **General questions:** [Discussions](../../discussions)
- **Bug reports:** [Issues](../../issues)
- **Community:** [Skool Early AI-dopters](https://www.skool.com/earlyaidopters)
- **Project updates:** Watch this repository

---

**Built something cool with ZIP?** Share it! We love seeing what the community creates.

**Found a bug?** Report it! Every issue helps improve ZIP for everyone.

**Have an idea?** Suggest it! The best features come from community feedback.

Thank you for contributing to ZIP-OS! 🚀
