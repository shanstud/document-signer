# Document Signer

Sign PDFs and document photos right in your browser — free, open source, no account, no uploads.

**Live app:** https://shanstud.github.io/document-signer/

Drop in a PDF or a photo of a document, place your signature on it, and download the signed PDF. Everything runs on your own device: your document is never uploaded to a server, because there is no server.

## What it does

- **Sign any PDF or document photo** (PNG/JPG), including multi-page PDFs
- **Three ways to sign** — draw it, type it in a handwriting style, or upload a photo of your signature (white background removed automatically)
- **More than one signer** — a signature library lets several people sign the same document; hand the device to the next person and the pad starts clean every time
- **Add text, dates and ticks** anywhere on any page — drag and resize everything into place
- **Works on phone and desktop**, light and dark mode
- **Built-in sample agreement** so you can try it instantly

## Privacy

This app was built privacy-first:

- Your documents are processed **entirely on your device** and are **never uploaded** — there is no document server and no database.
- The app itself **collects nothing**: no accounts, no sign-ups, no document storage.
- The PDF engine runs from code embedded in the page itself; the two code libraries load from public CDNs **with integrity checks**, so your browser verifies them before running them.
- Don't take our word for it — the code is right here in this repository. Read it, or disconnect from the internet after the page loads and it still works.

## Use it

- **Online:** open the live app link above — nothing to install.
- **Your own copy:** download `index.html` and open it in any modern browser, or host it on any static host (GitHub Pages, Netlify, your own server). It is a single file with no build step.

## Feedback — tell us what you want

Feature requests and bug reports are welcome in [Issues](../../issues). Tell us which tools you want next — the roadmap is driven by what people actually ask for.

## Roadmap

- PDF tools in the same privacy-first style: merge, split, rotate, images to PDF, PDF to images, compress
- More signature and form-filling options, based on your feedback

## Licence

MIT — see [LICENSE](LICENSE). Use it, share it, build on it.
