# Contributing

This is the account-wide default `CONTRIBUTING.md`, inherited by any
repository under this account that doesn't define its own. If a repository
has its own `CONTRIBUTING.md`, that one applies instead — check there first.

## General workflow

1. Fork the repository and create a branch off `main`: `<type>/<short-slug>`
   (e.g. `fix/off-by-one-in-parser`, `feat/csv-export`).
2. Make one logical change per branch and per pull request. If the change
   needs "and" to describe it, split it into two.
3. Follow [Conventional Commits](https://www.conventionalcommits.org/) for
   commit messages: `<type>(<scope>): <imperative summary>`, e.g.
   `fix(parser): handle trailing comma in CSV rows`.
4. Run the project's build, lint, and test commands before opening a pull
   request — see the repository's own README or `package.json`/`Makefile`
   for the exact commands, since they vary per project.
5. Open a pull request against `main` describing what changed and why. Keep
   pull requests under roughly 400 changed lines where possible — smaller
   changes get reviewed faster and with fewer defects.
6. Be responsive to review feedback. A pull request that goes silent for an
   extended period may be closed and can be reopened later.

## Reporting bugs and requesting features

Use the repository's issue templates. Include steps to reproduce, expected
vs. actual behavior, and enough environment detail (OS, version, etc.) for
someone else to reproduce the problem.

## AI assistance disclosure

Some repositories under this account are maintained with AI assistance
(Claude, via Lumen Industries automation) alongside direct human work. Where
that's the case:

- Commits authored with AI assistance carry an
  `Assisted-by: Claude (Anthropic) via Lumen Industries automation` footer,
  never a `Co-authored-by:` trailer naming the AI — that trailer implies an
  authorship status we don't claim.
- AI-assisted pull requests are reviewed against the project's tests before
  submission, and a human remains accountable for every change that ships.
- If a repository's own policy imposes additional AI-disclosure or
  AI-contribution rules, that policy takes precedence over this one.

This disclosure exists so contributors and reviewers know what they're
looking at. It isn't a claim that AI-assisted contributions are held to a
different bar — the same review and testing standard applies to all of them.

## Code of Conduct

Participation in this project is governed by the
[Code of Conduct](./CODE_OF_CONDUCT.md).
