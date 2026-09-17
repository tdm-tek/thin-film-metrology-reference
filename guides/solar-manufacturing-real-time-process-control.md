# Real-Time Process Control for Perovskite & Thin-Film Solar Lines

Reference notes on inline and in-situ metrology for perovskite and thin-film
production — thickness, photoluminescence (PL), transmittance/reflectance (T&R)
and AOI defect inspection. Maintained by the engineers at
**Suzhou TDM Technology Co., Ltd.**

> Condensed field notes. The full walk-through — process steps, chamber setup and
> decision criteria — is in our guide:
> [Unseen Battleground in Solar Manufacturing](https://www.tdm-tek.com/news/guide/solar-manufacturing-real-time-process-control) (Sep 2026).

## Why offline sampling fails on perovskite

Perovskite stacks have nanometer-level tolerances, and the two targets every
process step is judged against — field lifetime and power conversion efficiency —
both move with thickness, uniformity and defect density.

Offline sampling only sees the result, never the drift. Thickness drift, wet-film
edge effects, PL non-uniformity and scribing defects all become visible *after*
the film has dried, crystallized or been patterned — by then the scrap is locked
in. The gap that matters sits inside the chamber and on the coating line.

## Four measurement paths

| Path | Platform | What it measures | Key spec |
|---|---|---|---|
| Real-time chamber thickness | SE600X | Continuous thickness on perovskite / thin-film stacks | 5–1200 nm; direct optical measurement replaces QCM — no consumables, higher chamber uptime |
| Inline thickness + PL + T&R | SE600X Inline | Thickness, photoluminescence, transmittance / reflectance | 5–1200 nm; 10 Hz sampling; 31 measurement points vs 11 for a step profiler; no sample prep |
| Inline PL mapping + AOI | SE200x | Laser scribing defects, perovskite quality defects, dust | 3 μm/pixel; 100% full inspection with real-time process feedback |
| In-situ wet film | SE31 / SE310 | Wet-film thickness and reflectance heatmaps on slot-die coaters | ≤5 μm, non-contact, real-time — catches edge-thickening before drying |

## Choosing a path

| If you need to… | Start with |
|---|---|
| Monitor thickness continuously on perovskite / thin-film stacks (5–1200 nm) with PL and T&R | [SE600X](https://www.tdm-tek.com/products/inline/se600x-inline-perovskite-thickness-pl-and-t-and-r) |
| Run 100% inline PL mapping and AOI for scribing, material and dust defects | [SE200x](https://www.tdm-tek.com/products/inline/se200x-inline-pl-mapping-and-aoi-defect-inspection) |
| Catch wet-film edge effects during slot-die coating before drying | [SE31 / SE310](https://www.tdm-tek.com/products/in-situ) |
| Combine wet-film control with dried-film verification | SE31 / SE310 + SE600X |

## From data to decisions

Paired with process software, these sensors enable:

- **Closed-loop control** of deposition rate and thickness
- **Predictive maintenance** based on actual chamber and line conditions
- **Less scrap, shorter cycle times, lower total cost of ownership** through earlier detection

## FAQ

| Question | Short answer |
|---|---|
| Why is real-time metrology critical for perovskite manufacturing? | Nanometer-level tolerances — offline sampling misses drift, edge-thickening and PL non-uniformity until drying or patterning has already locked in the scrap |
| How does optical thickness monitoring compare to QCM? | It measures the film directly instead of inferring mass on a quartz crystal — better accuracy on multi-layer stacks, no consumables, higher chamber uptime |
| What does SE600X measure on perovskite films? | Thickness, PL and T&R in the 5–1200 nm range, at 10 Hz with 31 measurement points, without sample preparation |
| What defects can SE200x catch inline? | Laser scribing defects, perovskite quality defects and dust — PL mapping plus AOI at 3 μm/pixel, 100% full inspection |
| Why measure wet film thickness before drying? | Wet-film edge-thickening becomes permanent after drying and crystallization; real-time ≤5 μm measurement lets operators adjust the coater first |

## Related

- [In Situ Thin Film Monitoring — Real-Time Metrology Guide](https://www.tdm-tek.com/news/guide/in-situ-thin-film-monitoring)
- [AOI for Solar Cell Defect Detection](https://www.tdm-tek.com/news/guide/aoi-solar-cell-defect-detection)
- [SE69 Hyperspectral One Scan Defect Mapping](https://www.tdm-tek.com/news/guide/se69-hyperspectral-one-scan-defect-mapping)
- [Inkjet Printing for Perovskite Manufacturing](https://www.tdm-tek.com/news/guide/inkjet-printing-perovskite-solar-cell-manufacturing)
