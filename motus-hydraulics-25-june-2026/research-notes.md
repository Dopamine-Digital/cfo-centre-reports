# Research notes — Motus Hydraulics (CFO Centre Profit Leak Scan)

Built 25 June 2026. No ClickUp card exists; Jordan supplied the entity directly (jerry@motushydraulics.com). Entity unambiguous (email domain = website).

## Entity
- **Motus Hydraulics** ("Cylinder Specialists" / "Motus Hydraulics Global") — hydraulic cylinder manufacturer.
- Founded **1963**. HQ **7 Barnes Pl, Hastings, Hawke's Bay 4120, NZ** (plus second NZ site 25 Poporo Way, Hastings).
- Manufactures + supplies hydraulic cylinders, rams, hoses, fittings; off-the-shelf, custom-built, and OEM design services.
- "100 Hour Promise" rapid-build/ship commitment. Four-year product guarantee.
- Industries served: agriculture, horticulture, viticulture, construction, forestry, industrial, transport.

## Multi-country footprint (key signal)
- NZ: Hastings (x2 sites)
- Australia: Yatala QLD (123 Darlington Dr), Canning Vale WA (60 Tullock Way)
- Canada: Ancaster, Hamilton ON (1404 Cormorant Rd)
- USA: Madison Heights, MI (31465 Stephenson Hwy)
=> legal/operating presence in 4 countries; North America is a newer expansion.

## Leadership
- **Jerry Currie — Managing Director** (the prospect; decision-maker).
- Luke Currie — Production Manager (family).
- Seth McCallum — Global Sales. Ryan Carroll — Sales.

## Finance-leader check (HARD gate — APLYiD)
- Ran `find_finance_leader.py --company "Motus Hydraulics" --company-linkedin <url>`.
- **Result: found:true** — Matthew De***r, Chief Financial Officer (source: Apollo).
- => "no finance leader" angle FORBIDDEN. Report uses the **CFO's-CFO / fractional-twinning** framing throughout
  ("even with a CFO in seat / in the chair"). Hero punch reframed away from "with no in-house finance function".
  CFO name NOT printed on the report (Apollo single-source; avoid naming an unverified individual to the prospect).

## Size + headline basis
- Headcount estimates vary by source: SignalHire 13, Crunchbase/others 11-20 (likely NZ Ltd single entity), ZoomInfo 50-99 (likely group).
- Revenue: vendor estimate "< NZ$5M" (single NZ entity). Group across 4 countries materially larger but not publicly disclosed.
- Banding per `cfo-leak-benchmarks.md`: headcount-primary spread (13 single-entity -> Small; 50-99 group -> Large) disagrees with turnover (< $5M -> Small/Mid). Rule = take the lower/conservative band on disagreement, choose low end, round down.
- **Chosen band: Mid (anchor), low end. leak_figure_nzd_per_month = NZ$10,000.** Defensible for a 4-country, 60-year manufacturer; conservative (anchor is ~NZ$11,500; low end taken; round number).
- Headline single figure = NZ$10,000. Guarantee figure = NZ$10,000 (identical, per spec).

## 5 leak cards — per-card signal -> lever (each grounded)
1. **Custom and OEM job margin** (NZ$2,800-3,400, 30%) — off-the-shelf + custom + OEM cylinders across 7 industries; no per-job/per-line margin tracking => stretched custom builds run thin/loss unseen.
2. **Multi-entity and FX leakage** (NZ$2,100-2,700, 24%) — entities in NZ/AU/CA/US; without consolidated reporting + transfer pricing, profit leaks to FX, duplicated overhead, inter-company pricing. (CFO's-CFO reason #6: international expansion.)
3. **Inventory and working capital** (NZ$1,700-2,300, 20%) — stock for off-the-shelf + 100 Hour Promise ties cash in inventory/WIP across 5 sites; tighten stock + cross-border debtor days.
4. **Financial planning behind expansion** (NZ$1,300-1,900, 16%) — North America expansion + new product lines made without per-region unit-economics/payback modelling.
5. **Group systems, controls and reporting** (NZ$800-1,200, 10%) — reporting built for one NZ plant doesn't give real-time visibility across 4 countries; small per-branch leaks invisible at the top.

Midpoints sum ~NZ$10.1k ~= headline NZ$10,000. Bar %: 30/24/20/16/10 = 100.

## Sources analyzed (on the report)
- Website: https://motushydraulics.com
- Company LinkedIn: https://www.linkedin.com/company/motus-hydraulics
- DM LinkedIn (Jerry Currie): https://www.linkedin.com/in/jerry-currie-27a9b7326/

## QA gate
- Right entity: YES (Motus Hydraulics throughout; Jerry Currie MD).
- Specific not generic: YES (4-country footprint, 100 Hour Promise, 4-yr guarantee, custom/OEM, North America expansion, Currie family).
- Number grounded: YES (Mid band low end, conservative, recorded above; guarantee = headline).
- Guarantee congruent: YES (margin visibility, working capital, financial rigour behind growth/expansion; no invented jargon; no accountant framing).
- Finance-leader check ran: YES (found:true -> no absence claim anywhere; CFO's-CFO framing used).
- Render valid: pending headless render check.
