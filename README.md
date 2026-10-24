# Campus Energy Digital Twin: DLSU Case Study

A one-page case study made for the **Young Leaders Forum 2026** in Ho Chi Minh City, Vietnam, where it accompanied a research paper on using digital twins to manage campus energy. The paper won Best Research Paper at the forum.

The page makes the financial case for occupancy-driven energy control using De La Salle University in Manila as the example: a large, year-round campus in a tropical climate where cooling demand and unmanaged "ghost" consumption add up quickly.

## What the page covers

- DLSU's estimated annual electricity spend, from the DLSU Sustainability Report (2019 to 2021)
- The share of energy commercial and institutional buildings waste through unmanaged occupancy, per the U.S. EPA
- Projected savings at a conservative 15% reduction in consumption
- Cost and payback of a single sensor node (microcontroller, motion sensor and temperature sensor)
- Expected monthly cost reduction from automated, occupancy-based control

Figures are shown in both Philippine pesos and US dollars.

## Tech

A single self-contained `index.html` with inline styles and no dependencies. It is deployed to GitHub Pages by the workflow in `.github/workflows/static.yml` on every push to `main`.

To view it locally, open `index.html` in a browser.
