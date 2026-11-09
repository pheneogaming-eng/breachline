# Breachline

A free tactical shooter that runs in your browser. No install, no download: open the page and play.

## Features

- **5v5 attack and defense.** Attackers plant the Core on site A or B; defenders stop them or defuse it.
- **10 agents** with their own abilities and ultimates (Duelists, Initiators, Controllers, Sentinels).
- **16 guns** across sidearms, SMGs, shotguns, rifles, snipers and machine guns, with learnable recoil patterns.
- **3 maps:** Foundry, Dunelock and Frostgate.
- **Competitive mode** with placement matches, ranks from Copper to Apex, RR and match history.
- **Smart bots** that play the objective, call out enemies, use utility and get tougher as you rank up.
- **The Range** for aim practice, with accuracy, headshot, reaction time and time-to-kill stats.
- **Online multiplayer parties** for up to 10 players, with bots filling empty slots.
- **Valorant-style sensitivity** conversion, 103° FOV, raw mouse input and a dot crosshair.

## Controls

| Key | Action |
| --- | --- |
| WASD | Move (Shift to walk silently, Space to jump, C to crouch) |
| Mouse | Aim and shoot; right click to scope with snipers |
| Q / E / X | Abilities and ultimate |
| F | Hold to plant or defuse |
| R, 1, 2 | Reload, primary, sidearm |
| B | Buy menu |
| Tab | Scoreboard |
| Z | Ping a spot for your team |
| Esc | Pause and settings |

## Play it on GitHub Pages

1. Create a new repository on GitHub and upload `index.html` and this `README.md`.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute your game is live at `https://<your-username>.github.io/<repository-name>/`.

You can also just double-click `index.html` to play it locally.

## Notes

- The game loads [three.js](https://threejs.org) r128 from cdnjs, PeerJS from jsDelivr for multiplayer, and two fonts from Google Fonts, so it needs an internet connection.
- Your rank, settings and match history are saved in your browser (local storage). Clearing browser data resets them.
- Online multiplayer: open the **Multiplayer** tab, press **Create party**, and send your friends the code or the invite link. Players connect directly to the host's browser (peer to peer, using the free [PeerJS](https://peerjs.com) service to find each other), so the host should keep the game tab open and in front. Some school or work networks block peer-to-peer connections; if joining fails, try another network.
- Breachline is an original fan-made game inspired by tactical shooters. It isn't affiliated with or endorsed by any game company.
