# azure-lab-indexer

A repo that aggregates and scores various Azure labs for quality/usability.

## premise

It's often hard to seperate great vs ok labs.
Great labs should be ranked and more visible than weaker labs.
Let's rate and index those labs!

## scoring criteria

- READABILITY (poor spelling, markdown linting, grammar, etc)
- FRESHNESS (last commit)
- FRESHNESS (if IaC, date of APIVersions)
- FRESHNESS (dependencies up to date)
- LAB-TYPE (CLI / IaC / ClickOps)
- Hosting Organisation (Personal VS Org)
- Localisation (Fixed to language / Genericised)
- FILE-TYPES (binaries = bad)
- TEAM (maintaining team breadth)
- Individual page LENGTH
- Commit messages (Readable / Conventional)
