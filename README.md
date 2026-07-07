# <repo-name>

<one-line description>

## Governance

This repository is part of the `traverse-framework` organization and follows the
org-wide governance pinned in `.governance-version` — see
[traverse-framework/.github](https://github.com/traverse-framework/.github).

Template checklist for a new repo:

- [ ] Replace this README's placeholders.
- [ ] Add your first approved spec to `specs/governance/approved-specs.json`,
      then wire `scripts/ci/spec_alignment_check.sh` into your CI on pull
      requests (see an existing repo's `ci.yml` for the invocation).
- [ ] Add package ecosystems to `.github/dependabot.yml` (cargo, npm, ...).
- [ ] Confirm the `traverse-governance-baseline` ruleset is applied
      (`scripts/org/apply_rulesets.sh` in the .github repo).

## License

Apache-2.0 — see [LICENSE](LICENSE). Contributions require the
[org CLA](https://github.com/traverse-framework/.github/blob/HEAD/CLA.md).
