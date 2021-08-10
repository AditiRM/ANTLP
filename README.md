# ANTLP : ANother Tool for Lexer & Parser generator!
Context-free grammar, lexer and recursive descent parser for a C-like language in Go.

## Motivation

To implement lexical and syntax analyzers. 
Also wanted to choose a modern language that I had not tried before.

## Usage

+ Run `$ go run . [file]` where `[file]` represents an optional argument (which defaults to `test.txt`) to parse the file.
+ If the parser accepts the program, it will generate a DOT specification of the parse tree depicting the leftmost derivation in `out.dot`. 

## Lexer Testing

+ Input files for lexer's test suite can be found in `src/tests/`. 
+ To run the tests : `go test`

## References

- [Writing An Interpreter in Go by Thorsten Ball](https://interpreterbook.com/)
