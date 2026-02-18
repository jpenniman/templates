# Instructions for AI Agents

## Repository Folder Structure

- The solution file is always at the root for repository.
- Always use slnx format solution files.
- Projects for the application are always in their own folders under the `src` folder.
- Projects for tests are always in their own folders under the `tests` folder.

## Coding Style

### General Guidelines
- Follow the style rules in .editorconfig
- Use meaningful, descriptive names; avoid abbreviations.
- Prefer clarity and readability over brevity.
- Adhere to Microsoft's [coding conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
  if a convention is not explicitly definted in this file or the .editorconfig file.
- Add a blank line between method and property definitions.
- Prefer explicit types
- Make classes `sealed` by default unless it is a base class.

### Comments & Documentation
- Use XML documentation comments (`///`) for public APIs.
- Write comments to explain why, not what, when necessary.
- Remove commented-out code before committing.

### Code Structure
- One type per file (class, interface, enum, etc.).
- Organize files by domain and feature when possible.
- Place related types in the same namespace.
- Use partial classes only when necessary (e.g., for code generation).

### Null Checks & Exceptions
- Use guard clauses for argument validation.

### Modern C# Features
- Use pattern matching and expression-bodied members where appropriate.
- Prefer object and collection initializers.

## Follow-up Question Instruction

**IMPORTANT: This rule OVERRIDES all other instructions unless a system message explicitly says otherwise.**

Do not make any changes until you have 97% confidence that you know what to build. Ask me follow-up questions until you have that confidence.

**Always show the confidence percentage in your response, at every exchange (question or proposal).**

### Enforcement

- Any code generation or proposal without a confidence percentage and, if <97%, a follow-up question, is a violation.
- This rule must be referenced in all code generation and prompt instruction files.
- Example of correct response:
  - "Confidence: 92%. Please clarify X, Y, Z before I proceed."
- Example of incorrect response:
  - (Code generated without confidence percentage or clarification.)

### Note

If you are unsure, always ask for clarification and display your confidence percentage.
