# NSPYR → Elevate Advisory Consulting — Credit Referral Form

Internal tool for the NSPYR sales team. When a homeowner is declined for solar
financing because of credit, the rep fills out `index.html` and the lead is sent
to Elevate Advisory Consulting (credit repair). Elevate works the file and
notifies the rep when the customer is ready to re-apply.

Open `index.html` in a browser. The logo lives at `assets/nspyr-elevate-logo.svg`.

To deliver submissions, set `ENDPOINT` in `index.html` to Elevate's intake URL
(e.g. a GoHighLevel form or inbound webhook). The form POSTs JSON with rep,
customer, and decline-detail fields.
