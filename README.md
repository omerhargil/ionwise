# Ionwise

A lightweight, responsive memorization app for nine essential polyatomic ions. Built with plain HTML, CSS, and JavaScript—no build step or dependencies required.

## Included
- Study cards with reveal + self-rating
- Typed recall in both directions (name → formula and formula → name)
- Formula checking that requires the correct charge
- Name checking with exact spelling
- Six-pair matching game with a timer
- Progress and practice accuracy saved in local storage
- Responsive layout for desktop and mobile

## Run locally
Open `index.html` in a browser, or run a static server from this directory:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to Vercel
Import this repository in Vercel. Framework preset: **Other**. Build command: leave blank. Output directory: `.`. No environment variables are required.

## Ion reference set
| Name | Formula | Charge |
|---|---|---|
| Ammonium | NH₄⁺ | +1 |
| Phosphate | PO₄³⁻ | −3 |
| Hydroxide | OH⁻ | −1 |
| Bicarbonate (hydrogen carbonate) | HCO₃⁻ | −1 |
| Cyanide | CN⁻ | −1 |
| Nitrate | NO₃⁻ | −1 |
| Acetate | C₂H₃O₂⁻ | −1 |
| Carbonate | CO₃²⁻ | −2 |
| Sulfate | SO₄²⁻ | −2 |

Acetate is also commonly written CH₃COO⁻. The typed checker accepts both forms.
