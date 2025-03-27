# Bend Language Support

Visual Studio Code extension providing syntax highlighting and language support for the Bend programming language.

## Features

- Syntax highlighting for both imperative and functional Bend syntax
- Support for Bend's unique features like:
  - Type and object definitions
  - Both imperative and functional style code
  - Special syntax for monadic operations
  - Pattern matching
  - Native HVM functions

## Example

```bend
# Sample Bend code
type Option(T):
  Some { value: T }
  None

def identity(x: A) -> A:
  return x

main =
  let result = (identity 41)
  (+ result 1)
```

## Requirements

- Visual Studio Code 1.60.0 or newer

## Extension Settings

- This extension doesn't contribute any settings yet.

## Known Issues

- This is an early version of the Bend language extension.
## Release Notes
### 1.0.0

Initial release of Bend language support