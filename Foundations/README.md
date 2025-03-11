# Notes
## HTML
- servers will default to searching for `index.html` as home page 
- for quick setup of boilerplate, enter `!` on line 1, then select from drop down
- **Comment Shortcut:** `Ctrl` + `/`
- command to view on wsl 2 `explorer.exe index.html`
### Adding CSS
- Method A: link to CSS file
``` HTML
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```
- Method B: Internal
```<style> Insert CSS here </style>```


## CSS
### Basic syntax
- Selectors
    - HTML element CSS rule applies to
    - Universal: `*`
        - ex: `*{color: purple;}`
    - Type: selects all of given element type, in this case: `<div>`
        - ex: selects all of type `<div>`
        - `<div>Hello again!</div> <p>Hi...</p>`
        - `div {color: white;}`
    - Class
    ``` HTML
    <div class="alert-text">Please agree to our terms of service.</div>
    ```
    - `.alert-text { color: red; }`