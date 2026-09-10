# Thin Film Metrology — Quick Reference Notes

Field notes and quick-reference tables for thin film thickness measurement and
PV module testing, maintained by the engineers at **Suzhou TDM Technology Co., Ltd.**

> These notes are the "cheat sheet" companion to our [full measurement guides](https://www.tdm-tek.com/news/) —
> for step-by-step procedures, see the guides on our website.

## Common Film Stacks & Suggested Methods

| Application | Typical Film(s) | Primary Method | Notes |
|---|---|---|---|
| Anti-reflection coating | SiNₓ on textured Si | Reflectometry or Ellipsometry | Textured surface requires advanced modeling |
| TCO / transparent conductor | ITO, AZO | Ellipsometry | n/k needed for sheet resistance correlation |
| Wet coating (roll-to-roll) | Functional inks | **In-situ wet-film monitoring** | Measure from coating head, before drying |
| Passivation layer | AlOₓ, SiO₂ | Ellipsometry | Sub-nm precision required |
| Encapsulant | EVA / POE | Reflectometry | Thick film, low precision needed |

## Technique Cheat Sheet

| If you need… | Use… | Why |
|---|---|---|
| Thickness + n/k of multi-layer stack | Spectroscopic Ellipsometry | Two parameters (Ψ, Δ) across spectrum |
| Fast inline thickness of single layer | Reflectometry | Seconds per measurement |
| Real-time feedback during coating | In-situ monitoring (SE31 / SE310) | Measure wet film at coating head |
| Wide-band transmittance/reflectance during deposition | SE31-FM | T/R-based optical film monitoring |
| EL defects in finished PV modules | EL inspection | Electroluminescence imaging |

## PV Testing Standards — Quick Map

| Standard | Scope | Related guide |
|---|---|---|
| IEC 61215 | PV module design qualification & type approval | [IEC testing guide](https://www.tdm-tek.com/news/guide/iec-61215-testing) |
| IEC 61730 | PV module safety qualification | [IEC testing guide](https://www.tdm-tek.com/news/guide/iec-61730-testing) |
| EL / PL imaging | Defect detection (cracks, micro-cracks, shunts) | [EL vs PL guide](https://www.tdm-tek.com/news/guide/el-vs-pl-inspection) |
| IV curve | Electrical performance characterization | [IV curve guide](https://www.tdm-tek.com/news/guide/iv-curve-testing-guide) |

## FAQ

**Q: Can you measure film thickness on textured silicon?**
A: Yes — but the texture depolarizes light, so standard ellipsometry models fail.
Use a textured-substrate measurement method. See our
[thin film measurement guides](https://www.tdm-tek.com/news) for the approach.

**Q: What is the difference between in-situ and inline measurement?**
A: In-situ monitors the film *during* coating (at the coating head, wet film).
Inline measures after deposition on the production line. Both give real-time
feedback; in-situ catches problems earliest.

**Q: Which method for films under 10 nm?**
A: Spectroscopic ellipsometry or XRR. For routine production, ellipsometry is
the practical choice.

## More Resources

- Full guides: [Measurement Guides & Application Notes](https://www.tdm-tek.com/news/)
- In-situ solutions: [In-situ Metrology](https://www.tdm-tek.com/solutions/in-situ-metrology)
- PV testing: [Electroluminescence Testing](https://www.tdm-tek.com/solutions/pv-electroluminescence-testing)
- Products: [tdm-tek.com/products](https://www.tdm-tek.com/products)

---

*Maintained by [TDM Technology](https://github.com/tdm-tek) — thin film measurement
instruments for PV, semiconductor & display. [Contact us](https://www.tdm-tek.com/about).*
