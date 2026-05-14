# Immo-Tool — Investitions-Cockpit für Immobilien

Standalone-HTML-Tool zur Profitabilitätsanalyse von Immobilieninvestments.

**Live:** https://dmzickler-netizen.github.io/immo-tool/

## Funktionen

- **Objekt & Kauf** — Wohnfläche, Kaufpreis, Nebenkosten mit Bundesland-Auto-Grunderwerbsteuer
- **Grund & Boden** — Vereinfachte BMF-Methodik (Arbeitshilfe zur Kaufpreisaufteilung): Bodenrichtwert × Fläche × Miteigentumsanteil + NHK-basierter Gebäudewert → AfA-Aufteilung
- **Miete & Bewirtschaftung** — Kaltmiete, Hausgeld umlagefähig vs. nicht umlagefähig, Rücklagen, Mietausfall, Prognose-Annahmen
- **Sanierung & Mietpreisbremse** — Modernisierungs-/Energetik-/Instandhaltungs-Positionen mit ⅓-Schwellen-Check (BGH VIII ZR 7/19), § 559 BGB Modernisierungsumlage, § 6 EStG 15 %-Grenze
- **Bank** — Bis zu 2 Darlehen, Annuität, Restschuld-Tabelle, Volltilgungszeitpunkt
- **Kennzahlen** — Brutto-/Nettomietrendite, Faktor, Cashflow operativ + nach Steuern, EK-Rendite
- **30-Jahres-Verlauf** — Hochrechnung mit Miet-/Kosten-/Wertsteigerung, SVG-Chart

Reines HTML/CSS/Vanilla-JS, keine Abhängigkeiten. Daten werden in `localStorage` gespeichert; Export/Import als JSON.

## Disclaimer

Keine Steuer-, Rechts- oder Finanzberatung. Ergebnisse sind orientierende Kalkulationen.
Mietpreisbremse-Hebel: keine Garantie der gerichtlichen Anerkennung.
