# 📹 CCTV Technician Calculator

> A fully offline, single-file CCTV installation calculator with **14 professional tools** built for CCTV technicians, installers, and security system planners.

**Developed by [OnexusDev](https://onexusdev.xyz) X Moursalin Islam**

---

## ✨ Features Overview

### 🧮 14 Built-in Calculators

| # | Tool | Purpose |
|---|------|---------|
| 01 | **Cable Length / কেবল দৈর্ঘ্য** | Calculate total cable requirement and reel/box count based on cable runs, average length, waste allowance, and spare cable. |
| 02 | **HDD Storage / স্টোরেজ** | Estimate recording storage (GB/TB) from per-camera bitrate, recording days, daily hours, duty cycle, and reserve overhead. Suggests the next standard HDD size. |
| 03 | **DC Power Supply / DC পাওয়ার** | Size DC power supplies from device count, voltage, and maximum current per device with configurable reserve margin. |
| 04 | **PoE Budget / PoE বাজেট** | Validate total PoE draw against switch budget and per-port PoE limits. Includes PASS/FAIL checks. |
| 05 | **Lens FOV / লেন্স কভারেজ** | Compute horizontal/vertical field-of-view angles and scene width/height/area from sensor size, focal length, and distance. |
| 06 | **Network Bandwidth / ব্যান্ডউইথ** | Aggregate camera bitrate with configurable network headroom for bandwidth planning. |
| 07 | **Installation Quote / কোটেশন** | Build a complete project quote from camera cost, recorder, HDD, cable/accessories, labor, and markup percentage. |
| 08 | **DVR/NVR Count / রেকর্ডার সংখ্যা** | Calculate minimum recorder count, average per-recorder bitrate, and run channel/bandwidth validation checks. |
| 09 | **UPS Runtime / UPS ব্যাকআপ** | Estimate UPS runtime (hours/minutes) from battery bank voltage, Ah capacity, efficiency, usable energy fraction, and load. |
| 10 | **DC Voltage Drop / ভোল্টেজ ড্রপ** | Calculate loop resistance, voltage drop, load-end voltage, and drop percentage for two-wire DC copper circuits. |
| 11 | **Battery Capacity / ব্যাটারি Ah** | Compute required battery Ah from load, runtime, voltage, efficiency, usable capacity, and aging factor. Suggests next standard nominal size. |
| 12 | **IPv4 Subnet / IP subnet** | Full IPv4 subnetting: network address, subnet mask, broadcast address, total addresses, and usable host count from CIDR. |
| 13 | **Linear Camera Count / রেখা বরাবর ক্যামেরা** | One-dimensional camera layout estimate from area length, effective coverage, and adjacent overlap percentage. |
| 14 | **Material Quantity / মালামাল** | Calculate purchase quantity from base quantity, waste allowance, and pack size. |

---

## 🚀 Key Highlights

- ✅ **100% Offline** — No internet required. Works entirely in the browser.
- ✅ **Single-File Deployment** — One HTML file. No build tools, no dependencies.
- ✅ **Elementor-Ready** — Scoped CSS and unique IDs. Drop it into any page builder.
- ✅ **Bilingual UI** — Bengali + English labels throughout.
- ✅ **Real Formula Explanations** — Every calculator shows its underlying formula and assumptions.
- ✅ **Input Validation** — Bounds checking, integer enforcement, and clear error messages.
- ✅ **Print / PDF Support** — Dedicated print stylesheet for clean paper output.
- ✅ **Responsive Layout** — Works on desktop, tablet, and mobile.
- ✅ **Dark Theme UI** — Modern, high-contrast interface designed for field use.
- ✅ **PASS/FAIL Validation** — PoE budget and recorder count include automatic pass/fail checks.

---

## 🛠️ Technical Details

| Property | Value |
|----------|-------|
| **Language** | HTML5 + CSS3 + Vanilla JavaScript |
| **Dependencies** | None |
| **File Size** | ~65 KB (single file) |
| **Browser Support** | All modern browsers (Chrome, Firefox, Edge, Safari) |
| **CSS Scoping** | All styles prefixed with `#cctv-calc-app` |
| **ID Prefixing** | All element IDs prefixed with `cctv-` to avoid conflicts |
| **Print Support** | `@media print` stylesheet included |
| **Responsive** | Mobile-first breakpoints at 820px, 620px, 560px, 420px |

---

## 📦 Installation

### Option 1: Direct HTML Usage
1. Download `cctv-technician-calculator.html`
2. Open in any modern browser
3. Done. No server needed.

### Option 2: Elementor / WordPress
1. Copy the entire code (HTML + `<style>` + `<script>`)
2. Open Elementor → Add **HTML Widget**
3. Paste the code
4. Save and publish

### Option 3: GitHub Pages Hosting
1. Fork this repository
2. Enable **GitHub Pages** in Settings → Pages
3. Select the `main` branch
4. Access at `https://yourusername.github.io/cctv-technician-calculator/`

---

## 🧪 Formula Validation

Each calculator includes verified formula regression tests during development. Test cases cover:

- Cable total length accuracy
- HDD raw storage (bitrate × cameras × days × hours)
- DC power reserve calculations
- PoE design budget checks
- FOV scene width computation
- Network bandwidth with headroom
- Installation quote totals
- Recorder count validation
- UPS runtime estimation
- Copper voltage drop
- Battery design Ah
- IPv4 /24 network address
- Linear camera count
- Material pack rounding

---

## ⚠️ Important Disclaimers

> **This calculator is for planning and estimation purposes only.**
>
> - "PASS" results mean the arithmetic matches a specific test case — **not** that the result is 100% accurate for all manufacturers' devices.
> - For Hikvision storage/bitrate or lens results, always use the correct **model**, **codec**, **FPS**, **configured bitrate**, and **manufacturer datasheet**.
> - Verify all results against actual device specifications, local electrical standards, and measured site conditions before installation.
> - Voltage drop calculations assume ideal steady DC current and equal supply/return conductors — not a PoE Ethernet calculator.
> - UPS runtime is an idealized energy approximation; real runtime depends on battery chemistry, temperature, age, and discharge rate.

---

## 📄 License

This project is released for educational and professional use. See `LICENSE` file for details.

---

## 👨‍💻 Credits

**Developed by [OnexusDev](https://onexusdev.xyz) X Moursalin Islam**

- 🌐 Website: [onexusdev.xyz](https://onexusdev.xyz)
- 📹 Category: CCTV / Security Systems / Field Tools
- 🛠️ Built with: HTML, CSS, JavaScript (no frameworks)

---

## 🔗 Related Projects

- [CCTV Storage Calculator](#)
- [PoE Budget Planner](#)
- [IP Subnet Tool](#)

---

## 📌 Version

**v1.0.0** — Initial release with 14 calculators, bilingual UI, print support, and formula validation.

---

⭐ **If this tool helped you, please consider giving this repository a star!**
