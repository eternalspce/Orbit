# Orbit

Orbit is a local-first productivity workspace and Chrome New Tab extension.

## Production build

```bash
npm ci
npm run check
```

The deployable extension is written to `dist/`. Load that folder in Chrome via
`chrome://extensions` → Developer mode → Load unpacked.

## Privacy and data

Orbit stores settings, tasks, routines, and activity data locally in the browser
(Chrome extension storage, with a localStorage fallback). It has no account,
backend, telemetry, or cloud synchronization. Optional weather, media, fonts,
and user-configured links contact their respective third-party services.

## Support scope

Orbit is designed for one browser profile at a time. Data is not shared between
people or automatically synchronized across devices; export/backup should be
provided before relying on it for important records.
