# jonghoonbae.com

Artist website for the conductor **Jong Hoon Bae** — Artistic Director and
Principal Conductor of the Seocho Philharmonia, Seoul, and President of the
LAVS Foundation, Los Angeles.

Static HTML. No build step. Deployed on Cloudflare Pages; every push to `main`
publishes automatically.

## Files

| File | Page |
|---|---|
| `index.html` | Home |
| `biography.html` | Biography |
| `recordings.html` | Recordings |
| `contact.html` | Contact |
| `styles.css` | All styles |
| `_headers` | Cloudflare cache and security headers |
| `images/` | Photographs |

## Editorial rules

Biography copy on this site is restricted to verified material. The following
must **not** be added without documentary confirmation:

- UCLA degree titles and years; years taught at UCLA
- Founding and tenure years of the Republic of Korea Armed Forces Symphony Orchestra
- Official English name and year of the Republic of Korea honour
- Birthplace; years of study in Vienna and St Petersburg

The only verified review quotation is:

> The performances by the Seocho Philharmonia and UCLA Brass Quintet are splendid.
> — Guy Rickards, *Gramophone*, January 2022 (Naxos 8.559907)

Do not use: the "finest North American orchestras" quotation (unverified in the
English-language sources), any "Guinness World Record holder" claim (submission
reported as in progress, not awarded), or the BBC Music Magazine star rating.

Third-party databases credit Naxos 8.559907 to the wrong orchestra. The correct
ensemble is the **Seocho Philharmonia**; corrections are in progress.

## Local preview

    python3 -m http.server 8000
