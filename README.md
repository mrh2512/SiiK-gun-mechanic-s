https://siik-scripts-store.tebex.io/package/7295236

SiiK Gun Mechanics (Standalone)
Safety Switch • Fire Modes • Weapon Jamming • Minimal UI (Icons Only)

SiiK Gun Mechanics is a lightweight standalone FiveM script that adds realistic firearm handling to your server with a clean, modern 3-icon HUD. Toggle a safety, cycle fire modes, and deal with weapon jams — all without spammy notifications.

Built for RP servers that want better gunplay without heavy dependencies.

✅ Features
🔒 Safety Switch

Toggle weapon safety on/off instantly

Prevents firing while enabled

Works with all weapons (or only applicable weapons — configurable)

🔁 Fire Mode System (Auto Weapons Only)

Fire mode controls apply to automatic-capable weapons:

Single

Burst

Auto

✅ Includes a config option to disable any mode (e.g. disable burst entirely).

⚠️ Weapon Jamming

Random jam chance per shot (configurable)

When jammed: weapon won’t fire until cleared

Hold Unjam key to clear the jam

Uses an immersive reload sound when successfully clearing

🖥️ Minimal Icon HUD (Top-Left)

Icons only (no text notifications)

Appears only when a gun is drawn

Icons have different colours and light up/glow when active:

Safety (Green)

Jammed (Red + pulses)

Fire Mode (Blue)

🎮 Default Keybinds

(Players can rebind in FiveM Key Bindings)

N = Safety Toggle

J = Cycle Fire Mode

R = Unjam (Hold)

⚙️ Configuration

Easy config options including:

Jam chance per shot

Jam cooldown + unjam hold time

Burst shot count + delay

Safety affecting all weapons or only “auto weapons”

Enable/disable specific fire modes:

Config.ModeEnabled = {
  single = true,
  burst  = true,
  auto   = true,
}
📦 Weapon Support

Fire mode system applies to a configurable list of automatic weapons (SMGs, ARs, MGs, etc.).
Add or remove weapon hashes easily in config.lua.

🧩 Framework Support

✅ Standalone
No ESX / QBCore required.

📥 Installation

Drag the folder into your server resources:

resources/[standalone]/SiiK-gun-mechanics

Add to server.cfg:

ensure SiiK-gun-mechanics

Restart your server (or restart SiiK-gun-mechanics)

Important: FiveM can cache NUI. If UI doesn’t update after installing, clear client cache.

❓ FAQ
“Why don’t my keys work after changing defaults?”

FiveM saves binds per player. Players must change binds in:
Settings → Key Bindings → FiveM

“Does this affect pistols/snipers?”

Fire modes are intended for automatic-capable weapons only (configurable).
Safety can optionally apply to all weapons.

“Does it spam notifications?”

No. No chat spam, no popups — only the HUD icons.

✅ Performance

Designed to be lightweight and optimized:

Minimal loops

Only updates HUD when needed

No server-side load (client-only mechanics)

📌 Terms / Notes

Do not resell or redistribute.

Modifications for personal/server use are fine.

Support requires you to provide console errors if something conflicts.

📞 Support

If you need help:

Send your client console (F8) errors

Your server build version

Any weapon packs you’re using
