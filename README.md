# Interpreter Project in Go

## Introduction

This project is about creating an interpreter written in Go. The goal is to learn Go programming while gaining an understanding of how programming languages work. The interpreter will parse and execute a C-like language with semicolons, braces, and standard operators. Spaces in the language syntax are irrelevant.

## Features and Goals

- Simple, easy-to-understand codebase.
- Interpretation of a C-like syntax.
- Focus on learning both Go programming and basic concepts of language interpretation.

## Language Syntax

### Keywords

- `fn`: For defining functions.
- `let`: For declaring variables.

### Characters

- Braces: `{` and `}`
- Parentheses: `(` and `)`
- Operators: `=` and `+`
- Others: `,` and `;`

## Code Examples

```go
let five = 5;
let ten = 10;
let add = fn(x, y) {
    x + y;
};
let result = add(five, ten);
```

## Setup and Usage

(TODO: Provide instructions on how to set up and use the interpreter)

## Contributing

(TODO: Guidelines for contributing to this project)

## License

(TODO: Add license information)
