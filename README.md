# Anycubic Resin Matrix

A single-page, sortable comparison of every resin Anycubic currently sells, built from Anycubic's own technical data sheets.

**Live page:** https://raysantos.github.io/anycubic-resin-matrix/

## What's in it

17 resins across six families (Standard, Detail, ABS-Like, Water-Wash, Tough, Specialty), compared on:

| Group | Properties |
|---|---|
| Mechanical | Shore D hardness, tensile strength, elongation at break, Izod impact, flexural strength, flexural modulus, Young's modulus |
| Physical | Volume shrinkage, viscosity (25 °C), density |
| Printing | Normal exposure time, wash method (IPA or water), odor |
| Cost | 1 kg price, bulk $/kg |

Click any column header to sort, and hover (or tap) a resin's name to see what it's good for. Filter by family, water-washable only, or hide sold-out resins. ★ marks the best value in each column.

## Data notes

- All figures come from the Specification tab of each product page on [store.anycubic.com](https://store.anycubic.com/collections/uv-resin), checked October 2, 2026. Anycubic notes results vary with printer, post-cure and test setup.
- Anycubic's pages swap two labels: their "Bending Modulus" (~15–70 MPa) is really flexural strength, and "Bending Strength" (~350–3,300 MPa) is really flexural modulus. This page uses the corrected names.
- Where a collection listing and a product's spec sheet disagreed, the spec sheet value is used.
- Prices are the US store's 1 kg price on the date above and change often.

## Updating the data

All resin data lives in the `R` array near the top of the `<script>` in `index.html`. Each entry uses `[low, high]` ranges; add or edit a row and the sorting and ★ leaders recalculate automatically.

## Styling

Matches the Anycubic store: their #005AFF blue, pill-shaped controls, light-grey panels, and the MiSans Latin typeface with Inter as fallback (Inter is what loads unless MiSans is installed locally).

Not affiliated with Anycubic. Product names belong to their owner.
