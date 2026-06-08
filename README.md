# Salon Beispiel — Webseite

Statische Website für den Salon Beispiel in Musterstadt.
Italienisches Design, 3D-Animationen (three.js + GSAP), DSGVO-konform.

## Tech
- Reines HTML/CSS/JS (kein Build nötig)
- three.js + GSAP — **lokal gehostet** (kein CDN)
- Schriften (Playfair Display, Cormorant Garamond, Montserrat) — **lokal gehostet** (kein Google Fonts)
- Google Maps nur nach Einwilligung (Consent-Gate)

## Struktur
- `index.html` — Startseite
- `impressum.html`, `datenschutz.html`, `agb.html` — Rechtsseiten
- `legal.css` — Styling der Rechtsseiten
- `fonts/` — lokale Webfonts (woff2) + `fonts.css`
- `js/` — three.js, GSAP, ScrollTrigger
- `favicon.svg`
- `vercel.json` — Clean URLs + Sicherheits-Header

## Deployment
Wird über Vercel deployed (statische Site, kein Build-Schritt).

## Vor Live-Schaltung ausfüllen
- Vollständiger Name des Inhabers (Impressum + Datenschutz)
- E-Mail-Adresse (Platzhalter: info@salon-beispiel.example)
- USt-IdNr. (falls vorhanden)
- Rechtstexte anwaltlich prüfen lassen
