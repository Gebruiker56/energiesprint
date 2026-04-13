# EnergieSprint ⚡

**Privacy-first mobiele energie-app** — win van jezelf, geen server, geen account.

> Prototype voor gedachtenvorming — gebouwd met Claude (Anthropic)

## Live demo

Sla de link op zodra GitHub Pages actief is:
`https://JOUWGEBRUIKERSNAAM.github.io/energiesprint/`

---

## In 5 minuten online

### Stap 1 — GitHub account
Ga naar [github.com](https://github.com) en maak een gratis account aan (of log in).

### Stap 2 — Nieuwe repository
1. Klik op **"New repository"**
2. Naam: `energiesprint`
3. Zet op **Public**
4. Klik **"Create repository"**

### Stap 3 — Bestanden uploaden
1. Klik **"uploading an existing file"**
2. Sleep `index.html` en `README.md` naar het uploadvenster
3. Klik **"Commit changes"**

### Stap 4 — GitHub Pages aanzetten
1. Ga naar **Settings** → **Pages**
2. Bij "Source": kies **Deploy from a branch**
3. Branch: **main** / **(root)**
4. Klik **Save**

Na ~60 seconden is de app live op:
`https://JOUWGEBRUIKERSNAAM.github.io/energiesprint/`

---

## Wat zit erin

| Scherm | Functie |
|--------|---------|
| Home | Score, persoonlijke records, verbruik per categorie |
| Tijdlijn | Jij vs. jezelf — grafiek + maandoverzicht |
| Invoeren | Sliders voor elektra, gas, zonnepanelen + apparaatmetingen |
| Uitdagingen | Persoonlijke doelen + achievements |
| Tips | Bespaartips met maandelijkse besparing |

## Privacy & techniek
- Alle data opgeslagen in `localStorage` van de browser
- Geen server, geen database, geen account
- Volledig offline bruikbaar na eerste bezoek
- Één HTML-bestand — geen dependencies te installeren

## Ideeën voor doorontwikkeling
- [ ] Export naar CSV / PDF maandrapport
- [ ] Slimme meter koppeling (P1 poort)
- [ ] Energietarieven invoeren → kosten berekenen
- [ ] Doelen stellen per maand
- [ ] Push notificaties voor maandelijkse herinnering
- [ ] Vergelijking met gemiddelde vergelijkbaar huishouden (anoniem benchmark)
- [ ] PWA manifest voor echte app-installatie
- [ ] Meerdere huishoudens per apparaat (gezinsleden)

---

*Gebouwd als prototype — feedback welkom*
