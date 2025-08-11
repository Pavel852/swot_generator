# SWOT Generator (v1.5.4)

**Author:** PB

## English

### Overview
A single-file HTML app that generates a polished **SWOT analysis** image (PNG) with an optional frame and graph. It runs entirely in your browser—no build or install required.

### Features
- **Languages:** English 🇬🇧, Czech 🇨🇿, or **both at once** on the canvas.
- **Canvas export:** Render and **download PNG**.
- **Title & company line:** Large “SWOT ANALYSIS / ANALÝZA” header; company label near the top.
- **Optional graph:**
  - Radar polygon from S/W/O/T counts.
  - Red **direction vector** (prevailing trend from S/W/O/T balance).
  - Values box with counts.
  - **Blue strategy block** around x≈800, y≈1500 with percentages for **SO/ST/WT/WO** and **N (neutral)**.
- **Fast input:** Type and press **Enter**, click sample **chips**, or **drag & drop** chips into S/W/O/T panels.
- **Single file:** Pure HTML/CSS/JS with an embedded template image.

### Strategy percentages
Computed as weights and normalized to 100%:
- `SO = S * O`
- `ST = S * T`
- `WT = W * T`
- `WO = W * O`
- `N = 100%` only if there are **no** items at all.

Labels adapt to the language:
- EN: “Company strategy”, `SO=aggresive`, `ST=competention`, `WT=defenzive`, `WO=conservative`, `N=neutral`
- CZ: „Strategie společnosti“, `SO=agresivní`, `ST=soutěživá`, `WT=obraná`, `WO=opatrná`, `N=neutrální`
- BOTH: combined labels

### How to use
1. Open `swot_generator_v1_5_4.html` in a modern browser.
2. Fill **Company**, choose **Language**, toggle **with frame** / **with graph**.
3. Add S/W/O/T items (chips, type+Enter, or drag & drop).
4. Click **Render** to refresh the canvas.
5. Click **Download PNG**.

> If download is blocked when opened directly from disk (`file://`), run a tiny local server, e.g.:
- `python -m http.server`
- or `npx http-server`

### Files
- `swot_generator_v1_5_4.html` — main app

### License
Add your preferred license (e.g., MIT) in `LICENSE`.

---

## Čeština

**Autor:** PB

### Přehled
Jednosouborová HTML aplikace pro tvorbu **SWOT analýzy** do PNG. Běží přímo v prohlížeči – bez instalace a buildu.

### Funkce
- **Jazyky:** Anglicky 🇬🇧, Česky 🇨🇿, nebo **obojí současně** na výstupu.
- **Export:** Vykreslí plátno a umožní **stáhnout PNG**.
- **Nadpis & společnost:** Velký titul „SWOT ANALYSIS / ANALÝZA“; název společnosti u horního okraje.
- **Volitelný graf:**
  - Radarový polygon z počtů S/W/O/T.
  - Červený **vektor směru** (převažující trend).
  - Box s hodnotami.
  - **Modrý blok strategií** okolo x≈800, y≈1500 se SO/ST/WT/WO a **N (neutrální)** v procentech.
- **Rychlé zadávání:** psaní + Enter, klik na **šablonové chipy**, nebo **drag & drop**.
- **Vše v jednom souboru:** čisté HTML/CSS/JS s vloženou šablonou.

### Procenta strategií
Výpočty z vah, normalizace na 100 %:
- `SO = S * O`
- `ST = S * T`
- `WT = W * T`
- `WO = W * O`
- `N = 100 %` pouze když nejsou žádné položky.

Popisky podle jazyka:
- EN: “Company strategy”, `SO=aggresive`, `ST=competention`, `WT=defenzive`, `WO=conservative`, `N=neutral`
- CZ: „Strategie společnosti“, `SO=agresivní`, `ST=soutěživá`, `WT=obraná`, `WO=opatrná`, `N=neutrální`
- OBOJÍ: kombinace

### Použití
1. Otevři `swot_generator_v1_5_4.html` v moderním prohlížeči.
2. Vyplň **Společnost**, zvol **Jazyk**, přepni **s rámečkem** / **s grafem**.
3. Přidej položky do S/W/O/T (chip, psaní+Enter, nebo přetažení).
4. Klikni **Vykreslit**.
5. Klikni **Stáhnout PNG**.

> Pokud stažení blokuje prohlížeč při otevření z disku (`file://`), spusť malý lokální server, např.:
- `python -m http.server`
- nebo `npx http-server`

### Soubory
- `swot_generator_v1_5_4.html` — hlavní aplikace

### Licence
Doplňte vybranou licenci (např. MIT) do `LICENSE`.
