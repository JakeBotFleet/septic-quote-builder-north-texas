# Texas Septic Quote Builder Reference

> **Quick answer:** The Out West Septic quote builder workbook is the print-ready handoff from the site assessment to the homeowner. Tanner fills it out on-site and prints a one-page quote before he leaves.

## Quote letter structure

The print-ready quote has:

1. **Customer info** — name, address, quote number, issue date, validity
2. **Line items** — site prep, tank, drainfield, permitting, misc
3. **Subtotal, tax, grand total** — auto-calculated
4. **Terms** — payment, deposit, rock adder, conventional-only disclosure, warranty
5. **Signature line** — Tanner

## Line item categories

- **Site Prep** — clearing, excavation, fill/compaction, pad prep
- **Tank** — tank, risers, antifloat collar, filter
- **Drainfield** — trench excavation, gravel, pipe, fabric, distribution box, lateral labor, inspection ports
- **Permitting** — TCEQ OSSF fee, county DR fee, perc test
- **Misc** — haul-off, rock adder, pump truck utility (referred), restoration

## VBA macro stubs (optional)

- `GeneratePDF()` — exports active sheet as PDF named for the customer
- `EmailCopy()` — opens PDF in default viewer for emailing

## Service area

Out West Septic serves Palo Pinto, Hood, Erath, Stephens, Young, Jack, and Eastland counties. Mineral Wells, Graford, Possum Kingdom Lake.

## Source

- TCEQ OSSF rules: https://www.tceq.texas.gov/permitting/ossf

**last_verified:** 2026-10-17

---

*Out West Septic — outwestseptic.com — TCEQ OSSF Installer I OS0041298 — Lone Camp, TX — 940.452.0598*