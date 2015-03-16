# react-tutorial
Just a tutorial from facebook


## commands

### debug jsx in console (optional)

`jsxhint --jsx-only --harmony *`

### watch jsx

`jsx -x jsx --harmony --source-map-inline --watch src/ build/`

## tools

### sublime text 3:

- babel
- SublimeLinter-jsxhint

settings:

```
"jsxhint": {
    "@disable": false,
    "args": [
        "--harmony"
    ],
    "excludes": []
}
```