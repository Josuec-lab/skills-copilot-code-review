## Security
- Prevent SQL injection by using parameterized queries for all database operations involving user input.
- Prevent XSS (Cross-Site Scripting) by applying context-aware encoding/escaping to all user-supplied data rendered in HTML or other outputs.
- Prevent command injection by validating and sanitizing user input, and by avoiding shell execution of user-supplied data whenever possible.
- Prevent XSS (Cross-Site Scripting) by applying context-aware encoding/escaping to all user-supplied data rendered in HTML or other outputs.
- Prevent command injection by validating and sanitizing user input, and by avoiding shell execution of user-supplied data whenever possible.
- Search for risks that might expose user data.
- Prefer loading configuration and content from the database instead of hard coded content. If absolutely necessary, load it from environment variables or a non-committed config file.

## Code Quality
- Use consistent naming conventions.
- Try to reduce code duplication.
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.