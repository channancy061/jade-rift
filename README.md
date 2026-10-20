# Jade Rift

A crossover Pokémon ROM hack for **Emerald**. **Kanto and Hoenn are collapsing into each other**, and
Kanto's Gym Leaders, Elite Four and Champion challenge you on your way through Hoenn.

Sister hack: [Ember Rift](https://github.com/channancy061/emerald-rift) (the same story the other way round).

## What's different

- **Visiting challengers.** Each guards the matching gym or a story place. Each fights with a field effect of their
  type (rain, sun, terrain, hazards…) and gives you a TM after the first win.
- **Every boss redesigned.** Teams follow their type and grow through the game: 3 Pokémon at the first gyms, 6 at the
  last ones. Early bosses only use Pokémon that are fair at their level.
- **Wild Pokémon planned for the story.** Every route offers real answers to the next big battles. Route trainers use
  those Pokémon too, with fair moves (no Sand Attack spam).
- **Side stories.** Some challengers tell you where a legendary Pokémon has appeared.
- **A final chapter.** After the Champion, Steven, Birth Island and Deoxys. The credits only roll once it's caught.
- **New-game choices:**
  - **Difficulty:**
    - **Easy:** only important battles stop you.
    - **Normal:** as the original game.
    - **Hard:** trainers spot you from far away and in every direction, and Gym Leaders wait until their whole gym
      is beaten.
    - **Extra Hard:** as Hard, and every trainer has six Pokémon.
  - **Nuzlocke rules** (each one optional).
  - **Level caps.**
  - And more.

## What you need

No game is included. Patch **your own** copy of the original game:

| Patch | Needs | CRC32 |
|---|---|---|
| `patches/Jade-Rift.bps` | Pokémon Emerald Version (USA) | `1F1C08FB` |

Other versions won't work: European or Japanese games, other revisions, or other hacks. The patcher tells you if your copy
is the wrong one.

## How to patch

1. Open [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) in your browser, or use Floating IPS (Flips).
2. ROM file: your original game. Patch file: `Jade-Rift.bps`.
3. Apply the patch and save the new `.gba` file.
4. Play it in mGBA (recommended) or another GBA emulator, and start a **new game**.

At the start the game asks a few questions (difficulty, Nuzlocke rules…). Read each one and don't keep pressing A: Yes
is picked first, and B answers No. Your answers can't be changed later in that save.

## Player's Guides

- `guides/Jade-Rift-Players-Guide.html` opens in any browser. `guides/Jade-Rift-Players-Guide.md` has the same text.
- They list every important battle with its team, the level caps, and where to catch Pokémon (in playthrough
  order, with good catches for each battle). They also cover the shops, special evolutions and the final chapter.
- They show spoilers, so read only what you want.

## Status

These are **test builds**. Please report bugs and balance problems.

## Credits

- Built with [Poke Studio Customizer](https://github.com/channancy061/poke-studio-customizer).
- Based on pokeemerald-expansion by the Rom Hacking Hideout (RHH) team and on pokefirered-expansion (a community
  port), both built on pret's decompilations.
- Pokémon is © Nintendo / Creatures Inc. / GAME FREAK inc. This is a free fan project and is not affiliated with
  them. Don't sell it, and don't share patched ROMs.
