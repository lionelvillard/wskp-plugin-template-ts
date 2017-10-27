This is a wskp plugin for ... 

# Project configuration extension

Contributes to: 
- [action](https://github.com/lionelvillard/openwhisk-project/blob/master/docs/format.md#action)
- [builder](https://github.com/lionelvillard/openwhisk-project/blob/master/docs/format.md#builder)

## `action` contribution 

This contribution ...

### Example

```yaml
actions:
  <keyword>:
```

which expands to 

```yaml
actions:
  zip-action:
    code: ...
```

## `builder` contribution 

#### Properties  

description...

- `<keyword>`: (`<schema>`, required): description....

### Example

```yaml
actions:
  zip-action:
    builder:
      name: package
      excludes:
        - *.ts
```

### `schema`

...
