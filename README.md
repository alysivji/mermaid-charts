# Mermaid Charts

Generate charts using a markdown-like syntax.

- [Docs](https://mermaid-js.github.io/)
- [Live Editor](https://mermaid-js.github.io/mermaid-live-editor)
- [mermaid-cli](https://github.com/mermaid-js/mermaid-cli)

## Instructions

```console
./node_modules/.bin/mmdc -i input.mmd -o output.svg
```

### Puppeteer

```json
// puppeteer-config.json
{
  "args": [
    "--no-sandbox"
  ],
  "executablePath": "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome"
}
```

https://stackoverflow.com/questions/47122579/run-puppeteer-on-already-installed-chrome-on-macos
