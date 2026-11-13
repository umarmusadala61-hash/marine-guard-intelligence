Marine Guard Intelligence: SeaSentinel Demo Console

Proof-of-concept demo for the NIMASA Blue Economy Accelerator Programme (NIMASA-BEAP) 2026.

All data is simulated. Vessels, identities, positions and sea conditions are generated in the browser. Nothing here is live surveillance, and alerts flag patterns for human review. They do not prove wrongdoing.

**What it shows**
Sea map with moving vessels, an offshore platform zone and a port
Rule-based alerts: AIS gap, loitering, off-expected-route, identity conflict, predicted close encounter (closest point of approach)
Vessel profiles with simulated sea conditions and an investigation report
**Run locally**

Open index.html in a browser. It is one self-contained file with no dependencies.

**Host on GitHub Pages**
Create a new repository and upload index.html and README.md.
Go to Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select main and / (root), then save.
After a minute or two the site appears at https://<your-username>.github.io/<repo-name>/.
Where to edit
Vessels, routes and scenarios: the V array near the top of the script
Detection rules: the detect() function
Map drawing and layout: the SVG markup and CSS
**Planned (not built)**
Real AIS and ocean-condition data sources (licensing to be confirmed)
Customer voyage plans for expected-versus-actual comparison
API for pushing alerts into customers' security tools
