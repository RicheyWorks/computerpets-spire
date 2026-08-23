# Spire

**Pet Tower Climb** — Vertical climb that tests jump and endurance — daily height as a worldwide ghost race.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Agility is a horizontal course. Spire is up. Frogs shine. Heavy pandas do not, unless Dojo trained jump. Fair because stats are lived, not bought.

## Genre & engine

- Genre: **Arcade jumper**
- Engine: **Phaser.js**
- Stack: TypeScript · Phaser 3 · vertical platforms · jump + endurance stats
- Default surface: `8080`

## How you play

1. Infinite (capped) tower, daily seed.
2. Miss = fall to last checkpoint.
3. Height submitted at death or quit.
4. Cosmetic flag at your max floor in Hearth.

## Talks to

- computerpets-agility
- computerpets-dojo
- computerpets-telemetry
- computerpets-quests

## Failure doctrine

Pay-jump items do not exist. Lag spike → rewind 0.5s. Ghost of a banned cheater stripped by Telemetry.

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Spire must leave Rui walking.

## Layout

```
computerpets-spire/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
cd app; npm install; npm run dev
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
