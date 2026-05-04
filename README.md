# Codex Pet: Yukino Yukinoshita

This repository contains a custom Codex animated pet inspired by Yukino Yukinoshita.

The pet is packaged for local Codex use as a compact chibi, pixel-adjacent sprite with a winter palette, long dark hair, navy scarf, black coat, plaid skirt, and a calm reserved expression.

## Files

- `pets/yukino/pet.json` - Codex pet manifest.
- `pets/yukino/spritesheet.webp` - Validated 8x9 animated pet atlas.
- `qa/contact-sheet.png` - Visual QA contact sheet for all animation rows.
- `qa/review.json` - Frame inspection output.
- `qa/validation.json` - Atlas validation output.

## Install

Copy the `pets/yukino` folder into your local Codex pets directory:

```powershell
Copy-Item -Recurse -Force .\pets\yukino "$env:USERPROFILE\.codex\pets\yukino"
```

Restart Codex after copying the files.

## Validation

The generated `spritesheet.webp` passed the hatch-pet atlas validation with no errors or warnings.

MP4 preview rendering was skipped because the local Windows environment did not have the required video rendering dependency available.
