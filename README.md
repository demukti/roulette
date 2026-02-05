# Marble roulette

This is a lucky draw by dropping marbles.

[Demo]( https://lazygyu.github.io/roulette )

# Requirements

- Typescript
- Parcel
- box2d-wasm

# Development

```shell
> yarn
> yarn dev
```

# Build

```shell
> yarn build
```

# Customizations in This Fork

This fork includes UI and behavior changes for repeated personal use. Summary:

- Keyboard shortcuts: `Space`=Start, `S`=Shuffle, `F` (hold)=Fast‑forward (no overlay icon), `M`=Toggle menu, `L`=Toggle slow‑motion.
- Menu behavior: the settings menu no longer auto‑shows after a winner is shown. It stays hidden until toggled with `M`.
- Slow‑motion controls: a “Slow motion” toggle plus a minimum speed slider (0.20x–1.00x). Lower values slow more near the goal.
- Defaults: slow‑motion off, skills off.
- Persistence: slow‑motion toggle/slider and skills toggle are saved in `localStorage` under `mbr_settings` and restored on load.
- Winner display: winner text is ~30% smaller to handle long names better.
