MICHIGAN GASOLINE EXPECTATIONS — GITHUB PAGES

Upload BOTH files in this folder to the ROOT of your existing repository:
  index.html
  data.json

Do not upload the original respondent-level CSV.

GitHub Pages settings:
  Settings > Pages > Deploy from a branch
  Branch: main
  Folder: / (root)

The website uses Plotly.js from its public CDN and loads ./data.json.
The notebook's analyses are precomputed from the uploaded Michigan CSV.

Notes:
- The analysis sample follows the notebook: observations with at least one nonmissing A20/A20b response.
- Magnitude special codes 996, 997, 998, 999 and negative counterparts are removed.
- Annual response shares use codes 1, 3, 5, 8, 9.
- Magnitude histogram ranges and bins follow the notebook (A20a: 0–300; A20c: 0–200; 10-cent bins).
- Routing eligibility is coded as direction response 1 or 5. Confirm official questionnaire routing before interpreting routing inconsistencies.
- Monthly availability table is transposed (measures by month), matching the notebook.
