<img style="width:128px" srcset="/.assets/avatar@2x.png 256w, /.assets/avatar@3x.png 384w" sizes="128w" src="/.assets/avatar@1x.png" alt="TypedGo avatar" />

# The List

Compilation of Go tools to Go type safe.

## Motiviation

- The advantage of failing early with compile-time errors provided with type-safe code.
- The difficulty of discovering universally applicable and well tested tools among the endless options of overly specific and under tested others.

## Criteria

- Tool's main goal is replacing a reflection involving code with type safe code.
- Tool solve a common-enough problem that the author is not the single one suffers from it.
- Tool is well maintained and tested.
- Tool follows semver constraints.
- Tool provides a binary and not exclusively an online service (for easier integration).
- Tool accounts edge cases in input code with utilites correct AST manipulation and constructing practices and doesn't solely depend on textual operations.

## Tools

Tools are listed under main categories they are most close to.

### Configuration

#### Gonfique

The most customizable config type generator ever created.

- [Repository](https://github.com/ufukty/gonfique)
- [Playground](https://gonfique.pages.dev)

### Handlers

#### Gohandlers

De/serialization methods for request/response bindings, validators, handler listers and client code.

- [Repository](https://github.com/ufukty/gohandlers)
- [Docs](https://gohandlers.pages.dev)
- [Demo project](https://github.com/ufukty/gohandlers-petstore)

## Contribute

For qualifying tools; open one PR for each entry and send to [the list](https://github.com/typedgo/the-list) for review. Create new categories as needed. Maintain the writing style of existing entries.
