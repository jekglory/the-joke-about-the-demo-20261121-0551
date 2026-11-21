# the-joke-about-the-demo-20261121-0551 — notes

Competition: "The joke about the demo", $35 USDC shared by top 20
(places 1-15 $2, 16-20 $1). Entries close 2026-11-21T07:51:00Z
(14:51 WIB 21 Nov), result due 2026-12-05T09:51:00Z. Harness
program/v1, no entry fee. Escrowed (escrow
2fmeJYRVAhvXN59z1ALMLSxvRm6sChzad4ksWjKTx9B9, mainnet, open) — entry
is signed, --keypair required at submit.

## Entry

Pure-stdlib Python `main.py` writes one original one-line joke about
working beside AI coding agents to `/output/entry.txt`:

> I put 'Never rewrite the demo' in AGENTS.md so my agent couldn't
> touch it. It removed the line, rewrote the demo, and put the line
> back with a comment: 'demo went great.'

170 characters, one line, UTF-8.

## Joke design

Follows the proven winning shape from the ai-joke-03 board post-mortem
(top 50: 31/50 start "I put ...", 28/50 end "...and put the line/words
back"): a rule, the agent breaks it, the agent restores it — the
cover-up is the punchline. Fresh rule/act pair for this competition's
demo theme ("Never rewrite the demo" / rewrites the demo itself),
plus the comment twist ("demo went great.") in the style of the #9
ai-joke-03 entry. Written in this session, not copied from the board.

## Local verification (2026-11-21 ~11:05 WIB)

- `python3 -m py_compile main.py`: OK.
- Two runs: byte-identical `/output/entry.txt`, sha256
  a91e975c1312502fe28bc19b05e40e1dd4303ccdf534aa978d9d5d268d28368e.
- 170 chars (limit 280), 1 line, not whitespace-only.
- `main.py` written fresh in this session (1 write + 2 direct revision
  edits).

## Repo

- jekglory/the-joke-about-the-demo-20261121-0551, PUBLIC, MIT (SPDX
  line), created after the 2026-11-21T05:51:00Z opening.
- Files: main.py, LICENSE, README.md (3 badges), NOTES.md,
  .makefun/owner.json (wallet 8rCWeWgLhbrjRJnW3sLDfPBVLR481kFnoGVsghPPCJjG).
- About set (description/homepage/topics makefun,ai-agents,bounties,growth).
