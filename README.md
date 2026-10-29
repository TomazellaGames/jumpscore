# jumpscore

A minimalist rhythm game where you are a single line of light, jumping from shape to shape through a dark galaxy of sound. Every shape you hit plays a note, and the song is yours to build.

Made for [That Game Jam #2](https://itch.io/jam/thatgamejam02), based on the jam's theme song: [listen on YouTube](https://www.youtube.com/watch?v=z71a6UtZ6GY).

## Inspiration

> When I closed my eyes and listened to the song, I saw a dark space and lines, then sound, then shapes, and movement. I visualized the game before that 1 minute song ended. I felt at peace as if I was flying through space, jumping from star to star in a galaxy of sound.

## How to play

Shapes drift toward you along a faint musical staff: higher shapes are higher notes. Jump into them to play the melody, and try to hit each one right on the beat.

| Input | Action |
| --- | --- |
| **Space** / **Enter** / **Z**, click or tap | Jump. In the air: jump again, or dive if a shape is below you |
| **Hold** | Jump higher |
| **↑** / **W** | Always jump |
| **↓** / **S** | Always dive |

The first time you play, a short tutorial pauses mid-jump to teach the air jump and the dive. You can replay it from the end screen (button or **T**).

### Shapes

- **Polygons** (triangles, squares, pentagons, hexagons, octagons): single notes. Bounce off them to chain into the next one.
- **Stacked pairs**: chords. Two notes at once, worth more points.
- **Circles**: held notes. You ride them for a beat while the note sustains. Press to jump off early.
- **Small diamonds**: grace notes, quick low hops between phrases.

### Scoring

- Each hit scores more the higher the note and the longer your chain.
- **Perfect** hits (right on the beat) score double and bounce you higher.
- **Slams** (diving into a shape) score extra and launch you even higher.
- Hitting the ground resets your chain.

### The band

The music grows with you. Hitting shapes brings in layers of the band: bass groove, kick and hats, snare, then an arpeggio. Landing on the ground or missing shapes strips them away again. The four dots under your score show how many layers are playing.

Every run uses a new key, chord progression and melody, generated as you start.

## Running it

The whole game is a single file, [index.html](index.html), with no dependencies. Open it in a modern browser and press to begin. All audio is synthesized live with the Web Audio API.

Your best score is saved locally in the browser.

## Credits

Created by Tomazella Games with [Claude Code](https://claude.com/claude-code).

## License

[MIT](LICENSE)
