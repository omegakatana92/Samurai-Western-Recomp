# Samurai Western Recomp

An experimental native PlayStation 2 recompilation of **Samurai Western (European release, SLES_532.34)** for Linux and Steam Deck.

Built using [ps2-native-recomp](https://github.com/exoteric33/ps2-native-recomp) by exoteric33.

## Current status

**Initial playable test build.** Tested on Steam Deck: the game reached gameplay with working character controls, and PS2 memory-card saving/loading worked in local testing. This does not mean the entire game is verified. Some audio underruns and runtime code generation pauses were observed.

## Requirements

- Linux x86_64 / Steam Deck
- A legally obtained compatible copy of Samurai Western (Europe), including its original ISO and executable
- The original game files in the expected local paths for the current AppImage launcher

The initial AppImage may rely on paths from the build machine; it is **not yet confirmed portable** across other Steam Deck installations.

## Game files and copyright

This project is an independent technical experiment. **No copyrighted game ISO, executable, artwork, audio, or other commercial game assets are provided here.** Users must supply their own legally obtained copy. Do not upload extracted game assets or personal saves to this repository.

## Development notes

Local validation: native Linux executable compiles and starts on SteamOS; interactive gameplay and virtual memory-card save/load tested. Full-game compatibility, controller remapping, cutscenes, and performance need further testing.

## Credits

- Native recompilation framework: [exoteric33/ps2-native-recomp](https://github.com/exoteric33/ps2-native-recomp)
- This game-specific experiment: [omegakatana92](https://github.com/omegakatana92)

## Licensing

No new license is declared for this repository yet. Upstream source code, generated outputs, and third-party dependencies may carry separate licensing terms. Those terms must be reviewed before publishing source code or changing its license. No license is granted for commercial game assets.
