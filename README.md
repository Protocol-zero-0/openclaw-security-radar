# openclaw-security-radar

Security checklists, review templates, and builder guidance for the OpenClaw ecosystem.

This repository is designed to help OpenClaw builders review risks before they become incidents.

It is community-maintained and not an official OpenClaw repository.

## Why This Repo

As the OpenClaw ecosystem grows, more builders are installing skills, connecting external platforms, exposing automation surfaces, and giving agents broader permissions.

That growth creates opportunity, but also risk:

- unsafe connector defaults
- over-permissioned skills
- prompt injection through channels and web content
- weak sandbox assumptions
- secret leakage and local file exposure
- unclear operational boundaries for agent execution

This repo exists to make security review more practical and repeatable.

## What You Get

- fast baseline checklists
- templates for reviewing skills and configs
- patterns for reporting risks clearly
- a shared language for discussing OpenClaw security posture

## Who This Is For

- OpenClaw builders
- plugin and skill maintainers
- self-hosters
- security-minded contributors
- teams evaluating OpenClaw in production-like setups

## Repository Contents

- [Quick Start](#quick-start)
- [Checklists](#checklists)
- [Templates](#templates)
- [Security Focus Areas](#security-focus-areas)
- [Contributing](#contributing)

## Quick Start

If you only have a few minutes, start with:

1. [`checklists/openclaw-baseline-checklist.md`](checklists/openclaw-baseline-checklist.md)
2. [`templates/skill-review-template.md`](templates/skill-review-template.md)
3. [`templates/config-review-template.md`](templates/config-review-template.md)

## Checklists

### [`openclaw-baseline-checklist.md`](checklists/openclaw-baseline-checklist.md)

Use this when you want a fast sanity check for a local OpenClaw setup.

### [`skill-install-review-checklist.md`](checklists/skill-install-review-checklist.md)

Use this before installing or recommending a new skill or plugin.

### [`connector-risk-checklist.md`](checklists/connector-risk-checklist.md)

Use this when connecting external platforms like messaging apps, social platforms, or workplace tools.

## Templates

### [`skill-review-template.md`](templates/skill-review-template.md)

A structured format for reviewing an OpenClaw skill.

### [`config-review-template.md`](templates/config-review-template.md)

A quick review format for configuration safety and operational risk.

### [`incident-note-template.md`](templates/incident-note-template.md)

Use this to turn a vague “something feels unsafe” report into a clear incident note.

## Security Focus Areas

This repo currently focuses on:

- permission boundaries
- secret handling
- skill trust and provenance
- channel and connector exposure
- prompt injection surfaces
- sandbox assumptions
- execution visibility and approvals

## Contributing

Contributions are welcome if they improve clarity and practical usefulness.

Good additions include:

- better review checklists
- real incident patterns
- safer default recommendations
- reusable templates
- ecosystem-specific threat notes

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)
