# KLH-CSE-2026-27-2420030558-LexicalAnalyzer
# Lexical Analyzer Using LEX Tool

## Team Members

- **B. Kundana Mani** - 2420030558
- **M. Sai Kridhay Kumar** - 2420030211
- **J. Madhura** - 2420030535
- **R. Lokesh Reddy** - 2420030534

## Supervisor

**Mr. B. Dwarakanath**

## Abstract

The **Lexical Analyzer Using LEX Tool** is a Compiler Design project that focuses on the implementation of the lexical analysis phase, which is the first phase of a compiler. Lexical analysis processes source code and converts it into a sequence of meaningful tokens that can be used by the subsequent phases of compilation.

The system accepts source code as input and identifies different lexical elements such as **keywords, identifiers, operators, and other symbols** using predefined patterns and regular expressions. It also removes unnecessary comments and whitespaces from the source code, making it easier to process. In addition, the system counts the number of tokens identified during the analysis and generates a **symbol table** containing information about the recognized tokens.

The project is implemented using **LEX/FLEX with C** and demonstrates important Compiler Design concepts such as tokens, regular expressions, finite automata, and lexical analysis. The project provides a simple and practical understanding of how a compiler analyzes source code during its initial phase. Overall, it demonstrates how raw source code can be scanned, categorized, and transformed into structured tokens for further compiler processing.

## Setup and Execution

### 1. Install Required Tools

Install **LEX/FLEX** and a **C compiler such as GCC**.

### 2. Clone the Repository

```bash
git clone https://github.com/kundanamani-23/KLH-CSE-2026-27-2420030558-LexicalAnalyzer
cd KLH-CSE-2026-27-2420030558-LexicalAnalyzer
```
### 3. Generate the C File

If the LEX file is named lexer.l:
```bash
flex lexer.l
```

### 4. Compile the Generated C Code
```bash
gcc lex.yy.c -o lexer
```

### 5. Run the Program
```bash
./lexer
```

On Windows:
```bash
lexer.exe
```
### 6. Provide Input

Enter the source code to be analyzed. The lexical analyzer will identify and display the tokens and generate the corresponding symbol table.

Project Features
Identify keywords
Identify identifiers
Identify operators and symbols
Remove comments and whitespaces
Count tokens
Generate a symbol table
Display lexical analysis results
Technologies Used
LEX/FLEX
C Programming
Regular Expressions
Lexical Analysis

**Current Phase Status**
- Phase 1 – Project Selection & Planning: Completed
- Phase 2 – Project Setup & Requirement Analysis: In Progress
- Phase 3 – Lexical Analyzer Implementation
- Phase 4 – Testing & Validation
- Phase 5 – Documentation & Final Submission

## Conclusion

This project demonstrates the implementation of a lexical analyzer using LEX/FLEX and C. It provides a practical understanding of how the lexical analysis phase identifies and categorizes tokens from source code and prepares them for further stages of compiler processing.
