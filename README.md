# Shatterline

A browser rhythm game. Strike voxel cubes on the beat, dodge the red walls, and build the music as your Flow rises. Every hit plays a note in the current chord.

All the audio is made live in the browser with the Web Audio API, so there are no asset files. The whole game is in `index.html`.

## Play locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy to Vercel

1. Push this folder to a GitHub repo.
2. In Vercel: **Add New → Project**, then import the repo.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Deploy.

You can also run `npx vercel` from this folder to deploy without GitHub.

## Controls

- Six cells (3 × 2). The default keys are Q W E / A S D. You can rebind them on the title screen, and there are presets for Numpad and a two-hand split.
- `Esc` pauses. `[` and `]` adjust the audio offset. `1` `2` `3` pick a track.
- On touch screens, tap the cells.
