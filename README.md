# idiomark.org

The Idiomark org site — static GitHub Pages, serving [`idiomark.org`](https://idiomark.org).

Plain HTML + CSS, no build step. Brand assets live in `assets/` (Ink `#1C1B19`,
Seal `#B8402A`, Paper `#F3EEE4`).

## Local preview

```bash
python -m http.server 8080
# http://localhost:8080
```

## Deploy

Push to `main` — GitHub Pages serves from the repo root. CI (`ci-gate`) checks
internal links and brand tokens before merge.

The format itself lives at [`idiomark/idiomark`](https://github.com/idiomark/idiomark).

## License

[MIT](LICENSE) © Jordan Newell
