# Cursor Development Rules and Templates

A comprehensive set of development rules, standards, and templates for working with Cursor IDE.

## Overview

This repository contains a collection of development standards, best practices, and templates designed to maximize productivity and maintain code quality when working with Cursor IDE.

## Structure

```
.
├── .cursorrules              # Main cursor rules and standards
└── docs/
    └── templates/           # Project templates
        ├── feature/         # Feature documentation templates
        │   ├── README.md
        │   ├── api.md
        │   ├── architecture.md
        │   ├── components.md
        │   └── testing.md
        ├── feature-documentation-template.md
        └── task-plan-template.md
```

## Key Components

### 1. Cursor Rules (.cursorrules)

The main configuration file containing:

- Development standards
- Code formatting rules
- Git workflow practices
- Documentation requirements
- Memory management approach
- Logging standards
- Type system rules

### 2. Templates

#### Feature Documentation

- Complete template structure for new features
- Standardized documentation format
- Component documentation guidelines
- API documentation standards
- Testing requirements

#### Task Planning

- Structured task planning template
- Progress tracking format
- Status reporting standards
- Implementation steps format

## Usage

1. Copy `.cursorrules` to your project root
2. Copy template files to your project's docs directory
3. Copy the rules from `docs/cursor_settings.md` into your Cursor settings under 'Rules for AI'
4. Follow the standards and practices outlined in the rules

## Best Practices

- Always reference the rules before starting work
- Use templates for consistency
- Follow the git commit guidelines
- Maintain proper documentation
- Update templates based on learnings

## Sample Requests

### Starting a New Task

```
Hi, I need to start working on implementing user authentication. Please help me:
1. Create a new task plan
2. Set up the initial structure
3. Begin implementation
```

### Continuing a Task

```
I'd like to continue working on the authentication task from yesterday. Please:
1. Review the current status
2. Show me what's left to do
3. Help me proceed with the next steps
```

### Starting a New Feature

```
I want to start developing a new feature for user notifications. Could you:
1. Create the feature documentation structure
2. Set up the initial components
3. Help plan the implementation
```

## Contributing

Feel free to suggest improvements or report issues. Follow the standard git workflow:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

MIT License - See LICENSE file for details
