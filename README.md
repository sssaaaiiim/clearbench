# 🛠️ Clearbench — Inclusive Design Workbench

> A practical, self-testing workbench designed for testing, measuring, and remediating web interfaces against **WCAG 2.1 A, AA, and AAA** accessibility standards.

---

## ✨ Features & Benches

### 01. ⌨️ Keyboard & Screen Reader Bench
* **Roving Tabindex & ARIA APG Patterns**: Test vertical tablists, menu buttons, disclosure widgets, and modal focus traps.
* **Accessible Validation & Live Regions**: Form validation connected via `aria-describedby` and screen-reader announcements via `role="status"`.
* **Input Ledger**: Key-press journal that logs focus history to verify focus order and trap handling.

### 02. 🎨 Contrast & Magnification Rig
* **WCAG Contrast Calculator**: Real-time relative luminance calculation for text and UI component contrast ratios.
* **Auto-Fix Utility**: Suggests a passing ink color while preserving hue.
* **Magnification Stage**: Simulates up to 400% text scaling, 320 px reflow, custom text spacing, and color-vision deficiencies (Protanopia, Deuteranopia, Tritanopia, Achromatopsia).

### 03. 🔧 Remediation Workshop
* **Interactive Barrier Audit**: Inspect an intentional regression build vs. an accessible patched build.
* **Barrier Ledger**: Track, patch, and mark off 14 real-world WCAG accessibility barriers step-by-step.

### 04. 📝 Audit Ledger
* **Standard-Based Checklists**: Score individual WCAG criteria with pass/fail/NA verdicts and evidence notes.
* **Report Builder**: Generate and export formatted plain-text audit reports or print directly.

---

## 🚀 Quick Start

Clearbench is built using **pure HTML, CSS, and vanilla JavaScript** with zero external dependencies or build steps required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/clearbench.git](https://github.com/your-username/clearbench.git)
