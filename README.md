

# ThirdPerson Revamped

## Commands

- `!tp`
- `!thirdperson`
- `css_thirdperson`

Use any of these commands in chat or console to toggle third-person view.

A simple third-person camera plugin for Counter-Strike 2.

- Smooth camera transitions
- Admin-only option
- Custom messages and config
- Option to ignore walls for the camera (IgnoreWallForCamera)


> ⚠️ **Known Issue:**
> Bullets are fired from the third-person camera position, not the player's actual position.
> This cannot be fixed currently due to game limitations.

## Installation


1. Download and extract the zip file from the Releases page.
2. Copy the `addons` folder from the zip into your server root directory.
   - This will place the plugin DLL, CS2TraceRay DLL, and gamedata file in the correct locations automatically.
3. (Optional) Edit `configs/plugins/ThirdPersonRevamped/ThirdPersonRevamped.json` for custom settings.

Requires CounterStrikeSharp.

For more details, see the [original repository](https://github.com/KKNecmi/ThirdPerson-Revamped).

```json
{
  "OnActivated": " {PURPLE}ThirdPerson {GREEN}Activated",
  "OnDeactivated": " {PURPLE}ThirdPerson {RED}Deactivated",
  "OnActivatedMirror": " {PURPLE}Mirror Mode {GREEN}Activated",
  "OnDeactivatedMirror": " {PURPLE}Mirror Mode {RED}Deactivated",
  "OnWarningMirror": " {PURPLE}Mirror Mode {RED}requires ThirdPerson to be active!",
  "Prefix": " {GREEN}[Thirdperson]",
  "UseOnlyAdmin": false,
  "OnlyAdminFlag": "@css/slay",
  "NoPermission": "You don't have to access this command.",
  "UseSmoothCam": true,
  "SmoothCamDuration": 0.05,
  "StripOnUse": false,
  "IgnoreWallForCamera": false
}
```
