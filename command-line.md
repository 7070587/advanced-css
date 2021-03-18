$ sass <input.scss> [output.css]
# sass compile

## One-to-One Mode
```bash
sass <input.scss> [output.css]
```

```bash
sass scss/main.scss:css/style.css
```

## Many-to-many Mode
```bash
sass [<input.css>:<output.css>] [<input/>:<output/>]...
```

## Watch Mode
```bash
 sass --watch scss/main.scss:css/style.css
```