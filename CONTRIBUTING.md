# Team Workflow for Notes Manager

## Development Process

1. Check the feature tickets in the `/features` directory
2. Choose a feature to work on or create a new feature ticket
3. Create a feature branch (`feature/XXX-feature-name`)
4. Implement the feature with tests
5. Submit a PR for review

## Coding Standards

- Follow PEP 8 style guidelines
- Add type hints to function signatures
- Write docstrings for all functions and classes
- Include tests for new functionality

## Pull Request Process

1. Ensure all tests pass
2. Update documentation if needed
3. Link to the relevant feature ticket
4. Request review from the project owner

## Brain State Management

The project uses specialized commands to manage context and state:

- "Wake up gang" - Restore project context from saved state
- "Checkpoint gang" - Create milestone snapshots during development
- "Get Ready for Bed gang" - Save complete session state at conclusion

See the AI Collaboration Domain README for more details.