# Hi, I'm Nadia 👋

Data Analytics Engineering grad student at Northeastern. I work on turning messy,
disconnected business data into something a commercial team can actually make
decisions from.

## Currently

**Data Analytics Intern — Commercial Excellence, Archroma** (Charlotte, NC)

I'm on the Packaging Technologies commercial excellence team, where my main project
is a customer master reconciliation: joining SAP customer data, an internal register
of several thousand paper mill sites, and a third-party market dataset into a single
Power BI star schema — so the commercial team can see, for the first time, which
mills in the world it isn't selling to.

What that's involved:

- **Entity resolution across systems with no shared keys.** Name-only matching
  produced false positives at scale, so I built a corroboration rule requiring
  company name plus city, postcode, and street overlap before a match is accepted.
- **A human review queue instead of auto-fill.** Around a thousand ambiguous records
  get surfaced for sales-team review rather than written silently into the master.
  Data that joins cleanly but attaches figures to the wrong entity is worse than a
  blank field.
- **Dimensional modeling for Power BI** — two fact tables, eight dimensions, a
  documented data dictionary, and an open defect log with severity and owner.
- **An AI matching assistant I scoped and built myself** — an LLM-backed tool that
  drafts proposed matches for the review queue, with a human approving every one.
- **Documentation and runbooks**, since the team has no data engineering function
  and everything I build has to be maintainable without me.

Specific figures, account names, and the market data source are confidential.

## Tools
Python (pandas, NumPy, scikit-learn) · SQL · Power BI · Excel · Git · Jupyter
