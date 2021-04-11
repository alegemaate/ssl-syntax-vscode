# S/SL Syntax Support VSCODE

This extension adds basic support to VS Code for the S/SL langauge.

The Syntax/Semantic Language (S/SL) is an executable high level specification language for recursive descent parsers, semantic analyzers and code generators developed by James Cordy, Ric Holt and David Wortman at the University of Toronto in 1980.

## Features

Adds basic syntax support for .ssl and .def files in VS Code.

## Known Issues

None!

## Release Notes

### 1.0.0

Initial release of S/SL language support

### 1.0.1

Add `.def` support

Add basic icon

### 1.0.2

Add support for functions

Change token type of '\*' to represent control

Add support for '?' character

Clean up some missed tokens

### 1.0.3

Add support for function parameters

Use word bounds to ensure proper matching on tokens and numbers

Simplify regex

### 1.0.4

Fix syntax highlighting for functions followed by comments

## Testing Locally

- Make sure the language configuration settings in `language-configuration.json` are accurate.
- Press `F5` to open a new window with your extension loaded.
- Create a new file with a file name suffix matching your language.
- Verify that syntax highlighting works and that the language configuration settings are working.
