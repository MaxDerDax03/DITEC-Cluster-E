# Ballpark figures for your business case

For the intermediate presentation (M3, Monday 19.10) · handed out on 12.10 · status 13.09.2026

**Use these figures, or use your own and say why.** Every figure carries its source type:
- **[official]** statistics office or collective agreement
- **[integrator]** reseller list price
- **[IFR]** International Federation of Robotics
- **[commercial]** paid market report
- **[estimate]** assumption you should check

Details and links:
- [../staff_shortage_and_wages_dach.md](../staff_shortage_and_wages_dach.md) – wages
- [market_figures_and_prices.md](market_figures_and_prices.md) – prices and market growth

---

## 1 · What a staff hour costs

| Figure | Value | Source |
|---|---|---|
| Minimum wage, unskilled service staff, Switzerland 2026 | CHF 3,713 per month × 13 = **CHF 48,269 per year** gross | [official] L-GAV 2026, category Ia |
| Employer contributions (AHV/IV/EO, ALV, BVG, accident insurance, family allowance) | roughly **+15–20 %** → about CHF 56,000 per full-time job | [estimate] – check with a payroll source |
| Paid working time | 42 h per week, about 1,900 working hours per year after holidays | [official] L-GAV Art. 15 · [estimate] for the yearly hours |
| **Cost per staff hour (Switzerland, minimum wage)** | **≈ CHF 29** | [estimate] own calculation from the lines above |
| Median pay in Lucerne hospitality | CHF 4,900 per month – trained staff cost more than the minimum | [official] LUSTAT 2026 |
| Germany | €13.90 per hour statutory minimum (2027: €14.60) | [official] |
| Austria | ≈ €2,026 per month (collective agreement Vienna, service assistant) | [official] WKO |

## 2 · What the robot costs

List prices from resellers, USD, excluding tax, shipping, installation and training. RaaS = robot-as-a-service, a monthly fee over 36 months.

| Robot | Purchase | RaaS per month | Source |
|---|---|---|---|
| Pudu BellaBot | USD 14,500 | USD 409 | [integrator] RobotLAB |
| Pudu BellaBot Pro | USD 16,000 | USD 399 | [integrator] RobotLAB |
| Pudu BellaBot, Germany | EUR 14,990 incl. VAT | – | [integrator] Alpha11 |
| Pudu BellaBot, Switzerland | on request | on request | [integrator] Sebotics, Horw – ask them |
| Bear Robotics Servi | USD 9,990–11,990 (the same page shows both) | USD 279 | [integrator] RobotLAB |
| Bear Robotics Servi+ | USD 13,990 | USD 479 | [integrator] RobotLAB |
| Keenon T10 | USD 13,000–18,400 (varies by page) | USD 519 | [integrator] RobotLAB |
| Relay (hotel delivery) | subscription only | about USD 75,000 over 3 years, service included | press report quoting the CEO, 2023 |

**Costs that are not in the price** – estimate them and justify, ideally from an interview or a case source:
- mapping, table set-up, Wi-Fi coverage, a dock location;
- staff training hours;
- maintenance, repairs, spare parts, updates (check what a RaaS contract includes);
- downtime – and who does the work while the robot is down;
- staff time the robot needs: loading the tray, resets, recharging, re-mapping after a re-layout.

## 3 · How fast the market grows

| Series (units sold worldwide) | 2022 | 2024 | CAGR 2022–2024 | Source |
|---|---|---|---|---|
| Professional service robots, total | 158,000 | ≈ 199,000 | ≈ 12 % per year | [IFR] World Robotics 2023 and 2025 |
| Hospitality robots | 24,500 | 42,000 | ≈ 31 % per year – but **−11 % in 2024** | [IFR] |

- **Formula:** CAGR = (end ÷ start)^(1 ÷ years) − 1. A two-point CAGR hides the path in between.
- **Revisions:** IFR revises earlier years, so always name the edition. The 2026 edition appears on 24.09.2026.
- **Paid market reports** state 17–24 % per year for "restaurant" or "hospitality" robots, with very different market definitions [commercial]. Do not mix them with IFR unit figures.

## 4 · Worked example – illustrative only

Assumptions to replace with your own:
- BellaBot on RaaS;
- USD 1 = CHF 0.85 (use the current rate and date it);
- 360 operating days per year;
- CHF 29 per staff hour.

| Item | Calculation | Per year |
|---|---|---|
| RaaS fee | 409 × 12 = USD 4,908 × 0.85 | CHF 4,170 |
| Staff time the robot needs | 20 minutes per day × 360 days × CHF 29 | CHF 3,480 |
| **Robot cost per year** (without integration, repairs, downtime) | | **CHF 7,650** |
| Walking time saved – pessimistic | 0.5 h per day × 360 × CHF 29 | CHF 5,220 |
| Walking time saved – optimistic | 2 h per day × 360 × CHF 29 | CHF 20,880 |
| **Break-even** | 7,650 ÷ (360 × 29) | **≈ 45 minutes of walking saved per day** |

What this example leaves out – and your analysis should not:
- Saved walking time is only worth money if staffing or overtime actually changes, or if the time goes into guests (table turns, sales).
- There is a revenue side (faster service, novelty, retention of staff) and a risk side (low acceptance → low utilisation, staff turnover).
- Swiss purchase prices, installation and repairs are missing – ask Sebotics or an operator.

## 5 · In the intermediate presentation

- Show your calculation with a **range** (pessimistic / expected / optimistic), not one number.
- Name the **two assumptions that drive the result** and where they come from.
- If you use different figures, one sentence per figure: source, date, why it fits your deployment or the HSLU cafeteria better.
