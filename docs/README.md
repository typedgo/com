<img class="only-light-mode" style="width:128px" srcset="/.assets/avatar@2x.png 256w, /.assets/avatar@3x.png 384w" sizes="128w" src="/.assets/avatar@1x.png" alt="TypedGo avatar" />
<img class="only-dark-mode" style="width:128px" srcset="/.assets/avatar-dark@2x.png 256w, /.assets/avatar-dark@3x.png 384w" sizes="128w" src="/.assets/avatar-dark@1x.png" alt="TypedGo avatar" />

# The List

Compilation of Go tools to Go type safe.

## Motiviation

- The advantage of failing early with compile-time errors provided with type-safe code.
- The difficulty of discovering universally applicable and well tested tools among the endless options of overly specific and under tested others.

## Criteria

- Tool's main goal is replacing a non type-safe code with type safe Go code.
- Tool solve a common-enough problem that the author is not the single one suffers from it.
- Tool is well maintained and tested.
- Tool follows semver constraints.
- Tool provides a binary and not exclusively an online service (for easier integration).
- Tool accounts edge cases in input code with utilites correct AST manipulation and constructing practices and doesn't solely depend on textual operations.

## Tools

Tools are listed under main categories they are most close to.

### APIs

| Tool                                               | Description                                                                                                                          | Replaced type-unsafe practices                                                                    |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| [Gohandlers](https://github.com/ufukty/gohandlers) | Generate code for strongly typed and reflectionless request-response binding, request validation, registering routes and Go clients. | Reflection-based struct field iteration for request/response bindings. <!-- github.com/ufukty --> |

### Configuration

| Tool                                           | Description                                               | Replaced type-unsafe practices                                                             |
| ---------------------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [Gonfique](https://github.com/ufukty/gonfique) | The most customizable config type generator ever created. | Accessing config properties through hardcoded textual map keys. <!-- github.com/ufukty --> |

### Databases

| Tool                                     | Description                       | Replaced type-unsafe practices                                                                            |
| ---------------------------------------- | --------------------------------- | --------------------------------------------------------------------------------------------------------- |
| [sqlc](https://github.com/sqlc-dev/sqlc) | Generate type-safe code from SQL. | Reflection-based database row scanning (`sql.Rows.Scan` with generic mappers). <!-- github.com/ufukty --> |

### Enums

| Tool                                                           | Description                                   | Replaced type-unsafe practices                                                    |
| -------------------------------------------------------------- | --------------------------------------------- | --------------------------------------------------------------------------------- |
| [stringer](https://pkg.go.dev/golang.org/x/tools/cmd/stringer) | Tool to generate String methods for Go enums. | `fmt`-based runtime string conversions via reflection. <!-- github.com/ufukty --> |

## Review list

See [review list](./review.md) for tools queued for review.

## Contribute

Open a PR to [the list](https://github.com/typedgo/the-list) for qualifying contributions.

Contribution criteria for new tools:

- Create new categories as needed.
- Maintain the writing style of existing entries.
- Sort the table by 1st column.
- Add your Github profile URL to the last column as comment wrapped within `<!--` and `-->`.
