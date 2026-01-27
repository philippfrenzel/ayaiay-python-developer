# Senior Python Developer Agent Pack

A comprehensive ayaiay.org agent pack featuring a senior Python developer with 10+ years of experience in clean code, Domain-Driven Design (DDD), Entity Framework/ORM patterns, and unit testing best practices.

## Overview

This pack provides an expert-level Python development agent that embodies the knowledge and experience of a senior software engineer. The agent is designed to help you write production-quality Python code following industry best practices and modern software engineering principles.

## Features

### Senior Python Developer Agent

An expert AI agent specialized in:

- **Clean Code Principles**: Writing readable, maintainable, and simple code following SOLID principles
- **Domain-Driven Design (DDD)**: Implementing tactical DDD patterns including entities, value objects, aggregates, repositories, and domain services
- **ORM Best Practices**: Expert knowledge of SQLAlchemy, Django ORM, and Entity Framework patterns adapted to Python
- **Unit Testing Excellence**: Comprehensive testing with pytest, including mocking, fixtures, and test-driven development
- **Python Best Practices**: Type hints, error handling, dependency injection, logging, and modern Python features
- **Architecture**: Layered architecture with clear separation of concerns (domain, application, infrastructure, presentation)

## Installation

```bash
ayaiay install philippfrenzel/ayaiay-python-developer@1.0.0
```

## Usage

### Using the Senior Python Developer Agent

```bash
# General code assistance
ayaiay run senior-python-developer --task "Implement a user registration service"

# Code review
ayaiay run senior-python-developer --task "Review the user repository implementation"

# Architecture guidance
ayaiay run senior-python-developer --task "Design a DDD-based order management system"

# Testing help
ayaiay run senior-python-developer --task "Write unit tests for the payment service"
```

## Agent Capabilities

### 1. Code Implementation

The agent can help you implement:
- Domain entities and value objects with proper validation
- Repository patterns with clean abstractions
- Application services orchestrating business logic
- ORM models and database migrations
- API endpoints following REST best practices
- Comprehensive test suites

### 2. Code Review

Get expert reviews covering:
- Clean code principles and SOLID violations
- DDD pattern implementation
- ORM usage and query optimization
- Test coverage and quality
- Security vulnerabilities
- Performance considerations

### 3. Architecture Design

Receive guidance on:
- Layered architecture structure
- Domain model design
- Aggregate boundaries
- Repository interfaces
- Dependency injection setup
- Testing strategy

### 4. Refactoring

Get help with:
- Extracting domain logic from anemic models
- Implementing design patterns
- Improving test coverage
- Optimizing database queries
- Modernizing legacy code

## Best Practices Covered

### Clean Code
- SOLID principles
- DRY (Don't Repeat Yourself)
- YAGNI (You Aren't Gonna Need It)
- Meaningful naming conventions
- Small, focused functions
- Proper error handling

### Domain-Driven Design
- Entities with identity
- Immutable value objects
- Aggregates and aggregate roots
- Repository pattern
- Domain services
- Ubiquitous language

### ORM Patterns
- Entity mapping
- Repository implementation
- Query optimization
- Migration strategies
- Transaction management
- Connection pooling

### Testing
- Unit tests with pytest
- Test fixtures and factories
- Mocking and stubbing
- Integration tests
- Test-driven development (TDD)
- Code coverage goals

### Python Specifics
- Type hints (PEP 484)
- Dataclasses and Pydantic models
- Async/await patterns
- Context managers
- Decorators
- Property descriptors

## Example Interactions

### Example 1: Implementing a Domain Entity

**Prompt:**
```
Create a User entity following DDD principles with email validation
```

**Agent Response:**
Provides a complete implementation including:
- User entity with unique identity
- Email value object with validation
- Factory method for creation
- Type hints and documentation
- Unit tests

### Example 2: Repository Pattern

**Prompt:**
```
Implement a repository pattern for the Order aggregate using SQLAlchemy
```

**Agent Response:**
Delivers:
- Abstract repository interface in domain layer
- Concrete SQLAlchemy implementation in infrastructure layer
- Proper entity-to-model mapping
- Transaction handling
- Unit tests with mocks
- Integration tests with database

### Example 3: Code Review

**Prompt:**
```
Review this user service implementation for best practices
```

**Agent Response:**
Provides comprehensive feedback on:
- Clean code violations
- Missing error handling
- Test coverage gaps
- Security concerns
- Performance issues
- Suggested improvements with code examples

## Configuration

The agent is configured with:
- **Model**: claude-opus-4.5 (high-quality responses)
- **Temperature**: 0.7 (balanced creativity and consistency)
- **Max Tokens**: 8192 (comprehensive responses)
- **Tools**: Full access to file operations, code search, bash, web search, and GitHub integration

## Requirements

- ayaiay CLI version 1.0.0 or higher
- Python 3.10 or higher (for code examples and validation)
- Valid API key for Claude Opus 4.5 or compatible model

## Tech Stack Preferences

### Primary Technologies
- **Python**: 3.10+ with latest stable features
- **ORM**: SQLAlchemy 2.0+, Django ORM, or Tortoise ORM
- **Testing**: pytest, pytest-asyncio, pytest-cov
- **Type Checking**: mypy or pyright
- **Linting**: ruff (or black + flake8 + isort)
- **API Framework**: FastAPI or Django REST Framework
- **Dependency Management**: poetry or pip-tools

### Code Quality Tools
- **black**: Code formatting
- **isort**: Import sorting
- **mypy**: Static type checking
- **ruff**: Fast Python linter
- **bandit**: Security linting
- **pytest-cov**: Test coverage

## Project Structure

```
senior-python-developer/
├── ayaiay.yaml                          # Pack manifest
├── agents/
│   └── senior-python-developer.md       # Agent instructions
├── README.md                            # This file
└── LICENSE                              # MIT License
```

## Contributing

Contributions are welcome! Areas for enhancement:
- Additional code examples
- More DDD patterns (CQRS, Event Sourcing)
- Framework-specific guidance (Django, Flask, FastAPI)
- Advanced testing patterns
- Performance optimization techniques

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Author

Philipp Frenzel

## Support

For issues, questions, or suggestions:
- GitHub Issues: [https://github.com/philippfrenzel/ayaiay-python-developer/issues](https://github.com/philippfrenzel/ayaiay-python-developer/issues)
- ayaiay.org Documentation: [https://ayaiay.org/docs](https://ayaiay.org/docs)

## Changelog

### Version 1.0.0 (2026-01-27)

**Initial Release**
- Senior Python Developer agent with comprehensive expertise
- Clean code and SOLID principles guidance
- Domain-Driven Design (DDD) tactical patterns
- ORM and Entity Framework pattern implementation
- Unit testing best practices with pytest
- Type hints and modern Python features
- Production-ready code examples
- Comprehensive documentation

## Related Resources

- [ayaiay.org Documentation](https://ayaiay.org/docs)
- [ayaiay Demo Pack](https://github.com/ayaiayorg/ayaiay-demo)
- [Domain-Driven Design](https://martinfowler.com/tags/domain%20driven%20design.html)
- [Clean Code by Robert C. Martin](https://www.oreilly.com/library/view/clean-code-a/9780136083238/)
- [SQLAlchemy Documentation](https://docs.sqlalchemy.org/)
- [pytest Documentation](https://docs.pytest.org/)

---

**Note**: This agent is designed to provide expert guidance and generate production-quality code. Always review generated code for your specific use case and requirements.
