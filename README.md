# 🧵 Dressmaker Open Atelier Codex & Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-rose.svg)](https://opensource.org/licenses/MIT)
[![Companion: GameIndex](https://img.shields.io/badge/Companion-GameIndex%20Wiki-e11d48)](https://gameindex.wiki/games/dressmaker/)
[![Data: Verified](https://img.shields.io/badge/Data-Verified%20Patch%20Stats-emerald)](https://gameindex.wiki/games/dressmaker/)

An open, verified database and mechanics compendium for **Dressmaker** (developed by Cozy Lives, published by Free Lives). This repository contains structured datasets for all atelier equipment, pattern layouts, fabric efficiency parameters, customer brief metrics, and 100% quality sewing techniques.

---

## 🌐 Official Web Companion

For interactive fabric calculators, step-by-step garment assembly guides, and customer brief breakdown matrices, check the live web companion:

👉 **[GameIndex Dressmaker Atelier Companion](https://gameindex.wiki/games/dressmaker/)**

### Key Progression & Crafting Guides
- **[Dressmaker Beginner Guide & Studio Walkthrough](https://gameindex.wiki/games/dressmaker/guides/dressmaker-beginner-guide/)** — Atelier workstation layout, daily studio rhythm, and early customer order management.
- **[How to Get 100% Quality Score on Garments](https://gameindex.wiki/games/dressmaker/guides/dressmaker-100-quality-score-guide/)** — Precision seam guidance, corner deceleration, and needle speed controls.
- **[Fabric Grain Alignment & Pattern Cutting Guide](https://gameindex.wiki/games/dressmaker/guides/dressmaker-fabric-grain-alignment-cutting-guide/)** — Grain-line orientation rules, green outline confirmation, and zero-waste pattern nesting.
- **[Customer Briefs & Style Matching Guide](https://gameindex.wiki/games/dressmaker/guides/dressmaker-customer-briefs-style-matching-guide/)** — Client preference matrices, fabric tags, and appraisal tips for 5-star reviews.
- **[Best PC Settings & Sewing Assist Controls](https://gameindex.wiki/games/dressmaker/guides/dressmaker-best-pc-settings-fps-guide/)** — Mouse sensitivity calibration, Sewing Assist accessibility toggles, and high-FPS optimization.

---

## ✂️ Workshop Equipment Overview

| Equipment | Station Type | Key Mechanics | Studio Objective |
| :--- | :--- | :--- | :--- |
| **Cutting Table** | Fabric Preparation | Grain-line orientation, green outline feedback | Zero wasted yardage via efficient panel nesting |
| **Sewing Machine** | Assembly & Stitching | Needle speed regulation (W/S), fabric rotation (A/D) | 100% Seam Quality Score |
| **Drafting Desk** | Pattern Design | Digital pattern alteration, grading, dart adjustments | Custom client design fidelity |
| **Ironing Station** | Finishing & Pressing | Seam opening, steam temperature, wrinkle removal | Flawless final presentation grade |
| **Fitting Mannequin** | Client Showcase | Hemline drape verification, fit adjustments | 5-Star client review approval |

---

## 📦 Dataset Structure

The structured JSON dataset is available under [`data/items.json`](data/items.json):

```typescript
interface DressmakerStation {
  slug: string;
  name: string;
  role: string;
  category: string;
  schema_type: string;
  description: string;
  stats: Record<string, string>;
  body: string;
}
```

---

## 🤝 Contributing

Contributions, mechanic clarifications, and pattern nesting recipes are welcome! Please open an issue or pull request, or consult the [GameIndex Dressmaker Wiki](https://gameindex.wiki/games/dressmaker/).

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
