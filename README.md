# Venn — Find where your lives overlap.

Venn is a flatmate matching app for students and young professionals. Think Hinge, but for finding people you'd actually want to live with.

## What's in this repo

- **`index.html`** — Landing page with hero, feature sections, testimonials, and CTA
- **`signup.html`** — Pre-registration waitlist page with a multi-step form

## Stack

Pure HTML/CSS/JS — no build step, no framework.

- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Google Fonts](https://fonts.google.com): Space Grotesk · Hanken Grotesk · Space Mono

## Running locally

Just open `index.html` in a browser. No server needed.

```bash
open index.html
```

## Brand

| Token | Hex |
|---|---|
| Venn Blue | `#335CFF` |
| Venn Violet | `#8A5BFF` |
| Overlap Indigo | `#3A2FD6` |
| Ink | `#14161B` |
| Slate | `#5A6072` |
| Mist | `#E6E8EE` |
| Paper | `#FCFCFD` |
| Canvas | `#EDEEF2` |

## Status

Currently in pre-launch. The signup form collects waitlist registrations — wire up the `handleSubmit()` function in `signup.html` to your preferred backend (Airtable, Supabase, Mailchimp, etc.).
