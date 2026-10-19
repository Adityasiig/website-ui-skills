# Website UI skills

A private reference collection of the original skill documents used during the
portfolio redesign. The copied skill files are unchanged; this is not a custom
rewrite of their instructions.

## Start here

| Document | Purpose |
| --- | --- |
| [Sites skill](skills/sites/SKILL.md) | Website implementation, preview, and Sites publishing workflow |
| [Presentation-led design](skills/sites/references/design/presentation-led.md) | Page composition, content structure, and visual direction |
| [Imagegen skill](skills/imagegen/SKILL.md) | Raster artwork generation and editing |
| [Image prompting guidance](skills/imagegen/references/prompting.md) | Image composition and prompt construction |
| [Image prompt examples](skills/imagegen/references/sample-prompts.md) | Examples for different asset types |

The remaining reference documents are stored alongside each skill so their
documentation links retain their original structure.

## Runtime dependencies

These are instruction and reference files. They do not themselves provide the
tools they describe. Sites depends on the Codex Sites plugin, its native tools,
and its helper scripts. Imagegen's preferred path depends on the built-in image
tool; its optional CLI path needs the corresponding upstream script and runtime.
Plugin helpers, templates, executable scripts, account settings, credentials,
and the portfolio's source files are not included in this collection.

## Source and notices

- Sites files were copied from the installed OpenAI Sites plugin, version
  `1.0.2-remix-b.1`. Its package declares `Proprietary`; the original package
  attribution and licensing metadata are retained in
  [UPSTREAM.json](skills/sites/UPSTREAM.json).
- Imagegen files were copied from the installed OpenAI Imagegen skill. Its
  [Apache License 2.0](skills/imagegen/LICENSE.txt) is retained alongside them.

This repository is a personal reference copy, not an official OpenAI repository.
No repository-wide license changes the terms of the included components.
