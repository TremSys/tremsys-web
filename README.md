# tremsys-web

Static landing page for [tremsys.dk](https://www.tremsys.dk/).

`style.css` is generated from `input.css` with the [Tailwind CSS v4 standalone CLI](https://tailwindcss.com/docs/installation/tailwind-cli). Rebuild it after editing either `index.html` or `input.css`:

```sh
tailwindcss -i input.css -o style.css --minify
```

Public Sans is self-hosted in `fonts/` (SIL Open Font License, see `fonts/OFL.txt`), so the page makes no third-party requests.
