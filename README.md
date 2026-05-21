# Codex Pets

Custom Codex pets created by RaphaelXie.

## Pets

| Pet | Description | Files |
| --- | --- | --- |
| [Cat Quartet](pets/cat-quartet/) | Four chibi cats together: tuxedo, ragdoll, Abyssinian, and Siamese. | `pet.json`, `spritesheet.webp` |
| [Maodie_V1](pets/maodie-v1/) | A round-headed orange tabby with a warning/shouting failed state and a tiny white paper-roll prop. | `pet.json`, `spritesheet.webp` |
| [Aby](pets/aby/) | A show-grade Abyssinian cat with a long athletic body, ruddy ticked coat, large ears, and green eyes. | `pet.json`, `spritesheet.webp` |
| [uwhusky](pets/uwhusky/) | Dubs-inspired UW Alaskan Malamute with gray-white markings and a purple-gold bandana. | `pet.json`, `spritesheet.webp` |

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

Clone the repository, then copy the pet folder you want into your Codex pets directory.

macOS or Linux:

```bash
git clone https://github.com/raphaelxie/codex_pet.git
cd codex_pet

mkdir -p "$HOME/.codex/pets"
cp -R pets/uwhusky "$HOME/.codex/pets/"
```

To install every pet at once:

```bash
cp -R pets/cat-quartet pets/maodie-v1 pets/aby pets/uwhusky "$HOME/.codex/pets/"
```

Windows PowerShell:

```powershell
git clone https://github.com/raphaelxie/codex_pet.git
cd codex_pet

New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets"
Copy-Item -Recurse .\pets\uwhusky "$env:USERPROFILE\.codex\pets\"
```

Then restart or refresh Codex and choose the custom pet.
