# vitamin-c-virtual-lab
# Vitamin C Determination – Interactive Virtual Chemistry Lab

A browser-based virtual experiment to estimate Vitamin C (ascorbic acid) in fruit juice using DCPIP titration.

## Features
- Student details form (pre-filled with the supplied details; editable)
- DCPIP standardisation and automatic dye-factor calculation
- Interactive drop-by-drop sample titration with endpoint colour change
- Editable titre and dilution readings
- Automatic Vitamin C calculation in mg/100 mL
- Learning centre with principle, materials and procedure
- Five-question viva quiz with instant feedback
- Print / Save as PDF lab report

## Run locally
No Node.js or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Create a new public GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then click **Save**.
6. Wait for the Pages URL to appear in the Pages section.

You can also import the repository into Vercel as a static site. No build command is needed; the output directory is the project root.

## Calculation
Dye factor (mg/mL) = Standard ascorbic acid concentration (mg/mL) × standard aliquot (mL) ÷ DCPIP titre (mL).

The current interface assumes a 1 mL standard aliquot, so:
`Dye factor = standard concentration / standard titre`

Vitamin C (mg/100 mL) =
`(sample titre × dye factor × extract volume × 100) / (aliquot volume × original juice volume)`

## Scientific note
This is an educational simulation. The drop counter is illustrative; use the measured titre field for calculations. Actual results depend on reagent concentration, sample preparation, endpoint judgement, and experimental conditions. Perform real laboratory work only under supervision and follow institutional safety guidance.

## Student details
- Name: A R Veronica Nethra
- Register number: RA2611003050006
- Department: B.Tech Computer Science
