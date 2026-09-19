# Steganography Meme Builder

Browser-based tool that hides and extracts secret text in images using **LSB steganography**. All processing happens locally in your browser — images are not uploaded to a server.

## Quick start

1. Open [`index.html`](index.html) in a modern browser (or serve the folder with any static file server).
2. Upload an image (**PNG recommended**; JPEG compression can corrupt hidden data).
3. Enter a message and click **Hide Text**, or upload a stego image and click **Extract Text**.

No build step or package manager required.

## Features

- LSB depth: 1, 2, or 4 bits
- Color channel selection (all RGB, or R / G / B only)
- Optional basic XOR encryption
- Capacity hint based on image size and settings
- Drag-and-drop upload, progress feedback, reset
- Responsive card-based UI

## Layout

```
.
├── README.md
├── .gitignore
└── index.html    # single-page app (HTML/CSS/JS)
```

## Notes

- Prefer PNG for round-trip hide/extract reliability.
- Higher LSB modes increase capacity but can slightly change the visible image.
- Use responsibly; this is for education and personal experimentation.

© 2025 Steganography Meme Builder — local browser processing only.
