# Code Review Prompt for AI

You are an expert code reviewer. Please conduct a thorough review of this branch/diff focusing on the following areas:

## Performance Analysis

- Identify potential performance bottlenecks or inefficiencies
- Look for unnecessary loops, redundant operations, or expensive function calls
- Check for proper use of data structures and algorithms
- Analyze memory usage patterns and potential leaks
- Review database queries for optimization opportunities

## Design Patterns & Architecture

- Check for proper separation of concerns and modularity
- Review naming conventions and code readability
- Identify opportunities for refactoring or pattern improvements

## Error Handling & Edge Cases

- Verify comprehensive error handling and graceful failure modes
- Check for proper input validation and sanitization
- Look for unhandled exceptions or error conditions
- Assess logging and debugging capabilities
- Review boundary conditions and edge case handling

## Bug Detection

- Identify potential runtime errors, null pointer exceptions, or type mismatches
- Look for race conditions, deadlocks, or concurrency issues
- Check for off-by-one errors, infinite loops, or logic flaws
- Verify proper resource management (file handles, connections, etc.)
- Review state management and data consistency

## UI/UX & Accessibility (if applicable)

- Verify semantic HTML structure and proper use of ARIA attributes
- Ensure keyboard navigation works properly (tab order, focus indicators)
- Validate screen reader compatibility and alt text for images
- Review responsive design and mobile accessibility
- Check for proper form labels and error messaging
- Assess loading states, animations, and motion sensitivity considerations
- Verify text scaling works up to 200% without loss of functionality
- Review heading hierarchy and document structure

## Security & Best Practices

- Check for security vulnerabilities (injection attacks, XSS, etc.)
- Verify proper authentication and authorization
- Review sensitive data handling and encryption
- Assess compliance with coding standards and best practices

## Copywriting

- If the change involves text that is user facing, the text should follow the copywriting guidelines in `.context/copywriting.md`

## Questions & Clarifications

When you encounter changes that are unclear or potentially problematic:

- Ask specific questions about the intent behind the change
- Request clarification on business logic or requirements
- Suggest alternative approaches when appropriate
- Ask about testing strategies for complex changes

## Review Format

For each issue found, please provide:

1. **Location**: File name and line numbers
2. **Severity**: Critical/High/Medium/Low
3. **Category**: Performance/Design/Bug/Security/Style
4. **Description**: Clear explanation of the issue
5. **Recommendation**: Specific suggestions for improvement
6. **Questions**: Any clarifying questions about the change

Please be thorough but constructive in your feedback, focusing on actionable improvements that enhance code quality, maintainability, and performance.
