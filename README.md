# LiverCheck (prototype)

A clickable prototype of a patient-facing liver health tracker. Patients enter body measurements and blood results; the app shows two scores as green, amber or red and tracks them over time.

**Prototype only. Example data. Not medical advice and not for clinical use.**

## Scores

- **Fatty Liver Index** (Bedogni et al., 2006): BMI, waist, triglycerides, GGT. Below 30 green, 30–59 amber, 60+ red.
- **FIB-4** (Sterling et al., 2006): age, AST, ALT, platelets. AASLD 2023 cutoffs: below 1.3 green, 1.3–2.67 amber, above 2.67 red; low cutoff 2.0 from age 65; not reliable under 35.

## Data

Everything runs in the browser. Entries are saved only in the viewer's browser (localStorage); nothing is sent to a server. Do not enter real patient information.

## Hosting

Single static file (`index.html`), served with GitHub Pages from the `main` branch root.
