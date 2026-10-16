# ResinCalc Pro — Industrial Flooring Estimator

> A professional, interactive material estimator and quote generator for industrial, commercial, and decorative epoxy and resin flooring systems.

![ResinCalc Pro Preview](./assets/project-preview.png)

---

## 🚀 Features

- **Comprehensive System Presets**:
  - **Self-Leveling Epoxy (SL-200)** — Commercial & institutional spec
  - **Thin Multi-Coat Roll-On** — Warehouse & garage dust-proofing
  - **Luxury Metallic Art Resin** — Showrooms, residential villas, and retail
  - **Heavy-Duty Trowel Screed** — Heavy manufacturing & chemical containment
  - **Moisture Barrier Primer** — High-damp substrate slab preparation
- **Precision Material Breakdown**:
  - Dynamic calculations for Part A (Resin base), Part B (Hardener), and aggregates / broadcast quartz.
  - Kit packaging calculator (exact kit counts + leftover surplus buffer).
- **Substrate & Application Factors**:
  - Substrate porosity adjustments (smooth power-troweled, CSP-2 shot-blasted, damaged concrete).
  - Configurable waste and spillage allowance (5% to 20%).
- **Dual Measurement Units**:
  - Full support for both Metric ($m^2$, mm, kg) and Imperial ($sq\ ft$, mils, lbs).
- **Printable Quote / Client Proposal**:
  - Built-in print preview formatted specifically for contractor proposals and export to PDF.
- **Fully Self-Contained**:
  - Zero server dependency, fully static, bundled with all image assets.

---

## 📁 Project Structure

```text
resincalculator/
├── index.html                  # Main interactive estimator application
├── assets/                     # Self-contained images and system photos
│   ├── logo.png                # Brand mark
│   ├── project-preview.png     # Full interface preview
│   ├── self-leveling-epoxy.jpg # SL-200 system visual
│   ├── thin-multicoat.jpg      # Thin-coat system visual
│   ├── moisture-barrier.jpg    # Moisture barrier visual
│   ├── luxury-metallic.jpg     # Metallic swirl system visual
│   └── heavy-duty-screed.jpg   # Heavy screed system visual
└── README.md                   # Documentation and hosting guide
```

---

## 💻 Local Usage

Simply open `index.html` in any modern web browser:

```bash
# Windows PowerShell
Start-Process index.html

# Or via any local HTTP server
npx serve .
```

---

## 🌐 Free Hosting & Deployment

### 1. GitHub Pages (Instant from this repo)
1. Go to your repository on GitHub: [https://github.com/rynp/resincalculator](https://github.com/rynp/resincalculator)
2. Click **Settings** → **Pages** (in the left sidebar).
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. In about 1 minute, your site will be live at:
   `https://rynp.github.io/resincalculator/`

### 2. Vercel
Deploy with one command via the Vercel CLI:
```bash
npx vercel
```
Or import the repository directly in the [Vercel Dashboard](https://vercel.com/new).

### 3. Netlify
Drag and drop this repository folder onto [app.netlify.com/drop](https://app.netlify.com/drop) for instant hosting.

---

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript** — Ultra-fast, zero-overhead reactive estimation engine.
- **Tailwind CSS** — Modern typography and responsive layout.
- **Google Fonts** — Plus Jakarta Sans & Inter.
- **Designed with Google Stitch** — Unified AI-assisted canvas workflow.

---

## 📄 License

MIT License — Feel free to customize and use for commercial resin flooring contracting.
