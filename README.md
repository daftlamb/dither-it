# Dither It ✦

> Turn photos into dithered artwork.

Dither It converts any image into halftone and dithered art using classic algorithms. Export as PNG, SVG, or print-ready Riso/CMYK channel separations — free to use, no signup, no server.

---

## What it does

Drop in a photo. Choose a dithering algorithm. Adjust threshold, dot size, and palette. The result is a grainy, textured image in the spirit of risograph printing, pixel art, or old newspaper reproduction — ready for export.

---

## Algorithms

- **Floyd-Steinberg** — classic error-diffusion, smooth gradients
- **Ordered (Bayer)** — regular dot matrix, retro feel
- **Atkinson** — Apple Mac classic, high contrast
- **Stucki / Burkes / Sierra** — error-diffusion variants
- **Random** — noise-based threshold

---

## Color modes

- **Monochrome** — black and white
- **Custom palette** — define your own colors
- **Riso** — pick Risograph ink colors, export separate channels

---

## Export

| Format | Description |
|--------|-------------|
| **PNG** | Flat dithered image, free |
| **SVG** | Vector dot pattern, scalable |
| **Riso Channels ZIP** | Separate PNG per ink color, print-ready |
| **CMYK Channels ZIP** | CMYK separation for offset print |

---

## Tech

- Canvas 2D API — pixel-level dithering
- Custom dithering engine (no external library)
- No backend. No framework. One HTML file.

---

## Try it

→ **[ditheritapp.com](https://ditheritapp.com)**

---

## Made by

Design by [Mog](mailto:daftlamb@gmail.com)

Part of the *\*It* series of single-purpose creative tools.
