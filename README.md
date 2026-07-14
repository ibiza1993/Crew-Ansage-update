# Crew Ansagen — Update Feed

Private update manifests and release assets for Crew Ansagen.

## Layout

```
updates/latest.json
README.md
```

## Publish a release

1. Build/zip the app.
2. Create a GitHub Release and upload the zip.
3. Put the download URL + SHA256 into `updates/latest.json`.
4. Push to `main`.

Example `updates/latest.json` fields: `version`, `mandatory`/`breaking`, `changelog`, `download_url`, `sha256`.
