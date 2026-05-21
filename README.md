# Codex Pets

Custom Codex pets created by RaphaelXie.

## Pets

| Pet | Description | Files |
| --- | --- | --- |
| [Cat Quartet](pets/cat-quartet/) | Four chibi cats together: tuxedo, ragdoll, Abyssinian, and Siamese. | `pet.json`, `spritesheet.webp` |
| [Maodie_V1](pets/maodie-v1/) | A round-headed orange tabby with a warning/shouting failed state and a tiny white paper-roll prop. | `pet.json`, `spritesheet.webp` |
| [Aby](pets/aby/)  | A Codex custom pet based on a show-grade Abyssinian cat. | `pet.json`, `spritesheet.webp` |

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
git clone https://github.com/raphaelxie/codex_pet.git
cd codex_pet

mkdir -p "$HOME/.codex/pets"
cp -R pets/aby "$HOME/.codex/pets/"
```

To install every pet at once:

```bash
cp -R pets/cat-quartet pets/maodie-v1 pets/aby "$HOME/.codex/pets/"
```



Then restart or refresh Codex and choose the custom pet.
