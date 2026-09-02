# NSPYR → Elevate Advisory Consulting — Credit Referral Form

Internal tool for the NSPYR sales team. When a homeowner is declined for solar
financing because of credit, the rep fills out `index.html` and the lead is sent
to Elevate Advisory Consulting (credit repair). Elevate works the file and
notifies the rep when the customer is ready to re-apply.

Open `index.html` in a browser. The logo lives at `assets/nspyr-elevate-logo.svg`.


The form itself is the GoHighLevel form `tcMZuG7mrLkscqJ2Cj2c`, embedded inline.
Submissions go straight to that GHL location; no endpoint configuration needed.

`builder/styles.css` and `builder/referral-block.html` are copy-paste versions
for a page builder (scoped under `.nspyr-referral`).

## Client signup page

`signup.html` is the client-facing version: same branding, with the Dispute
Process signup form inline (transparent background, white labels; redirects to MyFreeScoreNow enrollment on completion). Builder copies live at
`builder/signup-styles.css` and `builder/signup-block.html` (scoped under
`.nspyr-signup`).
