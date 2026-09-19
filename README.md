# Smoke-RGBT

## 🔥 Smoke-RGBT Benchmark
<img width="1322" height="559" alt="image" src="https://github.com/user-attachments/assets/7d9b1123-9f0c-42fa-b037-855b1e45e5bf" />

**Smoke-RGBT** is an RGB-T video benchmark designed for visual perception
under real-world smoke conditions. It contains RGB and thermal
videos captured under diverse scenes and different levels of smoke degradation.

The benchmark is developed to facilitate research on robust RGB-T perception,
particularly under severe visibility degradation and cross-modal appearance
differences.

### Highlights

- 🎥 **523 RGB-T video sequences**
- 🖼️ **~902K video frames**
- 🌫️ Multiple smoke-density levels: **thin, medium, and thick smoke**
- 🌡️ Paired **RGB and thermal (TIR)** observations
- 📦 Modality-specific annotations for RGB and TIR
- 📝 Target-level language descriptions
- 🎯 Support for RGB-T tracking and other RGB-T perception tasks

---

## 📢 News

- **2026-09**: The Smoke-RGBT GitHub repository is online.
- **2026-09**: Several example sequences are released for preview.
- Full dataset and evaluation toolkit will be released progressively.

---

## 👀 Dataset Examples

The following figure shows representative sequences from **Smoke-RGBT**
under different smoke densities.

<p align="center">
  <img src="image.jpg" width="100%">
</p>

Examples include scenes under **thin**, **medium**, and **thick** smoke,
illustrating the complementary characteristics of RGB and thermal modalities.

### Download Example Sequences

Several representative sequences are currently available for preview:

**Baidu Netdisk:**  
[Download example sequences](https://pan.baidu.com/s/1nF2g4GowHEhJJFlobCEjIA?pwd=7728)

**Extraction code:** `7728`

> The complete Smoke-RGBT dataset will be released after dataset organization
> and publication procedures are completed.

---

## 📊 Dataset Overview

| Property | Smoke-RGBT |
| --- | ---: |
| Number of sequences | 523 |
| Number of frames | ~902K |
| Modalities | RGB + Thermal |
| Smoke levels | Thin / Medium / Thick |
| Scene types | Indoor + Outdoor |
| Target categories | 59 |
| Language descriptions | ✓ |
| Modality-specific annotations | ✓ |

---

## 📂 Repository Structure

```text
Smoke-RGBT/
├── README.md
├── image.jpg
├── 3.21-testlist.txt
└── ...
