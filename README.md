\# IAM Controls Evidence Toolkit



Map IAM controls to audit evidence, and pull that evidence with scripts.



\## The problem



Audit season usually means manual screenshots, ad-hoc spreadsheets, and scrambling to prove

that access reviews, joiner-mover-leaver processes, and privileged access controls actually

work — not just that they exist on paper. This toolkit turns that into a repeatable process.



\## Who this is for



IAM engineers, GRC/audit teams, and anyone who needs to map identity controls to compliance

frameworks and pull supporting evidence from Okta or SailPoint (ISC and IIQ).



\## What's inside



\- `controls/` — a master control list mapped to SOX, PCI DSS v4.0, DORA, and DPDPA, with the

&#x20; Okta / SailPoint ISC / SailPoint IIQ source for each

\- `evidence/` — scripts that pull evidence directly from Okta and SailPoint (ISC, IIQ)

\- `guides/` — how-to docs: ideal JML flow, role mining, pulling access review evidence

\- `architecture/` — notes and diagrams on IAM architecture at enterprise scale

\- `samples/` — synthetic sample output only — no real tenant data, ever



\## Quick start



1\. Set up a free developer tenant (Okta Developer Edition, or SailPoint's developer sandbox)

2\. Set your API credentials as environment variables (see each script's header comment)

3\. Run a script, e.g. `python evidence/okta/inactive\_accounts.py`



\## Disclaimer



All sample data in this repo is synthetic. This toolkit is for reference and portfolio

purposes only — it is not legal, compliance, or audit advice, and contains no material from

any employer.



\## Roadmap



\- Microsoft Entra ID evidence scripts

\- CyberArk architecture notes

\- Additional frameworks (ISO 27001, RBI/SEBI guidelines)



\## About



Built by Poulami, Senior IAM Engineer. \[LinkedIn] · \[Website]



\## Contributing



See `CONTRIBUTING.md`.

