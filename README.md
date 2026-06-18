# smart-road

A traffic intersection simulator built with Rust and SDL2. Vehicles enter from all four directions and navigate a smart intersection without collisions.

## Controls

| Key | Action |
|-----|--------|
| `↑` | Spawn vehicle from the North |
| `↓` | Spawn vehicle from the South |
| `→` | Spawn vehicle from the East |
| `←` | Spawn vehicle from the West |
| `R` | Spawn vehicle from a random direction |
| `Esc` | Show statistics / Exit |

## Requirements

- Rust (2021 edition)
- SDL2, SDL2_image, SDL2_ttf

## Run

```bash
cargo run
```
