# Memento

## Recipient experience prototype

This branch contains a throwaway responsive UI prototype for Memento's Recipient experience. It presents three structurally different mobile-and-desktop variants on one route.

```sh
npm install
npm run prototype
```

Open the local URL with one of these query parameters:

- `?variant=A`: selected Photos library, with compact New for you summaries, dense justified photo rows, and a desktop date scrubber
- `?variant=B`: rejected publication-feed exploration, retained as design evidence
- `?variant=C`: Event-page direction, retained separately from the Photos-page decision

Use the floating switcher or the left and right arrow keys to compare variants. Each variant includes responsive navigation, Events, People and Interest-list editing, Favorites, Comments, downloads, notification settings, and replayable onboarding. Click a photo to inspect the responsive media viewer. Open the avatar menu to reach Settings and onboarding.

All data and interactions are in memory. The prototype defaults to dark mode and uses Memento's selected Tailwind sky accent.
