# MINTH RFQ Generator

Internal tool for generating Assembly Line RFQ documents in P833/NX5A template style.

## Access
👉 **[Open the tool](https://YOUR-ORG.github.io/minth-rfq-generator)**

## Features
- P833 / NX5A MINTH template style (logo, background, blue headers, purple Poka-Yoke)
- Step-by-step procedure builder with per-step time input
- Cycle time meter — auto warns when over target, suggests Add Equipment or Add Operator
- Poka-Yoke auto-detected from procedure steps → choose Sensor / Camera / Manual per part
- Direct PPTX download in browser (no server, data stays local)

## Update the tool
1. Edit `index.html` locally
2. Go to GitHub repo → `index.html` → Edit (pencil icon)
3. Paste new content → Commit changes
4. GitHub Pages auto-updates within ~30 seconds

## Tech
- Pure HTML/CSS/JS — single file, no framework, no build step
- [PptxGenJS](https://gitbrentackerman.github.io/PptxGenJS/) for PPTX generation
- Minth time database built from Ford P833 Front + Rear Fascia real project data
