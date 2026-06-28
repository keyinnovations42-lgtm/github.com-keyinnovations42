# Key Innovations

**Construction technology studio — Marion, Ohio**

This repository hosts the official homepage for [Key Innovations](https://key-innovations.com), an independent studio building AI-powered software tools for the construction industry — created by a developer who came from the job site.

## What This Is

A single-page business landing site (`index.html`) served via GitHub Pages at [key-innovations.com](https://key-innovations.com). Sections:

- **About** — who's behind the studio and why the construction + software combination matters
- **Work** — current and in-progress projects
- **Contact** — a contact form that reaches the studio by email

## Contact Form & Email

The contact form works out of the box. Until a form service is connected, submitting opens the visitor's email app pre-addressed to the studio (mailto fallback).

To deliver messages straight to an inbox instead:

1. Create a free form at [formspree.io](https://formspree.io) and set its notification email.
2. Copy the form ID (looks like `xpzvqkdw`).
3. Paste it into `FORMSPREE_ID` in the `<script>` block at the bottom of `index.html`.

The destination address is set via `CONTACT_EMAIL` in the same script.

## Links

- [GitHub Organization](https://github.com/keyinnovations42)
- [Contact](mailto:EricBrammer@key-innovations.com)

## Tech

Static HTML/CSS/JS · GitHub Pages · custom domain (`key-innovations.com`)

---

© 2026 Eric Brammer / Key Innovations · Marion, Ohio
