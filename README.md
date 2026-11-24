# NexBridge

**Use more than one mod manager without fighting over Nexus links.**

NexBridge is a small Windows tray app that catches Nexus Mods **"Mod Manager Download"** (`nxm://`) links and sends each one to the mod manager *you* picked for that game. No more re-linking `nxm` every time you switch between managers.

📥 **Download:** [NexBridge on Nexus Mods](https://www.nexusmods.com/site/mods/2539)

---

## How it works

Windows only lets one program own `nxm://` links. NexBridge takes that spot and acts as a router:

1. You click **Mod Manager Download** on a Nexus mod page.
2. NexBridge receives the link and checks which game it's for.
3. It hands the link to the manager you chose for that game.

That's it — NexBridge doesn't download or install mods itself. Your mod managers keep doing what they already do.

## Features

- **Per-game routing** – add the games you play and pick a manager for each one.
- **Default manager** – catches links for any game you haven't set up.
- **Multiple installs of the same manager** – rename managers so you can point two copies at different games.
- **Enable / disable managers** with a toggle, plus Browse and Test buttons for each path.
- **Runs quietly in the system tray**, with an option to show or hide the tray icon.
- **Update notices** – NexBridge checks for new versions and lets you know; you download the update yourself.

## Getting started

1. Download and run the installer from the [Nexus page](https://www.nexusmods.com/site/mods/2539).
2. Open NexBridge and let it register itself as the `nxm` link handler.
3. In **Managers**, add your mod managers and set their installation paths.
4. In **Games**, add your games and choose a manager for each.
5. Set a **default manager** in the top box for everything else.

## About this repository

This repo hosts `version.json`, the small file NexBridge reads to check for updates. The app itself is distributed through Nexus Mods.

## Support

Questions, bugs or ideas? Post on the [Nexus page](https://www.nexusmods.com/site/mods/2539) or email **oddboxcode@gmail.com**.

## License

Released under the [MIT License](LICENSE). © 2026 OddBoxCode.

*NexBridge is a fan-made tool and isn't affiliated with or endorsed by Nexus Mods.*
