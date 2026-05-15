# Codex Pets

Custom Codex pets created by RaphaelXie.

## Pets

| Pet | Description | Files |
| --- | --- | --- |
| [Cat Quartet](pets/cat-quartet/) | Four chibi cats together: tuxedo, ragdoll, Abyssinian, and Siamese. | `pet.json`, `spritesheet.webp` |

## Repository Layout

Each pet lives in its own folder:

```text
pets/
  pet-id/
    pet.json
    spritesheet.webp
    contact-sheet.png
    README.md
```

`pet.json` and `spritesheet.webp` are the files needed by Codex. The contact sheet is included as a preview.

## Install A Pet

Copy a pet folder into your Codex pets directory:

```bash
mkdir -p ~/.codex/pets
cp -R pets/cat-quartet ~/.codex/pets/
```

Then restart or refresh Codex and choose the custom pet.
