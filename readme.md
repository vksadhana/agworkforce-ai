# agworkforce-ai

interactive research report quantifying how generative AI has reshaped entry-level hiring in agriculture and sustainability — built for the Rutgers Aresty Research Program (2025–2026).

live site: [vksadhana.github.io/AgSustainability](https://vksadhana.github.io/AgSustainability)

## what this is

a data-driven web report analyzing 25,530 federal and private sector job postings (2019–2025) to measure how ChatGPT's release shifted skill demands, compensation, and hiring barriers in agriculture and sustainability occupations.

presented at the Rutgers Aresty Undergraduate Research Symposium and the NAREA Conference (June 2026). awarded NAREA 2026 Poster of Merit.

## findings

**skill evolution** — active learning is the only skill category trending upward on the O*NET 5-point importance scale (2020–2024). every other category — personnel management, quality control, instructing — is declining, consistent with AI absorbing routine coordination roles.

**86 new tools** — geospatial and remote sensing tools (GIS, remote sensing platforms) entered 13 of 21 occupation categories since 2020, including roles like forestry technician and soil conservationist that historically had no such requirement. 86 distinct new technologies appeared in federal job postings between 2020 and 2024.

**compensation** — the raw agriculture vs sustainability wage gap collapses to +0.4% (NS) once GS grade and location are controlled (R² = 0.947). entry grade determines salary, not sector. GIS and data analytics are the primary route to entering at GS-7 or GS-9 rather than GS-5.

**structural barriers** — 56% of postings show ATS screening signals. federal early-career postings represent only 3.3% of federal listings vs 32% in the private sector. students face credential timing misalignment: requirements shifted after enrollment.

## methods

- data: USAJobs API (federal), Adzuna snapshot (private), O*NET DOL occupational database
- NLP-based skill extraction and classification in Python
- OLS with two-way fixed effects (company, year, location); company-clustered standard errors
- temporal split: pre-ChatGPT (2019–2022, n=16,578) vs post-ChatGPT (2023–2025, n=8,952)

## team

Sadhana Vasanthakumar, Vinayak Ghai, Ziyong Qu, Nikhil Srinivas

faculty advisor: Dr. Yanhong Jin, Department of Agricultural, Food, and Resource Economics, Rutgers University

## stack

- HTML, CSS, JavaScript
- Chart.js (data visualizations)
- IBM Plex Sans / Playfair Display
