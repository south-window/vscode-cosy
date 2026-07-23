# Change Log

## [Unreleased]

- Grammar: remove `ELSE` from the control keywords — FOX has no ELSE statement (only `ELSEIF`, per the foxy.f CSYN table).
- Grammar: add the missing statement keywords `DEBUG` and `GUIIO`.
- Grammar: beam-physics procedure names (DL, MS, PT, ...) now highlight only in statement position (start of line or after `;`) and never before `:=`, so ordinary variables like `dl := 1.5` are no longer scoped as functions; drop the duplicated `WSET` entry.
- Grammar: in `PROCEDURE`/`FUNCTION`/`VARIABLE` declarations, only the declared name is scoped as a function name; dimensions and bounds now get normal numeric and identifier scopes.
- Grammar: add the missing `^` (exponentiation) arithmetic operator.
- Grammar: remove the dotted-name `entity.name.class` identifier pattern — FOX has no dotted names; such identifiers now get the normal variable scope.

## [0.0.4]

- Fix COSY single-quoted strings, comparison operators, real numbers, and declaration comments in the TextMate grammar.
- Replace the space-containing ICO package part with an OPC-safe 256×256 PNG icon so the VSIX satisfies Marketplace part-URI rules.
- Add grammar regression tests and an explicit package file allowlist.

## [0.0.3]

- Expand keyword, intrinsic, operator, and beam-physics highlighting.

## [0.0.2]

- Fix comment bugs.

## [0.0.1]

- Initial release