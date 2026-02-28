```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure the efficient, maintainable, and reliable development of AI coding agents within this repository. Strict adherence to these principles is mandatory.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data models, and utility functions must be defined once and reused throughout the codebase.
*   Avoid duplicating code.  Refactor existing code whenever possible.
*   Implement common patterns and abstractions consistently.

## 2. KISS (Keep It Simple, Stupid)

*   Code should be as concise and easy to understand as possible.
*   Favor simple, straightforward solutions over overly complex ones.
*   Reduce cognitive load by making code easily readable and understandable.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module/agent should have one, and only one, well-defined responsibility.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.  New functionality should be added through new agents or classes, not by modifying existing ones.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be required to know about methods they do not use.
*   **Dependency Inversion Principle:** High-level modules should be replaced with low-level modules, which in turn should be replaced by abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Avoid adding features or functionality that are not currently required.  Prioritize core requirements.
*   Don't implement solutions based on potential future needs.
*   Focus on completing the current task before adding new features.

## 5. Testing & Coverage

*   **All development must be productive.**  Do not allow code to sit idle.
*   **Use mocks and stubs extensively.**  All testing must be performed against mocks.  No real implementations are allowed.
*   **Test coverage must be at least 80%.**  Automated testing is critical.
*   **Unit Tests:** Focus on individual functions and components.
*   **Integration Tests:** Test the interaction between different components.
*   **Contract Tests:** Verify that the agent's contract with external systems is met.
*   **Regression Tests:**  Run tests after every code change to ensure existing functionality remains intact.

## 6. Code Length & Structure

*   **Maximum code length: 180 lines.**  Strictly enforced.
*   **File structure:**  Organize code into logical directories based on functionality.
*   **Naming conventions:** Use consistent and descriptive naming conventions.
*   **Comments:**  Add comments only where necessary for clarity.  Avoid stating the obvious.

## 7. Specific Considerations for AGENTS.md

*   **Agent Class Definitions:** Each agent class should have a clear, single responsibility.
*   **Data Structure Definitions:**  Define data structures clearly with appropriate attributes and methods.
*   **API Definitions:** Provide precise documentation for all API endpoints.
*   **Error Handling:** Implement robust error handling and logging.
*   **Configuration Management:**  Consider a flexible configuration system to manage agent parameters.
*   **Dependency Injection:**  Use dependency injection to improve testability and maintainability.

## 8.  Documentation

*   **README:**  Provide a clear and concise README explaining the purpose of the repository and how to use it.
*   **API Documentation:**  Utilize a tool (e.g., Sphinx) to generate comprehensive API documentation.
*   **Code Comments:** Include thorough comments throughout the codebase, adhering to a consistent style.

## 9.  Development Workflow

*   Prioritize code quality over rapid development.
*   Perform thorough code reviews before merging changes.
*   Use a version control system (e.g., Git) with proper branching and merging strategies.

These guidelines are intended to guide the development process and ensure that AGENTS.md remains a well-structured and maintainable codebase.  Any deviation from these guidelines will be subject to review.
```