---
description: Effective Code Comments
globs: "**/*.{js,ts,py,go,java,rb,cs}"
alwaysApply: true
---


For more context read: https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/

- NEVER write comments for code that can be understood from the code itself
- Avoid redundant comments that restate the obvious
- Use comments to clarify the intent behind complex logic or decisions
- Use comments when non-obvious assumptions are made
- Keep TODO comments specific with assignees when possible
- ALWAYS update comments when the underlying code changes

# Solution

Fix redundant comments by removing them completely.
Never attempt to add additional clarification to the comments.
