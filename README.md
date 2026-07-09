# WikiTreeHelper
Helps people to write Wikitree Biographies and Converts WSYIWYG to Wikitree Markdown
import os

readme_content = """# WikiTree Markdown Companion

An interactive, side-by-side WYSIWYG editor and WikiTree markup code generator. This utility bridges the gap for genealogists who prefer a visual formatting interface while strictly generating clean, platform-compliant WikiTree markdown code.

## 🚀 Live Demo & Usage

This application is completely self-contained within a single HTML file. You don't need to install anything or run a server. 

1. Download the `index.html` file.
2. Double-click it to open it instantly in any modern web browser.
3. Start typing or paste your existing WikiTree markup code to synchronize and edit it!

## ✨ Key Features

* **Bi-directional Live Synchronization:** Type visually inside the rich WYSIWYG pane to instantly auto-generate WikiTree code, or paste existing profile code directly into the markup pane and click **"Sync to Rich Editor"** to import and edit it visually.
* **WikiTree-Specific Headers:** Built-in buttons for instantly dropping in correct `== Biography ==` and `== Sources ==` structures.
* **Smart Citation & Footnote Support:** Easily insert inline footnotes using a custom `<ref>` tag builder. A visual live compiler previewer at the bottom allows you to instantly track exactly how your references will read once published to your ancestor's profile.
* **MediaWiki Table Builder:** Rapidly generate clean, multi-column and multi-row Wikitables matching WikiTree criteria—ideal for setting up structured census records, gravestone indexes, and military timeline data grids.
* **Hyperlink Helpers:** Dedicated contextual tools to cleanly format internal WikiTree profiles (`[[ID|Display Text]]`) and standard external web URLs (`https://bigtext.vercel.app/`) with correct space-separation rules.
* **Clean Formatting Triggers:** Fast buttons for standard bold (`'''`), italics (`''`), combined formatting (`'''''`), strikethroughs (`<s>`), and double indented lists (`**`).
* **Safe Clean Canvas Operations:** A **Clear All** safety protection prompt to prevent accidentally losing your live profile progress.
* **Zero Dependencies / Framework Noise:** Crafted entirely with raw, safe vanilla JavaScript alongside highly responsive Tailwind CSS and Lucide vector icon assets loaded directly from trusted content delivery networks (CDNs).

## 📄 Repository Structure
