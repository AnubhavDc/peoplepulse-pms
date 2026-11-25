# PeoplePulse | Performance intelligence
An open-source academic Performance Management System (PMS) prototype for fictional NexaWorks. Runs entirely in the browser, without dependencies, accounts or paid services. Open index.html in a browser or serve it with any static HTTP server.

## Demo walkthrough
1. HR administrator: explore company KPIs, departments, trends and priority coaching actions.
2. People: search Neha Rao, open her profile and ask Pulse about improvement.
3. Switch to Engineering team manager, then Employee (Riya Sharma or any fictional employee). Compare scope, goals, feedback and coaching.
4. Record a check-in, add a SMART goal, explore the 9-box matrix, export CSV. These are simulated actions, stored locally; added goals and notes do not change the synthetic scores.
5. Use the quarter selector to compare historical fictional data.

## Publish on GitHub Pages
Create a public repository named peoplepulse-pms at https://github.com/new. Upload index.html, LICENSE, README.md (not the containing folder) to the root and commit to main. Go to Settings > Pages > Build and deployment > Deploy from a branch > main > / (root) > Save. Open the address displayed by GitHub when deployment succeeds. See https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site.

## Data and design
18 fictional employees; six departments; four quarters of synthetic scores. Score weights: goals 50%, competencies 25%, feedback 15%, development 10%. Scores rounded to nearest integer. Thresholds are assumptions, not vendor standards. CSS perspective, shadows, animated 3D-style orb, charts and responsive layout. All data is fictional; role switching is not secure access control. Pulse AI is a deterministic, local intent and recommendation engine (not a real LLM). No automated adverse employment decisions. Never enter real employee data into the public demo. No external services or telemetry. MIT license.

## Research inspiration (not vendor affiliation or a clone)
- Deloitte People Analytics: https://www.deloitte.com/in/en/services/consulting/services/human-capital/people-analytics.html
- Deloitte OrgAtlas: https://www.deloitte.com/in/en/about/story/OrgAtlas.html
- IBM AskHR: https://www.ibm.com/case-studies/ibm-askhr
- SAP SuccessFactors Performance & Goals: https://www.sap.com/products/hcm/performance-goals.html
