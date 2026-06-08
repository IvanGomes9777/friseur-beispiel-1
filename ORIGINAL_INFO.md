# Original-Daten (NICHT deployen)

Diese Datei enthält die ursprünglichen Inhaberdaten der Seite.
Sie ist über `.vercelignore` vom Live-Deployment ausgeschlossen.

**Zweck:** Falls der ursprünglich vorgesehene Käufer die Seite doch
übernimmt, können die Originalwerte 1:1 zurück eingesetzt werden.
Bis dahin laufen alle Texte mit neutralen Beispieldaten, damit die
Seite frei für andere Interessenten bleibt.

---

## Inhaber / Unternehmen (Original)

| Feld | Originalwert | Aktueller Platzhalter |
|---|---|---|
| Unternehmensname | Friseursalon Mauro Ricardo | Salon Beispiel |
| Kurz-/Logoname | Mauro Ricardo | Salon Beispiel |
| Tagline | La Bellezza Italiana · Münster / La bellezza italiana · Münster | La Bellezza Italiana · Musterstadt / La bellezza italiana · Musterstadt |
| Inhaber (Person) | Mauro Ricardo | Max Mustermann |
| Straße | Idenbrockplatz 5A (bzw. Idenbrockpl. 5A) | Musterstraße 1 |
| PLZ + Ort | 48159 Münster | 12345 Musterstadt |
| Stadt (Kurzform) | Münster | Musterstadt |
| Telefon (Anzeige) | 0251 1624493 | 01234 567890 |
| Telefon (tel:-Link) | 02511624493 | 01234567890 |
| E-Mail | info@mauro-ricardo.de | info@salon-beispiel.example |
| Domain (im README) | mauro-ricardo.de | salon-beispiel.example |
| Zuständige Kammer | Handwerkskammer Münster, Bismarckallee 1, 48151 Münster | Handwerkskammer [Ort einfügen], [Straße einfügen], [PLZ Ort einfügen] |
| Aufsichtsbehörde Datenschutz | LDI NRW (NRW) | Zuständige Landesaufsichtsbehörde [Bundesland einfügen] |
| Google-Maps-Query | Idenbrockplatz+5A+48159+Munster | Musterstrasse+1+12345+Musterstadt |
| Copyright-Jahr | © 2025 | © 2025 (unverändert) |

## Originale Kundenbewertungen / Namen (im Frontend)

Die Rezensionen-Sektion zeigte echte Google-Namen. Diese wurden durch
neutrale Beispiel-Reviews ersetzt:

| Original-Name | Original-Text (Auszug) | Platzhalter-Name |
|---|---|---|
| Di Piazza Uomo E Donna | „War heute wieder dort und bin absolut begeistert. Super Service, entspannte Atmosphäre …" | Anna M. |
| Horst Dübner | „Immer freundlich und kompetent! Gehe gerne dorthin, Termine werden eingehalten …" | Thomas K. |
| Lenchen K. | „Ich war dort zum Spitzen schneiden und wurde von einer sehr freundlichen jungen Frau empfangen …" | Sabine L. |

Die Texte der Reviews wurden bewusst leicht generalisiert, damit sie
nicht 1:1 als O-Ton einer real existierenden Person rückverfolgbar sind.

## Original-Texte mit Ortsbezug (zur Wiederherstellung)

- `index.html` Über-uns Headline:
  - Original: „Italienische Kunst im Herzen von <em>Münster</em>"
  - Platzhalter: „Italienische Kunst im Herzen von <em>Musterstadt</em>"
- `index.html` Über-uns Text:
  - Original-Satz: „… ein vertrauensvoller Partner für Schönheit und Stil in Münster zu sein."
  - Platzhalter: „… ein vertrauensvoller Partner für Schönheit und Stil in Musterstadt zu sein."
- `index.html` Location-Lead:
  - Original: „Wir befinden uns am Idenbrockplatz in Münster — gut erreichbar mit Bus und Auto."
  - Platzhalter: „Wir befinden uns in zentraler Lage in Musterstadt — gut erreichbar mit Bus und Auto."
- `index.html` Über-uns Einleitung:
  - Original: „Willkommen bei Mauro Ricardo — einem Ort, an dem die reiche Friseurkunst Italiens auf die pulsierende Kultur Münsters trifft."
  - Platzhalter: „Willkommen in unserem Salon — einem Ort, an dem die reiche Friseurkunst Italiens auf die pulsierende Kultur Musterstadts trifft."

## Wiederherstellung

Zum Zurücksetzen auf die Originaldaten einfach in allen Dateien
(`index.html`, `impressum.html`, `datenschutz.html`, `agb.html`,
`README.md`) die rechte Spalte oben wieder durch die linke Spalte ersetzen.
Suchreihenfolge empfohlen: Telefon (tel:-Link), Telefon (Anzeige),
PLZ+Ort, Straße, E-Mail, Inhaber, Unternehmensname, Stadt, Kammer,
Aufsichtsbehörde, Maps-Query, Review-Namen.
