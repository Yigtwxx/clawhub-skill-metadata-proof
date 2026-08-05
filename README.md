# clawhub-skill-metadata-proof

Throwaway caller repository for one ClawHub pull request: it proves that the
reusable `skill-publish.yml` workflow forwards `changelog`, `categories`, and
`topics` to `clawhub skill publish`, and that omitting those inputs adds no
flags.

Both jobs in `.github/workflows/proof.yml` hardcode `dry_run: true`, use no
repository secrets, and pin the ClawHub branch by full commit SHA. Nothing here
publishes anything.
