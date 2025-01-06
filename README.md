# Arabic Compiler Project

This project is a compiler for a programming language based on Arabic syntax. It includes a **Lexical Analyzer (Lexer)** and a **Parser**, built using C# with a Windows Forms interface. The compiler is designed to tokenize and validate Arabic-based programming constructs, providing feedback on syntax correctness and error details.

## Features

- **Lexical Analysis**:
  - Extracts tokens from Arabic code.
  - Recognizes keywords, identifiers, numbers, operators, and punctuation.
  - Tracks token positions (line and column).

- **Parsing**:
  - Validates syntax using Context-Free Grammar (CFG) rules.
  - Implements a recursive descent approach for parsing constructs like:
    - Declarations
    - Assignments
    - Conditionals
    - Loops

- **User Interface**:
  - **Text Area**: Write Arabic code.
  - **Process Button**: Trigger the analysis process.
  - **Token Display**: Shows extracted tokens with details.
  - **Syntax Feedback**: Displays syntax validation results, including error messages.
