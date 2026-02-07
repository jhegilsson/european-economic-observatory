# Iceland vs Europe — European Economic Observatory

An interactive dashboard comparing Iceland's economic indicators with European countries. Built with React and Recharts.

**[View Live Dashboard →](https://YOUR-USERNAME.github.io/europe-dashboard/)**

---

## What's Included

| Tab | Description |
|-----|-------------|
| **Dashboard** | Overview cards: policy rates, 10Y yields, inflation, GDP growth |
| **Macro** | GDP vs inflation scatter, policy rate vs inflation |
| **Employment** | Unemployment rates (total & youth) across 30+ countries |
| **Gov't Debt** | Debt-to-GDP ratios with Maastricht 60% ceiling reference |
| **GDP Growth** | Historical GDP growth (2019–2025) for select economies |
| **Inflation** | HICP/CPI trends (2019–2025) |
| **Housing Costs** | Housing affordability vs GDP per capita |
| **Policy Rates** | Central bank rates across Europe |
| **10Y Yields** | Government bond yields by country grouping |
| **Yield Curves** | Sovereign yield curves (3M to 30Y) |
| **Rate History** | Policy rate evolution since 2020 |

---

## Data Sources

- **Central Banks**: ECB, Seðlabanki Íslands, BoE, Norges Bank, Riksbank, SNB, NBP, MNB, ČNB, BNR, Danmarks Nationalbank
- **Macro Data**: Eurostat, OECD, IMF World Economic Outlook
- **Government Debt**: Eurostat EDP notification (Oct 2025), IMF
- **Bond Yields**: ECB Statistical Data Warehouse, national sources

Data as of **February 2026**. This is a static snapshot — data is not automatically updated.

---

## Countries Covered

**Eurozone (21)**: Germany, France, Italy, Spain, Netherlands, Belgium, Austria, Finland, Ireland, Portugal, Greece, Luxembourg, Slovenia, Slovakia, Estonia, Latvia, Lithuania, Malta, Cyprus, Croatia, Bulgaria

**EU non-Euro**: Poland, Hungary, Romania, Czech Republic, Denmark, Sweden

**Non-EU**: Iceland, Norway, UK, Switzerland

---

## Technical Details

- **Single HTML file** — no build step required
- **Dependencies** (loaded via CDN):
  - React 18
  - Recharts 2.12
  - Babel Standalone (for JSX transformation)
  - Google Fonts (DM Sans, Space Mono)

---

## Local Development

Just open `index.html` in a browser. No server needed.

For live reload during development:
```bash
npx serve .
```

---

## License

MIT — free to use, modify, and distribute.

---

## Author

[Jón Helgi Egilsson](https://jonegilsson.com)
