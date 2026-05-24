# agent-skills changelog

## 0.2.0

### Minor Changes

- 7f2be04: Initial npm release. Ships the full skills catalog, agent personas, slash
  commands, and pi extensions as an installable package, with a thin CLI
  (`npx agent-skills init`) that hands off to the LLM-driven
  `guided-workspace-setup` skill. Adds version-aware updates: the install record
  now embeds the package version, and re-running `/setup` after a version bump
  surfaces a per-artifact three-way diff (source@recorded vs installed copy vs
  source@current) before touching any file.

All notable changes to this project are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versioning follows
[Semantic Versioning](https://semver.org/spec/v2.0.0.html). Entries below 0.1.0
are pre-npm history captured in git.

The file is rolled forward by [changesets](https://github.com/changesets/changesets) —
do not edit it by hand. Add a `.changeset/<name>.md` file describing your
change and let `changeset version` aggregate it.

## Unreleased

Pending changesets in `.changeset/` will roll into the next release.
