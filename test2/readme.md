# Running 

`quarto preview` will open the browser with the rendered html file.

# Adding live code:
`quarto add r-wasm/quarto-live` will add the live code feature to the markdown file.

- then can change _quarto.yaml to:
```yaml
format:
  live-html:
```

# Publishing 
- github pages:
    - `quarto publish gh-pages` will publish the html file to the gh-pages branch