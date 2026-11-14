# SHOOT GUN

A browser-based first-person shooter set in a rainy container port. Cut three uplink relays while drones ("Gulls") and robot dogs ("Hounds") hunt you.

<img width="1685" height="906" alt="SHOOT GUN gameplay" src="https://github.com/user-attachments/assets/8dd32149-90f4-4d69-a573-4411a49a9ba9" />

## Run it

```sh
python3 -m http.server 8731
```

Then open http://localhost:8731 and click the page to capture the mouse and start the sound.

The game is a single-file browser project: `index.html` (~1.4 MB). It bundles Three.js and loads fonts from Google Fonts.

## Rebranding notes

The original game is preserved. The browser title, loading screen, title screen, debrief text, in-game terminal labels, and diagnostic labels have been changed to **SHOOT GUN**. An obsolete Claude-specific viewport meta tag was removed. Gameplay systems, level design, models, rendering, controls, and bundled Three.js code were not intentionally changed.

## Original game and attribution

SHOOT GUN is a rebranded personal modification of the public Saltline game. Credit for the original game design and implementation belongs to its original author.

- Original playable demo: https://realcodebear.github.io/saltline-fable-5.2/
- Original artifact: https://claude.ai/artifact/BGY1SztrAYcJQHSsnHHGmp
- Original project post by Felix Rieseberg (Anthropic): https://x.com/felixrieseberg/status/2119925633564463609

The original project was built with Claude Fable 5.2. The author-reported figures about the build process and cost have not been independently verified.
