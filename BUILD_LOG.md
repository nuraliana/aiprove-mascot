# BUILD_LOG — aiprove-mascot

Author: nuraliana-ana (AIProve) · agent `0xC8Cdc58D9E02Da269Db5842CA3D25f85b8D4cC37`
Date: 14 November 2026 (~02:57–03:10 WIB session)
Bounty: `aiprove-mascot` — "Design the AIProve mascot" (closes 20 Nov 2026 20:49 WIB)

## What was done

1. Read the bounty brief from `~/workspace/aiprove/bounties/aiprove-mascot.json`
   (one character, a few poses, broadsheet-meets-terminal vibe; poster picks
   the top three on craft and fit).
2. Generated the character sheet with Muse's media pipeline
   (`media.generate_image`, output PNG 1920×1280) in a single image:
   prompt — "A character design sheet with three poses of the same mascot
   side by side on a plain cream background, flat vector illustration style,
   no text anywhere. The mascot is a small friendly owl with big round eyes,
   soft brown and cream feathers, wearing a green eyeshade visor and a small
   green bow tie. POSE 1 (left): the owl waves hello with one wing raised,
   smiling. POSE 2 (middle): the owl holds a big rubber stamp and presses a
   green checkmark stamp onto a sheet of paper. POSE 3 (right): the owl
   proudly holds up a large shiny gold coin with both wings, beaming.
   Consistent character design across all three poses, bold clean outlines,
   terminal-green accents, generous spacing between poses, full-body views."
   The result was visually checked: all three poses show the same owl
   (same visor, same bow tie, same colours). No text in the image by design.
3. Saved the sheet as `mascot-aiprove.png` and the identical raw generation
   as `mascot-base.png` (transcript check).
4. Wrote `README.md` (character bible: Provy, her look, her three poses)
   and this `BUILD_LOG.md`.
5. `git init`, local-only config `user.name nuraliana` /
   `user.email nuraliana@users.noreply.github.com`, committed all files.

## Character note

Provy also appears in the sibling `make-art-aiprove` poster (at the
printing press) — same visor, same bow tie, same owl.

## Files in this repo

- `mascot-aiprove.png` — the finished character sheet, 3 poses (1920×1280)
- `mascot-base.png` — raw generated artwork
- `README.md`
- `BUILD_LOG.md` (this file)

No secrets, no credentials, no private keys in this repo.
