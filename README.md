# Mathai Fenn Publishing

This repository is the portable working archive for Mathai Fenn's publishing ecosystem.

## Structure

- `content/` — Complete Obsidian vault and source of written work.
- `content/public/` — Notes selected for publication through Quartz.
- `quartz/` — Quartz static-site project that publishes `content/public/`.
- `site/` — Hand-authored HTML pages for the main Mathai Fenn website.

## Publishing model

The complete Obsidian vault is maintained in this repository so that the
working environment can be reproduced on any machine.

Moving a note into `content/public/` is the decision to make that note
available to the Quartz thought cloud.

Quartz publishes only `content/public/`. Other vault content remains
unpublished by Quartz, although the repository itself is public.

## Related architecture

The detailed publishing architecture is maintained separately from this
repository.
