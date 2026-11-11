# SuryaSetu — Solar-powered irrigation for Telangana

A responsive static web application prototype for affordable solar/hybrid irrigation pumps (3–10 HP).

## Experiences
- **Website:** full dashboard with responsive desktop and mobile navigation.
- **Android preview:** compact Android-style phone interface.
- **iOS preview:** iPhone-style interface.

Use the experience switch in the top-right corner to change modes.

## Included modules
- Overview dashboard with illustrative energy, water, pump and health KPIs
- Pump stations and borewell engineering considerations
- Solar generation, grid import and permitted-export ledger
- Tamper-evident metering concept
- Groundwater flow and water-level monitoring
- Theft-resistant panel mounting, GPS tagging and incident workflow
- Service tickets and field maintenance concept
- Farmer and state-level savings scenario calculators
- Telangana programme dashboard and delivery roadmap
- CSV export for illustrative energy ledger
- Progressive Web App manifest and offline-shell service worker

## Run locally
Open `index.html` in a browser, or serve this folder with any static HTTP server.

## Publish
This repository includes a GitHub Actions workflow that publishes the root website to the `gh-pages` branch on every push to `main`.

After the first workflow run, open **Settings → Pages** and set the source to **Deploy from a branch**, branch **gh-pages**, folder **/(root)** if Pages is not already configured. The site URL will be:

`https://vamshiperumbudoor.github.io/suryasetu/`

## Prototype boundary
This is a **front-end demonstration**. Readings, pump stations, alerts, district deployments and KPI figures are simulated. It does not control physical pumps, read utility meters, authenticate field devices, track live GPS, dispatch technicians or process payments. Production use requires commissioned hardware, secure backend services, electrical and grid approvals, hydrogeological validation, cybersecurity review and field testing.

The 30% cost reduction is a target to validate, not a guaranteed claim. Pump sizing and cost must be verified against each site's total dynamic head, discharge, duty cycle, motor compatibility and lifecycle costs.

The Android and iOS modes are UI previews, not installable native binaries.
