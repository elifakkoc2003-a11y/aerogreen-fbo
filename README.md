# AeroGreen FBO

A front-end prototype that helps heavy business-jet operators plan a smooth arrival during **Super Bowl week in Los Angeles**. AeroGreen suggests a primary plan at **Van Nuys (VNY)** with **LAX** and **ONT** as backup options. A qualified FBO team member always makes the final decision.

- **Live demo:** https://elifakkoc2003-a11y.github.io/aerogreen-fbo/
- **Slides:** [AEROGREEN_SLIDE.pdf](AEROGREEN_SLIDE.pdf)

## What it does

- **Customer portal:** submit a flight request, get airport suggestions with estimated cost, parking, fuel, turnaround and security, then request confirmation.
- **FBO team portal:** review requests, request more information, or approve for final confirmation. Status updates flow back to the customer view.
- **Assistant chat:** answers common questions about the form, Sunday capacity, fees and the approval process.
- **Scenario planner, fee model and research context** for the FBO team.

> This is a demo. It needs no database or API key, and all results and approvals are simulated in the browser. Dashboard values are modeled assumptions, not official airport forecasts.

## Try the workflow

1. Submit the customer form.
2. Choose **Request confirmation** on an airport result.
3. Switch to **FBO team** with the selector in the top bar.
4. Try **Request more information** or **Approve for final confirmation**.
5. Switch back to **Customer portal** to see the updated status.

## Project structure

| File | Purpose |
| --- | --- |
| `index.html` | The whole site (both portals) |
| `app.js` | All behaviour: matching, request relay, chat, scenario planner |
| `styles.css`, `enhancements.css`, `portal-selector.css`, `simple-ui.css`, `customer-chat.css`, `scenario-visual.css` | Styles, loaded in this order. Colors live in the `:root` block of `styles.css`. |
| `heavy-business-jet-transparent.png` | Hero image |
| `RESEARCH-SOURCES.md`, `FEE-RESEARCH.md` | Sources behind the planning context and fee model |
| `AEROGREEN_SLIDE.pdf` | Presentation slides |

## Run locally

Open `index.html` in a browser.

## Credits

Built as a prototype for the NCBAA hackathon.
