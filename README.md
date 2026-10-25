# kaloconcierge-site

The public website for **Kalo Concierge** — a WhatsApp or Viber assistant for
small Greek hotels, built from conversations with hotel owners.

Live: **[kaloconcierge.com](https://kaloconcierge.com)**

## What this is

A bilingual (English / Ελληνικά) static marketing site, deliberately kept to
plain HTML and CSS with no build step and no tracking of any kind. It explains
the problem, what the pilot does, what it costs the hotel in privacy terms, and
how to get in touch.

## Structure

```text
index.html      # English
index-gr.html   # Ελληνικά
styles.css      # shared stylesheet
```

English and Greek are separate documents with reciprocal `hreflang` links and
canonical URLs, so each language has a single addressable version for search
engines.

## Deploying

The site is static and is deployed to Vercel. The repository is intentionally
free of secrets — `.env*` is ignored so that deployment tokens are never
committed.

## Notes

- No cookies, no analytics, no third-party embeds.
- The privacy commitments stated on the site are binding on the code: there is
  nothing here to collect data with.

## License

MIT — see [LICENSE](LICENSE).
