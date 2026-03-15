# 📊 Data Visualization with Wasm-Powered Aggregation

Built with **Rust + WebAssembly** for data crunching and **Svelte + Chart.js** for beautiful visualizations.

---

## ✨ Features

- 📂 Drag & drop CSV file upload
- 🔍 Auto-detect column names and types (numeric vs string)
- ⚙️ Aggregations — TBD
- 📊 Chart types — TBD
- 🔃 Group by any column
- 🔎 Filter rows by column value
- 📥 Export chart as PNG
- 💾 Export aggregated data as CSV
- 🎨 Dark / Light mode

---

## 🛠️ Tech Stack

| Layer              | Technology                          |
|--------------------|-------------------------------------|
| Data engine        | Svelte + `wasm-bindgen` + `wasm-pack` |
| CSV parsing        | `csv` crate                         |
| Serialization      | `serde` + `serde-wasm-bindgen`      |
| Frontend framework | Svelte + TypeScript                  |
| Charts             | Chart.js                            |
| Styling            | Tailwind CSS                        |
| Build tool         | Vite + `vite-plugin-wasm`           |
| Deployment         | Vercel with domain                       |

---

## ✅ TODO

### 🦀 Rust / Wasm Core
- [ ] Set up `wasm-pack` project scaffold
- [ ] ToDo: when a structure was established
- [ ] Expose all functions to JS via `wasm-bindgen`
- [ ] Write unit tests for aggregation logic
- [ ] Optimize with `wasm-opt`

### ⚛️ Frontend (Svelte + TypeScript)
- [ ] Set up Vite + Svelte + Tailwind project
- [ ] Integrate `vite-plugin-wasm` for Wasm loading
- [ ] ToDo: when a structure was established
- [ ] Add loading state while Wasm processes data
- [ ] Add error handling (invalid CSV, empty file, etc.)
- [ ] Add dark / light mode toggle
- [ ] Show processing time
- [ ] Export chart as PNG
- [ ] Export aggregated results as CSV

### 🎨 UI / UX
- [ ] Responsive layout (mobile + desktop)
- [ ] Empty state illustration (before file upload)
- [ ] Animated chart transitions
- [ ] Color palette for multi-series charts
- [ ] Accessible design (ARIA labels, keyboard navigation)

### 🚀 Deployment & Docs
- [ ] Add `README.md` with live demo link
- [ ] Add performance benchmark section to README
- [ ] Set up GitHub Actions CI (build + test)
- [ ] Deploy to Vercel
- [ ] Add live demo badge to README
- [ ] Add sample CSV datasets for demo
