# Bash Language Server

**WIP: This is still very much under development. I don't expect it to work on
other computers than mine**

Bash language server implementation based.

Uses [Tree Sitter][tree-sitter] and it's [grammar for Bash][tree-sitter-bash].

## Features

- [x] Jump to declaration
- [x] Find references
- [ ] Code Outline & Show Symbols
- [ ] Code completion

## How to run locally

Install the dependencies:

    npm install

Compile the server and vscode extension

    npm run compile

Continuously compile the server using

    npm run watch:server

Launch the extension using `Launch Client` from within vscode.

[tree-sitter]: https://github.com/tree-sitter/tree-sitter
[tree-sitter-bash]: https://github.com/tree-sitter/tree-sitter-bash
