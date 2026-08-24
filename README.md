# Pejlon — landningssida

Statisk säljsida. Inga byggsteg, inget ramverk: `index.html` är hela sidan.

## Utrullning
Kopplad till Cloudflare Pages. Varje push till `main` rullas ut automatiskt.

- Build command: *(tomt)*
- Build output directory: `/`

## Filer
| Fil | Vad |
|---|---|
| `index.html` | Hela sidan (HTML + CSS inline) |
| `favicon.svg` | Ikonen |
| `_headers` | Säkerhetsheaders och cache-regler (läses av Cloudflare Pages) |
| `robots.txt` | Tillåter indexering |

## Byta domän
Sök efter `pejlon.com` i `index.html` och ersätt på alla ställen
(`canonical` och Open Graph-taggarna).
