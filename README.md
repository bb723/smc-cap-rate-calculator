# SMC Cap Rate Calculator

A branded, single-page cap rate / NOI calculator for Standard Management Company, used to underwrite a potential rental project.

## Features
- Income inputs: purchase price, units, rent per unit, other income, vacancy.
- Expense entry two ways:
  - **Expense ratio** (quick): total operating expenses as a percent of effective gross income (defaults to 45%, overridable).
  - **Itemize** (manual): property taxes, insurance, management fee (10% of EGI, overridable), water, sewer, electric, heat, lawn and snow ($150 per property per month year round, overridable), repairs, and other.
- Live outputs: effective gross income, NOI, cap rate, expense ratio, price per unit.
- Target cap rate to implied value (offer price) helper.
- Print / save-to-PDF for sharing with an owner.

## Hosting
Static site, no build step. Served via GitHub Pages from the `main` branch root. `index.html` is the whole app; `logo.jpg` is the SMC mark.

For estimating purposes only.
