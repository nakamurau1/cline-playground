# CLAUDE.md - Guide for Repository Agents

## Build/Test/Lint Commands
This repository is primarily a playground for Cline AI. No specific build/test/lint commands are defined yet.
When implementation code is added, appropriate commands will be documented here.

## Code Style Guidelines
- **Languages**: JavaScript/TypeScript, Python may be used based on experiment needs
- **Formatting**: Use consistent indentation (2 spaces) and line endings
- **Naming**: Use camelCase for variables/functions, PascalCase for classes
- **Documentation**: All code should be well-commented with clear purpose statements
- **Error Handling**: Use try/catch blocks and provide meaningful error messages
- **Imports**: Group imports by source (internal/external), organize alphabetically
- **Types**: Use strong typing when available (TypeScript interfaces/types)

## Repository Structure
- `.cline/`: Contains Memory Bank files (projectbrief.md, productContext.md, etc.)
- `.clinerules`: Contains Cline-specific rules and preferences

## Memory Bank System
This repository uses Cline's Memory Bank system. All agents should review these files before working:
- projectbrief.md: Core requirements and goals
- activeContext.md: Current work focus and next steps
- progress.md: Current status and known issues