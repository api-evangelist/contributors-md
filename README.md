# CONTRIBUTORS.md (contributors-md)

CONTRIBUTORS.md is an open source convention used to recognize the people and organizations that have contributed to a project. The file lists contributors by name, GitHub handle, and contribution type, ranging from code and documentation to design, testing, accessibility, and community organization. CONTRIBUTORS.md is often paired with the All Contributors specification, which standardizes contribution categories using emoji keys and supports automated table generation through the All Contributors bot.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/contributors-md/refs/heads/main/apis.yml)

## Type

- **x-type:** standard

## Tags:

 - All Contributors, Attribution, Community, Documentation, GitHub, Markdown, Open Source, Recognition

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### CONTRIBUTORS.md Format

The CONTRIBUTORS.md format is a Markdown convention that lists project contributors and the kinds of contribution they have made. Many projects adopt the All Contributors specification, which uses emoji keys to classify contributions, an embedded HTML table to render the contributor list, and a .all-contributorsrc JSON config file consumed by the All Contributors bot to automate updates.

**Human URL:** [https://allcontributors.org/](https://allcontributors.org/)

#### Tags:

 - Attribution, Convention, Markdown, Recognition

#### Properties

- [Reference](https://allcontributors.org/)
- [Specification](https://allcontributors.org/docs/en/specification)
- [Documentation](https://allcontributors.org/docs/en/emoji-key)
- [Repository](https://github.com/all-contributors/all-contributors)

#### Features

- Recognizes non-code contributions including design, docs, and review
- Compatible with the All Contributors emoji key specification
- Automatable through the All Contributors GitHub App or CLI
- Renders as an HTML table with avatars and contribution badges
- Pairs with CONTRIBUTING.md and CODE_OF_CONDUCT.md

#### Use Cases

- Public attribution of every project contributor
- Recognizing accessibility, translation, and design contributions
- Automating contributor table updates via @all-contributors bot
- Demonstrating an inclusive open source community to sponsors
- Tracking contribution categories beyond commit history

### All Contributors Specification

The All Contributors specification defines a JSON schema (in .all-contributorsrc) plus a Markdown rendering convention that captures every contributor name, GitHub login, avatar URL, profile URL, and the list of contribution types using a defined emoji key. Tooling can regenerate the contributor table on demand and synchronize updates back into both .all-contributorsrc and CONTRIBUTORS.md or README.md.

**Human URL:** [https://allcontributors.org/docs/en/specification](https://allcontributors.org/docs/en/specification)

#### Tags:

 - Attribution, Specification, Standardization

#### Properties

- [Specification](https://allcontributors.org/docs/en/specification)
- [Documentation](https://allcontributors.org/docs/en/emoji-key)
- [Repository](https://github.com/all-contributors/all-contributors-cli)
- [Documentation](https://allcontributors.org/docs/en/cli/usage)

#### Features

- Defines a contribution type emoji key with 30+ categories
- JSON config schema in .all-contributorsrc as machine readable source
- CLI plus GitHub bot for adding contributors with a comment command
- Backed by an OSS community since 2017

#### Use Cases

- Standardizing contributor recognition across multiple projects
- Auditing contribution categories programmatically
- Generating contributor tables in README or CONTRIBUTORS files
- Recognizing accessibility, infrastructure, and security contributions

## Common Properties

- [Reference](https://allcontributors.org/)
- [Specification](https://allcontributors.org/docs/en/specification)
- [Documentation](https://allcontributors.org/docs/en/emoji-key)
- [Repository](https://github.com/all-contributors/all-contributors)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
