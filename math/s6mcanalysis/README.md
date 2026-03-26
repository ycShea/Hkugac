# HKUGAC Mathematics: S6 MC Analysis

The live portal for this module can be accessed at: **[https://ycShea.github.io/Hkugac/math/s6mcanalysis/](https://ycShea.github.io/Hkugac/math/s6mcanalysis/)**

This directory contains the web interface for managing S6 Mathematics Multiple Choice (MC) performance data, student administrative records, and DSE topic distribution for HKUGAC.

## 🚀 Key Features
- **Student Administration:** Centralized links for S5/S6 student lists and teacher group assignments.
- **DSE Topic Mapping:** A comprehensive index of DSE Mathematics MC questions categorized by topic and year (2012–2025).
- **Performance Analytics:** Direct access to "Live Spreadsheet" sections that handle complex scoring formulas and response extraction.
- **Mobile Responsive:** Built with Bootstrap 5 to ensure accessibility across desktop and mobile devices.

## 🛠️ Folder Structure
- `hkugac/`
  - `math/`
    - `s6mcanalysis/`
      - `index.html` (The dashboard code provided)
      - `README.md` (This documentation)

## 📖 User Instructions
1. **Data Entry:** Use the buttons under **Student Administration** to submit student responses via Google Forms.
2. **Analysis:** For sections marked with the `Live Spreadsheet` badge, the links will direct you to specific tabs within the Google Sheet. This ensures that dynamic formulas (like `VLOOKUP` and `QUERY`) remain functional and accurate.
3. **Curriculum Reference:** The **DSE Topic Analysis** section is intended for staff to quickly identify curriculum coverage across past papers.

## 🔧 Deployment & Maintenance
To update this portal:
1. Edit the `index.html` file within this directory.
2. Ensure any new Google Spreadsheet `gid` or `URL` is updated in the corresponding `<a>` tags.
3. Commit changes to the `main` branch to trigger the GitHub Pages update.

## 📝 License
Internal Use Only - HKUGAC Mathematics Department.
