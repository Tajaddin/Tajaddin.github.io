# tajaddin.github.io

Personal site, served by GitHub Pages from `main`. One static `index.html`, no build step, no framework, no tracking.

- `index.html` - the page. Fonts come from Google Fonts; everything else is inline.
- `Tajaddin_Gafarov_Resume.pdf` - the resume offered for download. It is generated from the resume builder in the private job-search workspace (the web copy leaves the phone number out) and copied here; edit it there, not here.
- `og.png` - the 1200x630 Open Graph image, rendered from an HTML template with headless Edge.

Local preview:

```
python -m http.server 8765
```

Numbers on the page come from each project's own benchmark. Labels: re-run (reproduced locally), live result file (needs a paid API key; the committed result matches), simulated (deterministic in-process benchmark, no network).
