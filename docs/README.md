<img style="width:128px" srcset="/.assets/avatar@2x.png 256w, /.assets/avatar@3x.png 384w" sizes="128w" src="/.assets/avatar@1x.png" alt="TypedGo avatar" />

# The List

Compilation of Go tools to Go type safe.

## Motiviation

- The advantage of failing early with compile-time errors provided with type-safe code.
- The difficulty of discovering universally applicable and well tested tools among the endless options of overly specific and under tested others.

## Criteria

- Tool's main goal is replacing a reflection involving code with type safe Go code.
- Tool solve a common-enough problem that the author is not the single one suffers from it.
- Tool is well maintained and tested.
- Tool follows semver constraints.
- Tool provides a binary and not exclusively an online service (for easier integration).
- Tool accounts edge cases in input code with utilites correct AST manipulation and constructing practices and doesn't solely depend on textual operations.

## Tools

Tools are listed under main categories they are most close to.

### Configuration

| Tool                                           | Description                                               |
| ---------------------------------------------- | --------------------------------------------------------- |
| [Gonfique](https://github.com/ufukty/gonfique) | The most customizable config type generator ever created. |

### Databases

| Tool                                          | Description                              |
| --------------------------------------------- | ---------------------------------------- |
| [gqlgen](https://github.com/99designs/gqlgen) | go generate based graphql server library |
| [sqlc](https://github.com/sqlc-dev/sqlc)      | Generate type-safe code from SQL.        |

### Handlers

| Tool                                               | Description                                                                                          |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| [Gohandlers](https://github.com/ufukty/gohandlers) | De/serialization methods for request/response bindings, validators, handler listers and client code. |

## Contribute

For qualifying tools; open one PR for each entry and send to [the list](https://github.com/typedgo/the-list) for review. Create new categories as needed. Maintain the writing style of existing entries.
