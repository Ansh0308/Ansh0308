# Fonts, icons and brand-mark sources

Everything is embedded inside the SVG files (base64 WOFF2 fonts, inline `<path>` icons, inline PNGs). Nothing is loaded at view time.

## Fonts (SIL Open Font License 1.1, embedding and redistribution allowed)

| Font | Use | Source | License file |
| --- | --- | --- | --- |
| Anton 400 (latin subset, WOFF2) | Display / oversized headings | `@fontsource/anton` 5.3.0 (https://github.com/googlefonts/AntonFont) | [OFL-Anton.txt](OFL-Anton.txt) |
| JetBrains Mono 400 + 700 (latin subset, WOFF2) | Mono / body text | `@fontsource/jetbrains-mono` 5.3.0 (https://github.com/JetBrains/JetBrainsMono) | [OFL-JetBrains-Mono.txt](OFL-JetBrains-Mono.txt) |

## Icons

Brand icons come from **Simple Icons** (CC0 1.0, see [CC0-Simple-Icons.md](CC0-Simple-Icons.md)). Path data is copied unchanged and only recoloured.

| Icon(s) | Source |
| --- | --- |
| JavaScript, Python, C, C++, React, Node.js, Express, Flask, Tailwind CSS, HTML5, CSS, MySQL, PostgreSQL, MongoDB, Docker, Git, GitHub, Postman, YouTube, Instagram | `simple-icons` 16.34.0 |
| LinkedIn | `simple-icons` 13.21.0 (no longer in the current release). Simple Icons lists the official source as https://brand.linkedin.com |
| Amazon AWS | `simple-icons` 11.14.0 (no longer in the current release). Listed source: https://commons.wikimedia.org/wiki/File:Amazon_Web_Services_Logo.svg |
| OpenAI | `simple-icons` 15.22.0 (no longer in the current release). Listed source: https://openai.com/brand |
| Java (cup + steam) | Never part of Simple Icons. Taken from the Java logo SVG at https://en.wikipedia.org/wiki/File:Java_programming_language_logo.svg (Oracle / Sun Microsystems mark). Only the cup and steam shapes are used, the wordmark and trademark symbol are removed. |

Icons that are near-black in their brand colour (Express, GitHub, Vercel, Render, AWS, OpenAI) are drawn off-white so they stay visible on the navy background.

Logos and brand names are trademarks of their respective owners and are used only to identify the technologies and profiles they stand for. Check each owner's brand guidelines if you reuse them.

## Portraits

`assets/hero.svg`, `assets/id-dashboard.svg` and `assets/connect.svg` embed the supplied `id.png` / `right_pointing.png` as PNG data URIs. They are only downscaled (Lanczos, premultiplied alpha) with the RGBA alpha channel kept; no pixels are redrawn, masked or retouched.

## Authored artwork

The gym, Formula 1 (chequered flag) and cricket illustrations, the lanyard/clasp, barcode and layout were drawn for this profile.
