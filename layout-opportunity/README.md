[README.md](https://github.com/user-attachments/files/32105754/README.md)
# Opportunity Page Layout — Redesign Prototypes

Interactive prototypes exploring a redesigned Salesforce **Opportunity** record page, built from the 9 September 2026 stakeholder review (Ben Partridge, Shari De Souza).

## What's here

Two directions, testing whether the Path (stage accordion) should stay permanently open or default to collapsed:

- **01 · Path Open** — Path stays expanded, showing Key Fields (Amount, Close Date, Payment Terms) and Guidance for Success at all times. Amount and Close Date are removed from the Details tab below to avoid duplication.
- **02 · Path Collapsed** — matches today's default behaviour. A new **Key Details** section reopens Stage, Probability, Amount and Close Date at the top of the Details tab.

## Key changes reflected

- **Amend Opp** button removed from open opportunities (was causing duplicate-opportunity errors)
- **Assets** removed from the top quick links, kept only as a sidebar widget
- **CSAT tab renamed to Notes**, now also housing the Notes related list
- **Guidance for Success** text corrected: outdated automation bullets removed, Burst reference generalised, Internal Review fixed to 75%, External Review fixed to 90% and its stray bullet deleted
- New **Quote Information** (renamed from CPQ Information), **Renewal Information** and **Licensing** sections
- PO Number / Job Number moved into Finance Information
- Several fields flagged rather than removed pending validation: Total Contract Value, Stems Requested, Custom Project Id, On Behalf Of

Full rationale and open actions are in the "Design notes" artboard inside the prototype.

*Built with Claude Design — HTML mock-up for layout validation, not connected to live Salesforce data.*
