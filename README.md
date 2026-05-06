# Find Mod Translations Database

Database for [Find Mod Translations](https://github.com/notcheesex/FindModTranslations).

Current database:

```text
Russian/translations.json
```

## Format

```json
{
  "version": 1,
  "updatedAt": "2026-05-06",
  "language": "Russian",
  "aliases": ["Russian (GitHub)"],
  "mods": []
}
```

`aliases` is optional.

## Entry

```json
{
  "name": "Example Mod",
  "packageId": "author.examplemod",
  "steamId": "1234567890",
  "url": "https://steamcommunity.com/sharedfiles/filedetails/?id=1234567890",
  "authors": "Mod Author",
  "gameVersions": ["1.6"],
  "translation": {
    "name": "Example Mod Translation",
    "packageId": "translator.examplemod.translation",
    "steamId": "0987654321",
    "authors": "Translator",
    "gameVersions": ["1.6"],
    "url": "https://steamcommunity.com/sharedfiles/filedetails/?id=0987654321"
  },
  "alternatives": []
}
```
