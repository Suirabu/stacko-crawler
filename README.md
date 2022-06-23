# Stacko Crawler

A simple text-based adventure game written in the [Stacko](https://github.com/Mercifle/Stacko) programming language!

**IMPORTANT NOTE:** This game *will not* work on the current version of Stacko. It is instead expected to work with upcoming versions of the language.

## How to play

```
$ ./Stacko Source/Game.stko
```

### Objective

Explore an infinite dungeon, defating enemies and collecting items along the way.

### Commands

- `l`   List available actions
- `m`   Move to a new room
- `h`   Heal (costs 1 gold)
- `s`   Display stats
- `q`   Quit the game

### Stats

- `health`

You health. May decrease if attacked by an enemy. If your health reaches zero the game ends.

- `attack`

Your attacking power. This value represents how much health enemies will lose each time you attack them.

- `gold`

How much gold you have. Gold can be used to heal yourself.

## License

This game is licensed under the MIT license.
