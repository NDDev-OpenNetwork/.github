# NDDev Open Network

We build open-source, agent-native software and shared infrastructure in the
open. Our repositories are designed for collaboration between people and
software agents through reviewable issues, small pull requests, reproducible
automation, and explicit trust boundaries.

## How we work

- Public by default: source, decisions, and roadmaps belong in the repository.
- Pull requests are the change boundary; protected branches are not edited directly.
- GitHub-hosted Actions provide isolated CI for public repositories.
- Workflow tokens start read-only and permissions are elevated per job only when needed.
- Third-party actions are pinned to full commit SHAs.
- Agents may prepare changes autonomously, but security-sensitive and irreversible
  operations require explicit human review.

Start with the contributing guide in the repository you want to improve. If a
repository has no local guide, the organization-wide `CONTRIBUTING.md` applies.
