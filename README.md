# Darkest Dungeon Companion Compositions

Compact team-composition notes extracted from ShuffleFM Darkest Dungeon guide videos.

Each `*-compositions.md` file contains only party-composition data: team names, hero order from rank 4 to rank 1, relevant combat skills, and short strategy notes. These are intended as quick gameplay references, not full video summaries.

## Source Videos

| File | Source |
| --- | --- |
| `grave-robber-compositions.md` | [Grave Robber and You: Darkest Dungeon Guide](https://youtu.be/-YPReTv9HUc) |
| `highwayman-compositions.md` | [Highwayman and You: Darkest Dungeon Guides Done Quick](https://youtu.be/eLlWIBdPlNw) |
| `shieldbreaker-compositions.md` | [Shieldbreaker and You: Darkest Dungeon Guide](https://youtu.be/EnKGh_wL06A) |
| `flagellant-compositions.md` | [Flagellant and You: Darkest Dungeon Guide](https://youtu.be/1glhtfGUr9Y) |
| `jester-compositions.md` | [Jester and You: Darkest Dungeon Guide](https://youtu.be/3ulLuT6eNi0) |
| `arbalest-musketeer-compositions.md` | [Arbalest, Musketeer, and You: Darkest Dungeon Guide](https://youtu.be/4UbSNrHvxAI) |
| `man-at-arms-compositions.md` | [Man-at-Arms and You: Darkest Dungeon Guide](https://youtu.be/h45UBLR3tDE) |
| `bounty-hunter-compositions.md` | [Bounty Hunter and You: Darkest Dungeon Guide](https://youtu.be/t6rz51-BbLo) |
| `antiquarian-compositions.md` | [Antiquarian and You: Darkest Dungeon Guide](https://youtu.be/8WAMK9p90Mc) |
| `leper-compositions.md` | [Leper and You: Darkest Dungeon Guide](https://youtu.be/K6NwDoftPtY) |
| `plague-doctor-compositions.md` | [Plague Doctor and You: Darkest Dungeon Guide](https://youtu.be/JrMG5POi2bU) |
| `occultist-compositions.md` | [Occultist and You: Darkest Dungeon Guide](https://youtu.be/SjqsgfreGhY) |
| `abomination-compositions.md` | [Abomination and You - Darkest Dungeon Guide](https://youtu.be/2JjV4PiPiS4) |
| `houndmaster-compositions.md` | [Houndmaster and You - Darkest Dungeon Guide](https://www.youtube.com/watch?v=cGLRPWj4EhQ) |

## Format

Each composition follows this structure:

```markdown
**Team: <Title>**
Heroes:
- R4 <Hero>: `<Skill>`, `<Skill>`, `<Skill>`, `<Skill>`
- R3 <Hero>: `<Skill>`, `<Skill>`, `<Skill>`, `<Skill>`
- R2 <Hero>: `<Skill>`, `<Skill>`, `<Skill>`, `<Skill>`
- R1 <Hero>: `<Skill>`, `<Skill>`, `<Skill>`, `<Skill>`

Strategy:
- <Core opening or combo.>
- <How the team kills, controls, or sustains.>
- <Important caveat or replacement when relevant.>
```

Ranks are listed from back to front: `R4` is the back rank, `R1` is the front rank.

## Method

The data was extracted from video chapters, descriptions, subtitles, and visible team screens. Hero and combat-skill names were cross-checked against local Darkest Dungeon wiki data, then skill lists were ordered by each hero's wiki combat-skill order rather than by mention order in the video.

The source wiki data used during extraction was local scraper output from:

```text
/Users/arthur/Developer/darkest-dungeon-wiki-scraper/darkestdungeon_wiki
```

## Caveats

- This repo summarizes gameplay guidance from the videos; it is not an official Red Hook Studios resource.
- The files intentionally omit full trinket lists, general hero overviews, and non-composition commentary.
- Some videos present flexible shells rather than exact four-hero named teams. Those files preserve the flexible nature instead of inventing a rigid party.
- The Leper video's English auto-subtitles were repeatedly rate-limited by YouTube with `HTTP 429`. `leper-compositions.md` was redone using the downloaded team-section video and visual confirmation of the team screens.

## Validation

The Markdown files were checked for:

- A `**Team: ...**` heading for each composition.
- A `Heroes:` section.
- Four hero lines ordered `R4`, `R3`, `R2`, `R1`.
- Inline backticked skills on each hero line.
- A `Strategy:` section for each team.
