# CLAUDE.md - AI Assistant Guide

This document provides guidance for AI assistants working with this repository.

## Project Overview

**Repository:** test
**Status:** New/Empty Repository
**Last Updated:** 2026-01-28

> This repository is currently being initialized. Update this section with:
> - Project description and purpose
> - Target users and use cases
> - High-level architecture overview

## Repository Structure

```
/home/user/test/
├── CLAUDE.md          # This file - AI assistant guidance
└── (project files)    # Add structure as project develops
```

> Document the directory structure as the project grows:
> - `src/` - Source code
> - `tests/` - Test files
> - `docs/` - Documentation
> - `scripts/` - Build and utility scripts
> - etc.

## Technology Stack

> Update this section with the technologies used:
> - **Language:** (e.g., TypeScript, Python, Go)
> - **Framework:** (e.g., React, Express, Django)
> - **Database:** (if applicable)
> - **Build Tools:** (e.g., npm, webpack, make)
> - **Testing:** (e.g., Jest, pytest, go test)

## Development Setup

### Prerequisites

> List required software and versions:
> - Node.js >= X.X
> - npm/yarn/pnpm
> - Other dependencies

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd test

# Install dependencies
# npm install  (or equivalent)

# Set up environment
# cp .env.example .env
```

### Running the Project

```bash
# Development mode
# npm run dev

# Production build
# npm run build

# Start production server
# npm start
```

## Common Commands

| Command | Description |
|---------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm test` | Run test suite |
| `npm run lint` | Run linter |
| `npm run format` | Format code |

> Update this table with actual project commands

## Code Conventions

### File Naming

> Document naming conventions:
> - Components: `PascalCase.tsx`
> - Utilities: `camelCase.ts`
> - Tests: `*.test.ts` or `*.spec.ts`
> - Styles: `component.module.css`

### Code Style

> Document code style preferences:
> - Indentation: spaces vs tabs, size
> - Quotes: single vs double
> - Semicolons: yes/no
> - Line length limit
> - Import ordering

### Git Conventions

**Branch Naming:**
- Feature: `feature/description`
- Bugfix: `fix/description`
- Hotfix: `hotfix/description`

**Commit Messages:**
- Use conventional commits format
- Start with type: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`
- Keep subject line under 72 characters
- Use imperative mood ("Add feature" not "Added feature")

Example:
```
feat: add user authentication flow

- Implement login/logout endpoints
- Add JWT token handling
- Create auth middleware
```

## Testing Guidelines

### Running Tests

```bash
# Run all tests
# npm test

# Run specific test file
# npm test -- path/to/test

# Run with coverage
# npm run test:coverage

# Watch mode
# npm run test:watch
```

### Writing Tests

> Document testing conventions:
> - Test file location (co-located vs separate directory)
> - Naming conventions
> - Coverage requirements
> - Mocking patterns

## Architecture & Patterns

> Document key architectural decisions:
> - Design patterns used
> - State management approach
> - Error handling strategy
> - Logging conventions
> - API design principles

## Key Files & Entry Points

> Document important files:
> - Main entry point
> - Configuration files
> - Environment variables
> - Build configuration

## Environment Variables

| Variable | Description | Required | Default |
|----------|-------------|----------|---------|
| `NODE_ENV` | Environment mode | No | `development` |

> Add environment variables as they are introduced

## API Reference

> Document API endpoints if applicable:
> - Authentication requirements
> - Rate limiting
> - Common response formats
> - Error codes

## Troubleshooting

### Common Issues

> Document common problems and solutions:

**Issue:** [Description]
```
Error message or symptom
```
**Solution:** [Steps to resolve]

## AI Assistant Guidelines

### Do's

- Read existing code before making changes
- Follow established patterns in the codebase
- Run tests after making changes
- Keep changes focused and minimal
- Use the existing code style
- Commit with clear, descriptive messages

### Don'ts

- Don't introduce new dependencies without good reason
- Don't over-engineer solutions
- Don't change unrelated code
- Don't skip tests
- Don't commit sensitive data (API keys, passwords)
- Don't force push to shared branches

### Before Making Changes

1. Understand the existing code structure
2. Check for related tests
3. Verify the change is necessary
4. Consider edge cases
5. Plan the minimal change needed

### After Making Changes

1. Run the test suite
2. Run linter/formatter
3. Review your changes
4. Write clear commit messages
5. Push to the correct branch

## Contributing

> Document contribution guidelines:
> - Pull request process
> - Code review requirements
> - CI/CD pipeline
> - Release process

---

*This CLAUDE.md should be updated as the project evolves. Keep it current to help AI assistants work effectively with this codebase.*
