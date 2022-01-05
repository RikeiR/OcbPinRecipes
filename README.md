# OCB Pin Recipes Mod - 7 Days to Die (A20) Addon

A small harmony mod enabling to pin recipes on the UI.

Needs to be installed client and server side. And both need
EAC (Easy Anti-Cheat) to be turned off! There is no server-side
only version of this mod as it contains custom code. The mod
must also be installed on dedicated servers if you want to
use it in that setup, to persist pinned recipes for users.

![In-Game Pinned Recipes](Screens/in-game-screen-pins.jpg)

![In-Game Details Pinned](Screens/in-game-left-pins.png)

## Changelog

### Version 0.3.0

- Amount of items is now also pinned
- Added craft & clear recipe button
- Refactored data persisting to work on server
- Old pinned recipes will be lost on upgrade

### Version 0.2.0

- Persist pinned recipes over sessions
- Hide pinned recipes when game pauses
- Fixed improper recipe name displayed
- Improved UI look and feel a little
- Also allow to pin locked recipes
- Add tooltip for each ingredient
- Add static global manager class
- Recreated ULM pin icon from scratch

### Version 0.1.0

- Initial version

## Compatibility

I've developed and tested this Mod against version a20.b218.

[1]: https://github.com/OCB7D2D/A20BepInExPreloader