# EnergieSprint ⚡

**Privacy-first mobiele energie-app** — win van jezelf, geen server, geen account.

> Prototype voor gedachtenvorming — gebouwd met Claude (Anthropic)

---

## Live demo

Na GitHub Pages activeren:
`https://JOUWGEBRUIKERSNAAM.github.io/energiesprint/`

---

## In 5 minuten online via GitHub Pages

### Stap 1 — GitHub account
Ga naar [github.com](https://github.com) en maak een gratis account aan (of log in).

### Stap 2 — Nieuwe repository
1. Klik **"New repository"**
2. Naam: `energiesprint`
3. Zet op **Public**
4. Klik **"Create repository"**

### Stap 3 — Bestanden uploaden
1. Klik **"uploading an existing file"**
2. Sleep `index.html` en `README.md` naar het uploadvenster
3. Hernoem het HTML-bestand naar `index.html` vóór uploaden
4. Klik **"Commit changes"**

### Stap 4 — GitHub Pages aanzetten
1. Ga naar **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main / (root)**
4. Klik **Save**

Na ~60 seconden live op `https://JOUWGEBRUIKERSNAAM.github.io/energiesprint/`

---

## Verwarmingstypes

De app ondersteunt vier situaties:

| Type | Elektra | Gas | Bijzonder |
|------|---------|-----|-----------|
| Gas (cv-ketel) | 250–500 kWh/mnd | 15–150 m³/mnd | Klassiek profiel |
| Warmtepomp | 600–2000 kWh/mnd | 0 m³ | COP-score bijhouden |
| Hybride | 300–700 kWh/mnd | 0–60 m³/mnd | Combinatie WP + gas |
| Stadsverwarming | 200–450 kWh/mnd | 0 m³ | Geen gas, geen WP |

Score en records passen zich automatisch aan op het gekozen type.

---

## Wat zit erin

| Scherm | Functie |
|--------|---------|
| Home | Score, persoonlijke records, verbruik per categorie |
| Tijdlijn | Scoregrafiek + alle maanden — jij vs. jezelf |
| Invoeren | Sliders elektra, gas/COP, zonnepanelen + apparaatmetingen |
| Doel | Persoonlijke uitdagingen + achievements |
| Over | Kernprincipes, ideeënlijst, reset |

---

## Privacy & techniek

- Alle data in `localStorage` van de browser — verlaat het apparaat nooit
- Geen server, geen database, geen account, geen cookies
- Volledig offline bruikbaar na eerste bezoek
- Eén HTML-bestand — niets te installeren

---

## Ideeën voor doorontwikkeling

- [ ] P1-poort koppeling — slimme meter automatisch uitlezen
- [ ] Energietarieven invoeren → kosten per maand berekenen
- [ ] Maandrapport exporteren als PDF
- [ ] Push-notificatie: maandelijkse invoerherinnering
- [ ] CO₂-uitstoot naast kWh en m³
- [ ] Apparatenbibliotheek met standaard wattages per merk/type
- [ ] Anonieme benchmark met vergelijkbaar huishouden
- [ ] Meerdere profielen per apparaat (bijv. vakantiewoning)
- [ ] PWA manifest voor echte app-installatie met icoon
- [ ] Exporteren/importeren van data (backup)

---

*Prototype versie 0.2 — feedback welkom*  
*Gebouwd met Claude (Anthropic)*
