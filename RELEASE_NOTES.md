# Samurai Western Recomp — v0.1.0

**Experimental Steam Deck / Linux x86_64 build**

## Verified locally
- Native recompilation built successfully
- Runs on SteamOS without the previous GLIBC 2.44 requirement
- Gameplay reached with character controls functioning
- Virtual PS2 memory card saving and loading confirmed
- AppImage launched successfully in local testing

## Known limitations
- Full-game playthrough has not been verified
- Occasional audio underruns were reported
- The initial AppImage may depend on local game ELF/ISO paths; portability to other devices is not yet verified
- Some runtime EE/VU recompilation and IOP compatibility warnings were observed

## Required user content
Original compatible Samurai Western (Europe) game assets must be legally supplied by the user. The AppImage and repository must not include the commercial ISO, original game ELF, or game assets.

## Acknowledgments
Built using exoteric33's ps2-native-recomp framework. Licenses and distribution rights for all code and bundled dependencies should be reviewed before public binary distribution.
