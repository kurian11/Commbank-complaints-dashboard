Commonwealth Bank Complaints Dashboard

An interactive overview of Commonwealth Bank's customer complaint performance across Australia, built as a single self-contained HTML file — no backend, no build step, all data embedded.

Live demo: https://kurianthomas1001.github.io/commbank-complaints-dashboard/ (update this link once GitHub Pages is enabled)

Overview

The dashboard reproduces a stakeholder wireframe as a working BI tool. It tracks executive-level KPIs alongside complaint trends, channel and annual breakdowns, and a state-level view on an interactive map of Australia. Every filter and every chart or map click cross-filters all panels at once, and the KPIs recompute live — so you can drill from a national summary down to a single state, product or year in one click.

KPIs
KPI	Definition
Total complaints	Record count in the current filter
Timely-response rate	% of complaints with a timely response
Disputed rate	% where the consumer disputed the outcome
Resolved with relief	% closed with monetary or non-monetary relief
Open (in progress)	Count of cases still in progress
Top issue	Most frequent complaint issue in the current filter
Features
Bidirectional cross-filtering — dropdown filters, chart bars, and map states all filter every other panel
Six live KPI cards that recompute against the active filter set
Visualisations: request-channel bar, monthly complaint-trend line, annual breakdown bar, and a clickable state map
Responsive down to mobile
Accessible — ARIA labels, keyboard-operable controls, visible focus states, WCAG AA contrast
Tech
Vanilla JavaScript — no front-end framework
Chart.js (via CDN) for the bar and line charts
Hand-built inline SVG tile-map for state-level filtering
Python (pandas) used to profile and prepare the dataset, then embed it as JSON
Data

467 complaint records spanning 2011–2020, with fields covering product, sub-product, issue, request channel, state, company response, timeliness, dispute status and resolution status.


Personal portfolio project built from a Commonwealth Bank–styled BI brief using synthetic sample data. Not affiliated with or endorsed by Commonwealth Bank; the logo is used illustratively.
