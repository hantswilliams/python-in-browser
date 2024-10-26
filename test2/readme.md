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
- `quarto render` will generate the html file inside of the same folder
- then can go to pages in github and publish the html file; 
    - https://quarto.org/docs/publishing/github-pages.html 
    - by setting to the /docs folder within test2/docs in this example