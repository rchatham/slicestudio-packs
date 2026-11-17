# Slice Studio sound packs

The sound packs that [Slice Studio](https://slicestud.io) downloads on demand: drum kits and sampled instruments.

The packs are the files attached to this repo's [releases](https://github.com/rchatham/slicestudio-packs/releases). The repo itself holds no audio, only this page and the licences.

## How the app uses this

- The app reads `catalog.json` from the newest release. It lists each pack with its size, its address and its SHA-256.
- A pack is a zip: `pack.json`, `CREDITS.txt` and a `samples/` folder of 16-bit 44.1 kHz WAV files.
- The app checks a download against the catalog's SHA-256 and refuses it if they differ.

## The packs

| Pack | What it is | Built from | Licence |
|------|------------|------------|---------|
| Machine Kit | Drum machine sounds made on analog-style synths | [Synthesizer Percussion](https://freepats.zenvoid.org/Percussion/electric-percussion.html), FreePats project | CC0 1.0 |
| Garage Kit | A real kit in a room | [Gogodze Phu Vol II](https://github.com/sfzinstruments/karoryfer.gogodze-phu-vol-ii), Karoryfer Samples | CC0 1.0 |
| Upright Piano | A real upright, recorded every three keys | [Upright Piano KW](https://freepats.zenvoid.org/Piano/acoustic-grand-piano.html), FreePats project | CC0 1.0 |
| Finger Bass | An electric bass played with the fingers | [Bass Guitar YR (finger)](https://freepats.zenvoid.org/ElectricGuitar/clean-electric-bass.html), FreePats project | CC0 1.0 |
| Orchestra | Strings bowed and plucked, harp, French horn, flute, glockenspiel | [VSCO 2: Community Edition](https://versilian-studios.com/vsco-community/), Versilian Studios (Sam Gossner) | CC0 1.0 |

## Licence

Every sound here comes from a library its makers released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), and the packs are offered the same way. The sounds were trimmed, levelled and converted for the app; nothing else was changed.

Each library's own licence file, as it was when downloaded, is in [`licenses/`](licenses). Each pack's `CREDITS.txt` names its source.

Thanks to the people who made these libraries and gave them away.
