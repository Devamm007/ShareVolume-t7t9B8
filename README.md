# Cardinal Health Shares Volume Web App

## Overview
This web application fetches and displays the shares outstanding data for Cardinal Health (CIK 0000721371) from the SEC's data API. It visualizes the maximum and minimum share counts over recent fiscal years, with dynamic updates based on URL query parameters.

## Usage
1. Clone this repository:
```bash
git clone <repository_url>
```
2. Open `index.html` in your browser.
3. To view data for a different company, append `?CIK=XXXXXXXXXX` to the URL, replacing `XXXXXXXXXX` with the desired 10-digit CIK.

## Development & Customization
- The app fetches data from the SEC API, using a proxy if a different CIK is specified.
- Data is stored in `data.json`.
- The webpage updates dynamically based on fetched data.

## License
This project is licensed under the MIT License. Feel free to contribute or customize.

## Collaboration
Open to collaboration! Reach out via GitHub issues or pull requests.

---

**Note:** Ensure your browser allows local file access or serve via a local server for full functionality.