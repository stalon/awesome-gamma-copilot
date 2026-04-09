# Awesome GAMMA Copilot

GitHub Copilot skills and instructions for the **GAMMA framework** - a powerful Java framework for managing persistence, page descriptions, and modular web applications.

## Overview

This repository archives specialized Copilot skills and instructions tailored to GAMMA development, enabling you to leverage AI assistance for:

- **Persistence**: Entity mappings, queries, transactions, and data optimization
- **Page Design**: Layout creation, components, interactions, and accessibility
- **Modular Architecture**: Module structure, dependencies, inter-module communication
- **Web Integration**: API design, security, authentication, web-GAMMA integration
- **Debugging**: Troubleshooting GAMMA-specific issues

## Structure

```
├── skills/              # Task-specific Copilot skills
├── instructions/        # Behavioral guidelines for Copilot
```

## Installation

1. Copy skill files from `skills/` to `~/.config/Copilot/prompts/` (Linux/Mac) or `%APPDATA%/Code/User/prompts` (Windows)
2. Copy instruction files from `instructions/` to the same location
3. Restart VS Code or reload Copilot Chat

## Skills

- **gamma-persistence-helper**: Configure entities, queries, transactions, and persistence optimization
- **gamma-page-designer**: Design page layouts, components, interactions, and accessibility
- **gamma-modular-app-builder**: Build and organize modular GAMMA applications
- **gamma-web-integration**: Integrate web applications with GAMMA modules and APIs
- **gamma-debug-assistant**: Debug and troubleshoot GAMMA-related issues

## Instructions

- **gamma-persistence-instructions**: Persistence standards and conventions
- **gamma-page-instructions**: Page design guidelines
- **gamma-modular-instructions**: Modular architecture principles
- **gamma-web-instructions**: Web development and integration standards
- **gamma-general-instructions**: General GAMMA framework conventions

## Contributing

To add new skills or instructions:

1. Create a new `.prompt.md` (for skills) or `.instructions.md` (for instructions) file
2. Include a YAML frontmatter with `name`, `summary`, and `description`
3. Add clear, actionable content for Copilot
4. Submit a pull request

## License

MIT
