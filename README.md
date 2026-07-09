# Excalidraw Scripts Collection

This repository is a curated script archive for `Obsidian + Excalidraw`.

It organizes commonly used Excalidraw scripts by function so they are easier to browse, copy, preview, and maintain. The current collection includes `86` script source files together with their matching `SVG` preview images.

## Project Scope

- Good for backing up commonly used Excalidraw scripts to GitHub
- Good for finding scripts by category instead of searching through scattered folders
- Good for building a personal script library, teaching/demo library, or reference archive

This is not a standalone plugin project. Most scripts in this repository depend on the following runtime environment:

- Obsidian
- Excalidraw for Obsidian
- ExcalidrawAutomate / Script Engine

## Directory Structure

```text
Excalidraw/
└─ Scripts/
   ├─ 00_Common_Utilities
   ├─ 01_Selection_and_Batch
   ├─ 02_Layout_and_Alignment
   ├─ 03_Lines_and_Arrows
   ├─ 04_Text_Tools
   ├─ 05_Style_and_Color
   ├─ 06_Obsidian_Links_and_Embeds
   ├─ 07_Images_and_Icons
   ├─ 08_Mind_Maps
   ├─ 09_Presentation_and_Export
   ├─ 10_Study_Cards
   └─ 90_Experimental
```

Notes:

- `*.md`: script source and usage notes
- `*.svg`: script preview image or supporting visual

## Category Overview

| Category | Count |
| --- | ---: |
| 00_Common_Utilities | 10 |
| 01_Selection_and_Batch | 7 |
| 02_Layout_and_Alignment | 15 |
| 03_Lines_and_Arrows | 8 |
| 04_Text_Tools | 10 |
| 05_Style_and_Color | 12 |
| 06_Obsidian_Links_and_Embeds | 8 |
| 07_Images_and_Icons | 2 |
| 08_Mind_Maps | 2 |
| 09_Presentation_and_Export | 5 |
| 10_Study_Cards | 3 |
| 90_Experimental | 4 |

## How To Use

1. Install Obsidian.
2. Install and enable the `Excalidraw` plugin.
3. In a script-enabled environment, place the required `md` script file into your script directory, or copy the script content directly into your own Excalidraw Script file.
4. Run the corresponding script inside Obsidian / Excalidraw.

Different scripts may require different Excalidraw versions, network access, or extra plugins. Please read the header comments in each script file first.

## Source and Copyright Notes

This repository mainly republishes and reorganizes community Excalidraw scripts. Some content clearly comes from upstream projects and community-contributed scripts. Known sources include, but are not limited to:

- `zsviczian/obsidian-excalidraw-plugin`
- Related community scripts and demo resources

Therefore:

- Original author credits, licenses, and bundled notices should be preserved
- If a script file includes its own license or source note, that file-level note takes priority
- The added directory organization, documentation, and archive structure in this repository only represent the curation work itself

For more specific release notes, see `NOTICE.md`.

## License

This repository includes the `AGPL-3.0` license text at the root level to cover the curation layer and the public release notes of this repository.

If any script comes from a third party and includes its own original license, attribution, or usage requirements, the upstream terms should be followed first.
