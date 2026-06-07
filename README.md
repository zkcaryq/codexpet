# codexpet

Codex custom pet package for `中野二乃` / Nakano Nino.

## Files

- `pet.json` - Codex pet configuration.
- `spritesheet.webp` - 1536x1872 animated pet atlas.
- `qa/contact-sheet.png` - visual contact sheet for all rows.
- `qa/previews/*.gif` - per-state animation previews.
- `qa/validation.json` - deterministic atlas validation result.

## Install

Copy `pet.json` and `spritesheet.webp` into a Codex pets folder:

```text
D:\AI\codex\pets\nino\
```

The installed folder should contain:

```text
pet.json
spritesheet.webp
```

## Validation

The generated atlas passed validation:

- Format: WebP RGBA
- Size: 1536x1872
- Cell size: 192x208
- Errors: none
- Warnings: none
