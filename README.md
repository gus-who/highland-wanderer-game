# Highland Wanderer

*A blade against the mist.*

A single-file, browser-based 2D side-scrolling brawler set in a mythic, cinematic Scottish
Highlands — layered rain, glitching lochs, rolling folklore hills, Highland cows and sheep — drawn
in the flat-shape, rounded-silhouette style of **Samurai Jack**. Play a lone cloaked katana
wanderer clearing waves of folklore-corrupted beasts across three stages, ending in a duel with the
Great Horned Beast.

## How to play

No install, no build step, no dependencies. Just open the game:

```
open index.html      # or double-click it in your file browser
```

> Tip: run it from a real browser window (not a background tab) — browsers throttle the animation
> loop when the tab isn't focused.

## Controls

| Action | Keys |
| --- | --- |
| Move (with full air control) | `←` `→` / `A` `D` |
| Jump (variable height) | `Space` / `↑` / `W` |
| Slash — 3-hit combo | `J` |
| Heavy strike | hold `J` |
| Air slash | `J` while airborne |
| Roll (ground) / Air-dash | `K` |
| Parry → Riposte | `L`, then `J` on a successful parry |
| Focus special (screen-clearing) | `I` (when the Focus meter is full) |
| Pause | `Esc` |
| Mute | `M` |

**Read the signs:** every beast flashes a red ⚠ glyph and winds up before it strikes. **Jump** the
low charges, **roll** through lunges, **parry** for a riposte.

## Stages

1. **The Loch Shore** — rolling shoreline hills over a shimmering loch; shadow stags.
2. **The High Moor** — a long climb to a windswept summit; stags and mist wraiths.
3. **The Black Glen** — standing stones under a huge moon; a gauntlet, then the **Great Horned Beast**.

## Under the hood

- **Pure vanilla:** one `index.html`, HTML + CSS + Canvas 2D + JavaScript. No frameworks, no assets.
- **Procedural art:** every character, hill, tree, and weather effect is drawn in code.
- **Terrain-driven camera:** the camera is a continuous function of the ground beneath the hero —
  higher elevation widens the shot, slopes tilt the land up into the frame, so the world scales up
  and down as you move through the hills.
- **Synthesized audio:** all SFX and the wind/rain ambience are generated with the Web Audio API.

## Credits

Built with [Claude Code](https://claude.com/claude-code).
