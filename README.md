# Link Pet Open-Source Package

This folder is a ready-to-use Codex pet package.

## Direct-use files

- `pet.json`: pet manifest
- `spritesheet.webp`: final Codex pet spritesheet

If you want to use this pet directly in Codex, place this whole folder under your pets directory, for example:

```text
~/.codex/pets/link/
```

The root of this folder already matches that layout.

## Extra files

- `preview/contact-sheet.png`: human-readable animation preview
- `meta/validation.json`: atlas validation result
- `meta/review.json`: frame extraction and QA result
- `extras/spritesheet.png`: PNG version of the final atlas for inspection or editing

## Notes

- The core package passed atlas and frame QA.
- Preview video files are not included because video rendering was blocked by temp-directory permissions in this environment.
- Current display name: `林克`
- Current pet id: `link`
