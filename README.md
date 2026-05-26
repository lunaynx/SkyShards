# SkyShards

[🌐 Live App](https://skyshards.com/)

SkyShards is a website for the Hypixel Skyblock attribute fusion system.

## Features
- Calculate the fastest/cheapest way to fuse attributes
- Automatic adjustment of fusion tree based on custom rates and current bazaar prices
- Clean and responsive design

## Getting Started
To run locally:
```sh
pnpm install
pnpm run dev
```

## Updating Fusion Data
The dev server serves static JSON from `public/`; `dist/` is ignored build output. After exporting data from `SkyShards-Parser`, sync it with:
```sh
pnpm run data:sync
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.
