# trimtab-privacy

Privacy policies for **Trimtab Labs** Chrome extensions, served via GitHub Pages.

- Live site: https://loringtonian.github.io/trimtab-privacy/
- One folder per extension: `/<extension>/index.html` → `https://loringtonian.github.io/trimtab-privacy/<extension>/`

## Published policies

| Extension | URL |
|-----------|-----|
| Zonewise — Time Zone Converter & World Clock | https://loringtonian.github.io/trimtab-privacy/zonewise/ |

## Adding a new policy

1. Copy `zonewise/index.html` to `<new-extension>/index.html` and edit the content.
2. Add a row to this table and a link in the root `index.html`.
3. Commit + push to `main`; GitHub Pages redeploys automatically.
4. Paste `https://loringtonian.github.io/trimtab-privacy/<new-extension>/` into the extension's Chrome Web Store **Privacy policy URL** field.
