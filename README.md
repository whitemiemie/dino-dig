# Dino Dig · A Day of Small Bones

An interactive exhibit on operant conditioning, built for PSY 111. One page holds two views:

- **Dino Dig** (`game.html`): a 90-second pixel-art dig (goal: 24 bones). Four dig spots run four reinforcement schedules (fixed ratio 5, variable ratio 5, fixed interval 5 s, variable interval 4 s). A big dinosaur keeps coming for ours: firing the flare post sends it away (negative reinforcement), and ignoring the footsteps gets ours grabbed and dropped (positive punishment). At dusk one slab quietly stops paying (extinction). Field guide mode explains each spot on a card.
- **A Day of Small Bones** (`day-map.html`): a map tour of one ordinary day in 12 stops, from a phone notification at 07:05 to one more video at 23:30, covering the four consequences, the four schedules, extinction, shaping, discriminative stimuli and real-world uses.

## Run it

Open `index.html` in Chrome. The switch in the top bar (Dino Dig · Field guide · Your day) moves between the game and the map; a round in progress pauses while the map is showing. Everything works offline except the web fonts, which fall back to system fonts.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Entry page that keeps the game and the map loaded and switches between them |
| `game.html` | Dino Dig field camp game |
| `day-map.html` | A Day of Small Bones map tour |
| `day.html` | Earlier scrolling version of the day, kept as a backup |
| `bg.jpg`, `slab_*.png`, `pit_*.png`, `flare.png` | Dig site art |
| `town.jpg`, `town_night.jpg`, `dig_island.png` | Town map art (day and night) and the dig island |
| `dino_sage_hat.png`, `raider.png` | Our dinosaur and the big dinosaur |

## Credits

- Concepts follow the PSY 111 lecture *Learning (Part 1)* and Kosslyn & Rosenberg, *Introducing Psychology*.
- The dinosaur silhouette is based on the Chrome offline dinosaur from the Chromium project, recoloured and redrawn for this exhibit.
- Fonts: Pixelify Sans and Atkinson Hyperlegible (Google Fonts); digits use Tiny5 (SIL Open Font License), inlined.
