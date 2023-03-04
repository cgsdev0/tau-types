# Build TAU Types action

This action builds the type definitions for TAU from an input JSON schema file.

## Inputs

## `schema-file`

**Required** The path to the schema file. Default `"eventsub_subscriptions.json"`.

## `output-file`

**Required** The path to the output file. Default `"index.d.ts"`.

## Example usage

```
uses: cgsdev0/tau-types-action@v1
with:
  schema-file: 'schema.json'
  output-file: 'index.d.ts'
```
