# Robot Adventure

A single-file 3D browser game: play **Blue, the Robot Warrior** in a procedurally generated, endless tropical meadow, and fight worm monsters and icy dragons. Playable on desktop, Android phones and Steam Deck. Everything (models, textures, code) is embedded in `index.html`.

**Play:** enable GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root) and open the Pages URL, or just open `index.html` in a modern browser.

## Controls
| Action | Keyboard | Touch |
|---|---|---|
| Move / run | WASD or arrows / Shift | left-side joystick / RUN |
| Look | drag, Q / E | drag right side |
| Jump | Space | JUMP |
| Attack (tap again for combo) | J or Enter | ATTACK |
| Combo / Flourish / Stance / Draw / Showreel | K / F / C / R / T | – |
| Zoom | wheel, + / − | pinch |
| FPS counter | G | FPS button |

Settings (⚙): zoom, camera sensitivity, light, dragon / worm / tropical-plant / fern density, fullscreen. Settings are remembered.

## Combat
Worms chase you, bite for damage and can be dodged by jumping. Icy dragons are rare and tough: they bite up close and spit ice bolts from range (jump to dodge both). The combo ends on the blow that finishes the last enemy in reach. Attack and the spin combo damage worms in front of you (the combo hits all around). Health regenerates slowly out of combat; if you fall you respawn at the start.

## Credits (all CC BY 4.0)
- "Blue, The Robot Warrior" by AJ (ArneJans)
- "Simple grass chunks" (ground textures) by 3dhdscan
- "Tropical Plants Pack M02P" by MozzarellaARC
- "icy dragon" by chengzijieczj
- "Worm Monster" by CR!STALLL
- "fern grass 02" by Digital screen official

Built with [three.js](https://threejs.org/).

## Progression
Killing monsters earns XP. Each level raises max health (+15) and damage (+8%) and fully heals you. Progress is saved in the browser. Health and XP bars sit at the bottom-left of the screen.
