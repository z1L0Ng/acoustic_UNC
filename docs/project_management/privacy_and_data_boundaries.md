# Privacy And Data Boundaries

This project may involve clinical collaborators and health-related acoustic signals. Until formal approvals and data-use rules are confirmed, use the conservative boundary below.

## Do Not Commit

- PHI or patient identifiers.
- Raw clinical audio recordings.
- Raw clinical metadata exports.
- Consent forms or recruitment records.
- Private collaborator emails.
- Access tokens, credentials, or private data links.

## Acceptable In Git

- Public paper citations and links.
- Public dataset metadata and download instructions.
- De-identified aggregate summaries.
- Experiment code and configuration.
- Synthetic examples that cannot identify a person.
- Meeting briefs with sensitive details removed.

## Local-Only Paths

The following paths are ignored by Git and can be used for local staging only if needed:

- `materials/private/`
- `data/private/`
- `data/raw/`
- `data/clinical/`

Before moving any local material into tracked documentation, remove names, identifiers, patient details, private contact information, and unpublished sensitive content.

