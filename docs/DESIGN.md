# Spire design

Implement against this file, not folklore.

## Identity

- Product: **Spire**
- Repo: `computerpets-spire`
- Idea: Pet Tower Climb
- Genre: Arcade jumper
- Engine: Phaser.js
- Surface: `8080`

## Loop

Agility is a horizontal course. Spire is up. Frogs shine. Heavy pandas do not, unless Dojo trained jump. Fair because stats are lived, not bought.

## Play beats

- Infinite (capped) tower, daily seed.
- Miss = fall to last checkpoint.
- Height submitted at death or quit.
- Cosmetic flag at your max floor in Hearth.

## Neighbors

- computerpets-agility
- computerpets-dojo
- computerpets-telemetry
- computerpets-quests

## Failure doctrine

Pay-jump items do not exist. Lag spike → rewind 0.5s. Ghost of a banned cheater stripped by Telemetry.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
