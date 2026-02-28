```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, efficient, and high-quality development for all AGENTS.md files. Adherence to these principles is crucial for maintaining a sustainable and maintainable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent module should have a single, clearly defined purpose.  Avoid creating overly complex modules with multiple responsibilities.
*   **Code Reuse:**  Implement reusable components and functions whenever possible.
*   **Abstraction:**  Use abstract classes and interfaces to decouple different parts of the system and promote code reuse.
*   **Avoid Redundant Logic:** Refactor existing code to eliminate duplicated logic across multiple locations.

## 2. KISS (Keep It Simple, Stupid)

*   **Simplicity:** Prioritize simple solutions over complex ones. Complex code should be thoroughly examined and documented.
*   **Readability:**  Write code that is easy to understand, even by someone unfamiliar with the specific implementation details.
*   **Minimalism:** Avoid unnecessary complexity.  Strive for the simplest solution that satisfies the required functionality.
*   **Clear Names:** Use descriptive and consistent naming conventions for variables, functions, and classes.

## 3. SOLID Principles

*   **Single Responsibility Principle (SRP):** Each class/module should have one and only one reason to change.
*   **Open/Closed Principle:**  Systems should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients shouldn’t be forced to bound to methods they don’t use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Over-Engineering:**  Don’t implement features that aren’t currently needed.  Defer implementation until it's truly required.
*   **Progressive Complexity:** Build incrementally.  Start with the essential functionality and add complexity only as the system evolves.

## 5. Code Length & Structure

*   **Maximum Code Length:** Each file should not exceed 180 lines of code.
*   **Code Organization:**  Organize code into logical modules and packages.  Use a consistent directory structure.
*   **Comments:**  Write clear and concise comments to explain complex logic or non-obvious code sections.  Avoid unnecessary comments that merely restate the code.
*   **Naming Conventions:** Use a consistent naming convention (e.g., snake_case) throughout the codebase.

## 6. Testing

*   **Unit Testing:**  All code must be thoroughly tested through unit tests.
*   **Test Coverage:**  Achieve a minimum of 80% test coverage.  Tools should be used to automatically generate test suites.
*   **Test Design:**  Write tests that exercise expected behavior and boundary conditions.
*   **Mocking:**  Use mocks and stubs *only* for testing.  No use of real implementations.

## 7. Production Readiness

*   **Error Handling:** Implement robust error handling and logging to provide informative feedback.
*   **Logging:** Use logging strategically to track events and debug issues.
*   **Configuration:**  Use configuration files to manage application settings.
*   **Documentation:**  Include clear documentation for all modules and components.

## 8.  File Size

*   **File Size Limit:** Each file must not exceed 180 lines of code.
*   **Code Clarity:** Prioritize readable and well-structured code, minimizing unnecessary complexity.

## 9.  Specific Requirements

*   **[Module Name]:** [Brief Description] –  [Key Functionality]
*   **[Module Name]:** [Other Important Details] – [Data Structures Used]
*   **[Module Name]:** [Dependency on other modules] – [Specific Imports]



---

```