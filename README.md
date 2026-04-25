# Netrivo

Statisk prototype for Netrivo, med forsida, prosjektstarter og fleire demoar som viser ulike nivå av nettsider:

- **Enkel**: ryddige og direkte nettsider for små verksemder.
- **Standard**: meir struktur, tillit og innhaldsdybde.
- **Premium**: meir særpreg, visuell kontroll og høgare opplevd verdi.

## Struktur

- `index.html` er hovudsida og fungerer som inngang til demoane.
- `prosjektstarter.html` er ein interaktiv brief/prosjektstarter som foreslår nivå og lagar eit utgangspunkt for vidare dialog.
- `netrivo-enkel-*.html`, `netrivo-standard-*.html` og `netrivo-premium-*.html` er desktop-demoar.
- `netrivo-mobil-*.html` er mobilvariantar.
- `assets/` inneheld delte statiske ressursar.

## Køyre lokalt

Dette er reine statiske filer utan byggesteg. Opne `index.html` direkte i nettlesaren, eller køyr ein enkel lokal server frå repo-rota:

```bash
python3 -m http.server 8000
```

Deretter kan sida opnast på `http://localhost:8000`.

## Kvalitetssikring

Det finst førebels ikkje automatisk test-, lint- eller byggoppsett i repoet. Ved vidare utvikling bør lenkesjekk og enkle smoke-testar vurderast, spesielt for demo- og mobilvariantane.