# The Friendly Ghost

This is a user-friendly cheat for [Phasmophobia](https://store.steampowered.com/app/739630/Phasmophobia/).

It is my pet project. I'm doing this for fun and learning x86 assembly and Lua in the process. I play Phasmo pretty regularly, so updates are guaranteed, at least in the near future :)

## Features
- Teleport
- Invincibility
- Infinite stamina

## Target game version
[Cursed Possessions | Update v0.5.1.1](https://store.steampowered.com/news/app/739630/view/3099039480050972560)

## How to use
1. Launch the game
2. Launch The Friendly Ghost
3. Have fun ;)
4. When done close The Friendly Ghost before you exit the game

### Hotkeys
- Ctrl+F1: Remember current position to Slot 1
- F1: Restore position from Slot 1
- Ctrl+F2: Remember current position to Slot 2
- F2: Restore position from Slot 2
- Ctrl+F3: Remember current position to Slot 3
- F3: Restore position from Slot 3
- Ctrl+Space: Jump
- Ctrl+Left: Step to the left
- Ctrl+Right: Step to the right
- Ctrl+Up: Step forward
- Ctrl+Down: Step backward
- F4: Toggle invincibility
- F5: Toggle infinite stamina

## Notes
- Teleport position values for each slot can be entered manually in the cheat window.
- Length of a step and height of a jump can be changed in the UI. I don't know what those units are; all I know is that they are not linear.
- Step in any direction does not take camera rotation into account.
- The Friendly Ghost used to be able to attach to the game process when it was launched before the game, but since I started using [Mono Data Collector](https://wiki.cheatengine.org/index.php?title=Mono), it is not possible anymore.
- The game will not close normally while the cheat is running (once again, blame [Mono Data Collector](https://wiki.cheatengine.org/index.php?title=Mono)). So it is a good idea to always close the cheat first.
- Why the binary has such a large size? Well... Mono. Data. Collector.

## License
This project is licensed under the terms of the [BSD 3 license](https://opensource.org/licenses/BSD-3-Clause).

Project icon: [Flaticon.com](https://flaticon.com)
