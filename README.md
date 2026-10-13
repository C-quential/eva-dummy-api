# eva-dummy-api
Contains dummy json files to test EVA LMS integration with Roosterplanning

Roosterplanning reads `scholingen.json` and `inschrijvingen.json`. They are published from an Excel file with `Publiceer.html`:

| File | Purpose |
|---|---|
| `Publiceer.html` | Checks a filled-in Excel and publishes both json files to this repo. Open it from the shared OneDrive folder; the Hulp button explains the rest. |
| `EVA-dummy-import-voorbeeld.xlsx` | Example Excel; the Toelichting sheet explains the fields. |
| `instellingen.js` | Settings for `Publiceer.html`. The token is empty here on purpose: fill it in only in the copy in the shared OneDrive folder, never in this repo. |
