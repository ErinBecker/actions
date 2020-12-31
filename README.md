# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `pr`

**Required** The pull request number

### `repo`

**Required** The value of the repository. Defaults to `github.repository`

## Outputs

### `VALID`

Tells you if the Pull Request is valid (e.g. it exists and does not modify any actions files)

## Example usage

uses: zkamvar/check-pr@use-js
with:
  pr: 227
  repo: grunwaldlab/poppr
