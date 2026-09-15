# JSON Viewer Tool

A fast, single-file JSON viewer and formatter that runs entirely in your browser. No install, no build step, no server, just open the HTML file.

## Features

- **Smart search** plain text, plus `in:field`, `type:kind`, and `has:field` declarations, a results list, and the exact path shown for the current match
- **Jump to Source** click any line or search match to jump straight to it in the Source panel and edit it there
- **100% client-side** nothing you paste or upload is ever sent anywhere
- **Tree / Preview / Collapsible / String views**, built lazily so large files stay fast
- **Sessions panel** work on multiple files at once, each kept in your browser's local storage
- **Compare mode** view two sessions side by side, each with its own independent search
- Multiple syntax color themes
- Copy, download, and drag-and-drop upload

## Getting Started

Open `JSON_Viewer_Tool.html` in any modern browser (Chrome, Firefox, Safari, Edge). Paste JSON into the Source panel, or drag and drop a `.json`/`.txt` file, the formatted result appears in the Output panel.

## Privacy

Everything runs locally in your browser, parsing, searching, formatting. No accounts, no ads, no server component.
