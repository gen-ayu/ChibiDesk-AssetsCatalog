
# ChibiDesk Assets Catalog

A community asset catalog for ChibiDesk.

## Asset types

- `wallpaper`: Static and live desktop backgrounds.
- `asset`: GIFs, APNGs, short videos, animated stickers and desktop overlays.

## Repository structure

- `catalog/index.json`: Public catalog of approved assets.
- `catalog/categories.json`: Asset types and initial tag vocabulary.
- `schema/asset.schema.json`: Asset record validation rules.

## Submission workflow

1. A community member submits a download link through Discord.
2. The bot validates the submission and checks for duplicates.
3. A moderator reviews the link, content, tags and redistribution permissions.
4. Approved entries are published to the catalog.
5. The Discord bot displays previews, metadata and download links.

## Security

- Never commit bot tokens, API keys or private credentials.
- Pending submissions and moderation records remain outside the public catalog.
- Only approved assets are published.
- All assets must have a legitimate source and appropriate redistribution permissions.

