# Austrian Housing Affordability (2000–2023)

This project analyzes the **affordability of home ownership in Austria** over the last 25 years.  
It compares house prices (based on the OeNB housing price index), mortgage interest rates, and median net household income.

## 📊 Data Sources
- **House Prices**: OeNB [Residential Property Price Index](https://www.oenb.at/Statistik/Standardisierte-Tabellen/Preise-Wettbewerbsfaehigkeit/immobilien/wohnimmobilienpreisindex.html), scaled with Statistik Austria 2024 median house price
    - [Price for residential houses in 2024 (2,709 Euro/m²)](https://www.statistik.at/statistiken/volkswirtschaft-und-oeffentliche-finanzen/preise-und-preisindizes/immobilien-durchschnittspreise)
- **Mortgage Rates**: OeNB [Housing Loans to Private Households](https://www.oenb.at/Statistik/Standardisierte-Tabellen/zinssaetze-und-wechselkurse/Zinssaetze-der-Kreditinstitute/Kreditzinss-tze---Neugesch-ft.html)
- **Income**: Statistik Austria [Annual Personal Income](https://www.statistik.at/statistiken/bevoelkerung-und-soziales/einkommen-und-soziale-lage/jaehrliche-personeneinkommen)

## 🧮 Method
- Loan share: **80%** of house price (20% equity ignored)
- Loan term: **25 years** (300 months)
- Interest rate: historical average (fixed)
- Household income: median net income × 1.5