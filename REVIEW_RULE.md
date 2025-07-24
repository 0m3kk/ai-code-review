# JavaScript Code Review Rules

## General Principles

*   **Readability:** Code should be easy to read and understand. Use clear, descriptive names for variables, functions, and classes. Avoid abbreviations unless they are universally understood.
*   **Consistency:** Adhere to a consistent coding style throughout the codebase. This includes formatting, naming conventions, and structural patterns. Tools like ESLint can help enforce this.
*   **Modularity:** Break down large functions, components, and files into smaller, focused, and reusable modules. Each module should ideally have a single responsibility.
*   **Maintainability:** Write code that is easy to modify, extend, and debug in the future. Avoid overly complex or "clever" solutions that are hard to grasp.
*   **Performance Awareness:** While not always the primary goal, be mindful of potential performance bottlenecks, especially in critical paths or frequently executed code. Optimize for performance when necessary, but prioritize clarity first.
*   **Security:** Be vigilant about common web vulnerabilities (e.g., XSS, CSRF, injection) when handling user input, external data, or interacting with sensitive information. Sanitize and validate all inputs.
