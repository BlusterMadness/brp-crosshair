# Bluster Crosshair

A lightweight, standalone aiming crosshair for FiveM servers, originally made for BlackLight RP by Bluster_Madness.

## Features
- Simple centered crosshair.
- Shows while free-aiming with a weapon; hides when no longer aiming or unarmed.
- Works independently of QBCore, ESX, Qbox, and other frameworks.
- No database or additional FiveM resources required.
- Editable image (`ui/crosshair.png`) and sizing (`ui/style.css`).

## Installation
1. Extract the ZIP. You should have **one** folder named `bluster-crosshair`, containing `fxmanifest.lua`, `client`, `ui`, and these documentation files.
2. Place `bluster-crosshair` inside your FiveM server's `resources` folder (directly or under a resource group such as `[standalone]`).
3. Add this to `server.cfg`:
   ```cfg
   ensure bluster-crosshair
   ```
   If you already have `ensure [standalone]` and placed the resource inside that group, you do not need an additional ensure line.
4. Restart the server, or start the resource using `ensure bluster-crosshair` in the server console.

## Customize
- To change the crosshair graphic, replace `ui/crosshair.png`.
- To change its size, edit the `.crosshair` width and height in `ui/style.css`.
- Source files are provided unencrypted so you can modify them.

## License
The included project license is MIT. Read `LICENSE` for its terms. **Before public redistribution, confirm that any code retained from the original mrm project is redistributable under compatible terms and preserve all original license/copyright notices as required.**

## Credits
- Bluster_Madness — this rewrite and distribution.
- mrm — original crosshair project credited in the previous README.
- @NCDev — inspiration credited in the previous README.
