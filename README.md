# Behind the Mask — A Masquerade Social Mixer

One-page event website (static HTML/CSS/JS, no build step).

- **Live:** Saturday 8th August 2026 · 5:00 PM – 7:00 PM · Diamond Sea Hotel, 232 Võ Nguyên Giáp, Đà Nẵng
- **Reservations:** form emails the host (via FormSubmit) and the guest gets an auto-reply.
- **Payment:** VietQR shown on the page; reservations confirmed manually once payment is received.

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8123
```

## Deploy
Static site — deployed on Render via `render.yaml` (publish path `.`).
