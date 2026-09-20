# 📄 Resume-Editor

A modern, interactive, browser-based **Resume Editor** and **PDF Generator** featuring live editing, customizable dual-column theme palettes, ATS-optimized export ordering, floating formatting tools, and instant offline persistence.

---

## ✨ Features

### 🎨 1. Dynamic Theme & Color Customizer
- **Interactive Palette Panel**: Easily customize colors for both the **Sidebar (Left Column)** and the **Main Page (Right Side)**.
- **6 Curated 1-Click Presets**:
  - 🌲 **Emerald** (Modern dark slate & vibrant teal)
  - 🌌 **Midnight Navy** (Deep navy & electric blue)
  - 🏛️ **Bronze & Obsidian** (Warm dark charcoal & copper gold)
  - 🍃 **Forest Sage** (Rich evergreen & fresh mint)
  - 🌹 **Crimson Rose** (Deep wine & bold coral)
  - 🖤 **Clean Monochrome** (Minimalist zinc & obsidian)
- **Live CSS Synchronization**: Changes reflect immediately across the entire resume and persist in `localStorage`.

---

### 📄 2. Dual PDF Export Modes
- **Design PDF**:
  - Export a sleek, two-column layout with customized color gradients, clear typography, and print-perfect margins.
- **ATS-Friendly PDF**:
  - Generates a clean, single-column, parser-safe black-and-white format designed for optimal parsing by Applicant Tracking Systems (ATS).

---

### 🔢 3. Customizable ATS Section Ordering
- Every section includes an interactive **`ATS #`** sequence number box.
- Customize the exact order in which your sections appear when exported in ATS mode (e.g., place *Technical Skills* or *Projects* above *Experience* depending on the role).
- All custom sequences are automatically saved.

---

### ✍️ 4. In-Place WYSIWYG Editing & Structural Controls
- **Direct Editing**: Click and edit any text block, bullet point, date, or role title directly in the document.
- **Section & Bullet Reordering**: Move bullet points, skill groups, or entire sidebar sections up or down with one click (`▲` / `▼`).
- **Dynamic Spacers**: Insert customizable blank spacing to balance page layout and avoid awkward print breaks.
- **Floating Selection Toolbar**: Select any text to quickly apply **Bold**, *Italic*, **Grey (Muted Highlight)**, or hyperlinks (`🔗`).

---

### 💾 5. Privacy-First & Zero Dependencies
- **100% Client-Side**: No backend server, external API dependencies, or databases needed.
- **Autosave**: Everything automatically saves to browser `localStorage` as you type.
- **Reset Option**: Safely revert to default sample data at any time.

---

## 🚀 Getting Started

### 1. Run Locally
No build step or Node.js environment is required. Simply open `resume_editor.html` in your favorite web browser:

```bash
# Clone the repository
git clone https://github.com/adil-rahman-3063/Resume-Editor.git

# Open the editor in your default browser
# On Windows:
start resume_editor.html

# On macOS:
open resume_editor.html

# On Linux:
xdg-open resume_editor.html
```

---

## 🖨️ PDF Export Tips

When printing or saving as PDF (`Ctrl + P` / `Cmd + P` or using the toolbar buttons):
1. Set **Destination** to **"Save as PDF"**.
2. Set **Paper size** to **A4**.
3. Set **Margins** to **None** or **Default**.
4. In **More settings**, enable **"Background graphics"**.
5. Disable **"Headers and footers"** for a clean, borderless export.

---

## 🛠️ Built With

- **HTML5** (Semantic structure & contenteditable)
- **Vanilla CSS3** (CSS Variables, Flexbox, Grid, Custom Print Media Queries)
- **Vanilla JavaScript** (Zero dependencies, event-driven state management, `localStorage` persistence)
- **Google Fonts** (*Fraunces*, *Inter*, *IBM Plex Mono*)

---

## 👤 Author

**Adil Rahiman**
- GitHub: [@adil-rahman-3063](https://github.com/adil-rahman-3063)
- Portfolio: [adilrahman.cc](https://adilrahman.cc)
- LinkedIn: [Adil Rahiman](https://www.linkedin.com/in/adil-rahiman-3815b5290/)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
