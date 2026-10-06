# Public publishing checklist

## Purpose

Publish useful lessons that readers can understand and reproduce. Keep business/customer operations separate from educational examples.

## Workflow

1. Propose a topic in the appropriate public guide repository and identify the learner and outcome.
2. Draft with its templates/tutorial.md. Prefer a new minimal example using fictional data over copying internal configuration.
3. Review every file, image, command output and commit proposed for publication. Exclude credentials, customer identifiers, private hostnames/addresses, private locations, internal links and operational incident details.
4. Use material you have permission to publish. Attribute upstream sources and preserve any applicable notices. Record the license for any third-party example; do not assume public visibility grants reuse rights.
5. For executable labs, run the exact instructions in a clean, authorized environment. Record software/hardware versions, date, expected output, failure cases, cleanup and resource costs. Mark untested work as draft.
6. Have a maintainer review the public diff for accuracy, learning value, evidence and publication suitability before merging.
7. Update the path README and roadmap. Review lessons when their dependencies change and mark outdated material clearly.

## Content states

- **Concept exercise:** educational reasoning/planning; no execution claim.
- **Draft lab:** instructions under development, not validated.
- **Tested lab:** exact environment, date and results recorded.
- **Archived:** retained for context, no longer maintained.

## Boundaries

Do not make an existing private repository public as a publication shortcut. A clean example should not carry private commit history. There is no automatic mirroring or deployment in this framework.

## Licensing

No repository-wide reuse license has been selected for this initial framework. Choose and review an appropriate license before describing these repositories as open-source distributions or accepting substantial external contributions.
