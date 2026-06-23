# CLAUDE.md — neo-candy-tela-purple

## Project overview

Standalone repo for the **neo-candy-tela-purple** folder-icon theme — the same folder set as
`erikdubois/surfn-tela-purple` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-tela-purple/` — folders only. Packaged as `neo-candy-tela-purple-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-tela-purple/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
