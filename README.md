# Universal Combat Framework Demo

A playable Windows build of the demo level of **Universal Combat Framework**, the Unreal Engine plugin that combines Soulslike Enemy Combat and Universal Player Combat. You play the player side against enemies that run the enemy AI and fight with combos from the player's own action graphs. You need no Unreal Engine to play it.

**[Download UniversalCombatFrameworkDemo.zip](https://github.com/Rigbak/UniversalCombatFramework-Demo/releases/latest/download/UniversalCombatFrameworkDemo.zip)** (Windows)

The link always serves the newest build. Every build is listed under [Releases](https://github.com/Rigbak/UniversalCombatFramework-Demo/releases).

## What is in it

- **Freeflow:** eight bare-handed enemies taking turns. Counter a jab or a cross that shows the counter marker, and dodge the red haymaker.
- **Over Shoulder:** six enemies, each drawing a baton, a sword or its fists, playing combos from that weapon's action graph one at a time.
- **The Souls-like arena:** a dual-sword boss that rests between its strings, raises its guard after a run of your blows, rages at half health and breaks under your parries. Bring it low and finish it with the sword execution.
- **The hallway:** doors, chests, a loot chest, a weapon rack and six paired action stations with executions, counters and a vault.
- **The wardrobe hall:** a pad for every weapon and piece of gear, and pads that switch between three inventory styles.

Each place plays its own music. Press H for the debug views menu: each row switches one of the plugin's debug views on or off, and the game pauses while the menu is open.

## How to run it

1. Download the ZIP.
2. Right-click it and choose **Extract All**. A demo started from inside the ZIP cannot find its files.
3. Open the extracted folder and run `UniversalCombatFrameworkDemo.exe`. Its first start can install Microsoft's Visual C++ runtime.

**Windows protected your PC?** The demo is not code-signed, so Windows SmartScreen can stop the first start. Choose **More info**, then **Run anyway**.

## What you need

- Windows 10 or 11, 64-bit
- A graphics card with DirectX 12
- About 1.5 GB of free disk space for the ZIP and the extracted demo
- A keyboard and mouse, or a gamepad

## Keys

| Action | Keyboard and mouse | Gamepad |
|--------|--------------------|---------|
| Move, look | W A S D, mouse | Left stick, right stick |
| Light attack | Left mouse button | Right shoulder |
| Heavy attack | Right mouse button | Right trigger |
| Guard (a sword parries on a press as the hit lands) | Q | Left trigger |
| Lock on, then flick sideways to switch target | Middle mouse button, then the mouse | Top face button, then the right stick |
| Dash, or a vault over an enemy with bare fists | Space | Left shoulder |
| Interact, and the second option | E, F | Bottom face button, left face button |
| Draw or put away a belt slot | 1 to 4 | D-pad |
| Open the inventory | I | Tap View |
| Debug views menu (H again, Escape or B closes it) | H | Hold the menu button, press the D-pad left |
| Sprint (hold) | Left Shift | Left stick click |
| Jump to the start, the paired actions, the style plates | 7, 8, 9 | Hold the right special button, press the D-pad up, right, down |

Under Freeflow the right mouse button guards, and a guard on a punch showing the counter marker counters it.

## Terms

The demo is free to play, for evaluation only. You may not pass the files on, sell them or reuse anything inside them.

The demo's locomotion includes animations and Blueprints adapted from Epic Games' Lyra Starter Game and Game Animation Sample, and its footstep, hit, swing, dodge, gear, guard and interface sounds come from Lyra Starter Game and its landing, jump and body fall sounds from the Game Animation Sample, all used under the Unreal Engine EULA. Its UI uses the Inter and Cinzel typefaces under the SIL Open Font License 1.1.

## Links

- [Universal Combat Framework on Fab](https://www.fab.com/listings/ecc5de6d-b0d1-49ea-8a79-17dd634de60f)
- [Documentation](https://rigbak.com/docs/ucf)
- [Every demo](https://rigbak.com/demos)
- [Discord support](https://rigbak.com/discord)
