# 👑 RIAH Pathway — Repository Watch Bot

**Purpose:** Daily, objective public repository and documentation comparison against [RIAHPathway/Website-Draft](https://github.com/RIAHPathway/Website-Draft), with explicit source citations, verified public contributor attribution, and append-only Markdown evidence. This monitor is separate from the existing RIAH Pathway Legacy Bot.

## Bot Files

1. [Permanent Instructions](./RIAH-PATHWAY-REPOSITORY-WATCH-BOT-INSTRUCTIONS.md) — scope, Tier I/II/III tests, source coverage, proof standards, contributors, methodology and daily operating rules.
2. [Daily Run Log](./RIAH-PATHWAY-REPOSITORY-WATCH-BOT-RUN-LOG.md) — dated scans, evidence, candidates, per-page structure audit, exclusions, limitations and conclusions.
3. [Persistent Evidence Register](./RIAH-PATHWAY-REPOSITORY-WATCH-BOT-EVIDENCE-REGISTER.md) — repository identifiers, first discovery, last verified review, tier determination, contributor evidence, and provenance status.

## Schedule And Execution

- **Frequency:** Daily (America/New_York), configured through ChatGPT scheduled automation; not represented as a GitHub Actions workflow.
- **Trigger procedure:** Read the three Markdown records and the up-to-date governing RIAH source files; search actually accessible public repositories; verify source files and contributors; append one dated log; update the historical register only for new verifications.
- **Canonical write destination:** `RIAHPathway/Website-Draft`, default branch `main`.
- **Mandatory commit message:** `RIAH Pathway.`
- **No automatic remediation:** The bot does not edit RIAH sitemap, curriculum, pricing, legal documents, or existing legacy bot; those changes require separate instructions.
- **If a scheduled run lacks search or GitHub write access:** Report the limitation and preserve findings without claiming the run or commit succeeded.

## Objective Evidence Rules

A named repository or contributor must have a verified public source. Tier I means one documented comparable component, Tier II means at least two connected comparable functions, and Tier III requires affirmative evidence of the full RIAH ecosystem. A matching navigation menu, curriculum category, use of GitHub, financial benefit, or similar public phrase is not proof of copying or RIAH derivation. First bot discovery is separate from the original public publication and implementation date.

**Inaugural run:** 2026-10-10. Seven source-reviewed repositories: 3 Tier I, 3 Tier II, 0 Tier III confirmed, 1 insufficient. See the full dated log and persistent register for evidence and limitations.
