# Hi, I'm Nadia 👋

Data Analytics Engineering grad student at Northeastern. I work on the part of
analytics that decides what not to trust.

## Currently

**Data Analytics Intern — Commercial Excellence, Archroma** (Charlotte, NC)

My main project is a customer master reconciliation: joining three source systems
that had never shared a key into a single reconciled view.

What that's involved:

- **Entity resolution across systems with no shared keys.** Name-only matching
  produced false positives at scale, so I built a corroboration rule requiring
  company name plus geographic agreement before a match is accepted.
- **A human review queue instead of auto-fill.** Around 1,080 ambiguous records
  get surfaced for review rather than written silently into the master. Data that
  joins cleanly but attaches figures to the wrong entity is worse than a blank field.
- **Dimensional modeling** with a 203-field data dictionary and a 31-item defect
  log carrying severity and a named owner per entry.
- **Documentation and runbooks**, since the team has no data engineering function
  and everything I build has to be maintainable without me.

Specific figures, account names, and the market data source are confidential.

## Also

**Fraqt** — data and systems design on a pre-launch AI compliance tool. Structured
1,194 public federal passages against relevance, completeness, and consistency
criteria, and designed change detection so superseded guidance gets flagged rather
than served.

**Northstar Insight Group** — co-founded a research and reporting studio. Reviewed
100+ client materials for source accuracy, spreadsheet logic, chart clarity, and
editorial quality, logging 80+ issues with evidence, severity, and corrections.

## Projects

**[Diamond Price Drivers](https://github.com/nadiasrana/diamond-price-drivers)** —
918 pear-shaped diamonds across four retailers. Three regression bases reported
separately, because aggregating grade averages inflates the fit and reverses the
slopes. The limitations section is the point.

## Tools

**In production work:** SQL · Power BI (DAX, Power Query) · Excel · SAP · SPSS

**Also work with:** Python (pandas, NumPy, scikit-learn) · PostgreSQL · R · Git 

## Methods

Entity resolution · data quality and validation · defect logging · structured
evaluation · rubric adherence · source verification · regression · KPI reporting

[nadiasrana.github.io](https://nadiasrana.github.io) ·
[LinkedIn](https://linkedin.com/in/nadiasrana)
