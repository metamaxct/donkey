# Raíl Salvaje — itch.io kit

## Subir el juego / Uploading
1. `python tools/build_itch.py` → `dist/rail-salvaje-itch.zip`
2. itch.io → *Create new project* → **Kind of project: HTML** → sube el zip y marca *This file will be played in the browser*.
3. Viewport **1280 × 720**, activa *Mobile friendly* y *Fullscreen button*. Desactiva *Automatically start on page load* (el audio necesita un clic).
4. Capturas: `dist/itch-page/shot*.jpg` (se generan con `python tools/shots_server.py 8776` y `tools/test.js`).
5. Género: *Platformer / Racing* · Etiquetas: `2d`, `arcade`, `local-multiplayer`, `split-screen`, `gamepad`, `roller-coaster`, `minecart`, `speedrun`.

---

## Página — Español

**Raíl Salvaje** es una montaña rusa arcade en vagoneta. Salta, frena y cambia de vía a toda velocidad por 5 mundos pintados a mano en código: una mina de cobre, una selva, un glaciar, un volcán y una ciudad de neón. Cada vuelta cambian de ambiente (día, noche, cataclismo) y cada tres llega un remix más rápido.

- 5 mundos × 3 ambientes, con jefes que te persiguen: la roca rodante, la serpiente reina, la avalancha, el gusano de lava y el dron patrulla.
- Tramos bajo el agua, túneles a oscuras donde tú enciendes las luces, vagonetas desbocadas, cambios de vía y carriles paralelos.
- Barriles secretos que llevan a **salas bonus** llenas de gemas contrarreloj.
- **Pico**, el loro compañero: te avisa de los peligros, te da doble salto y aguanta un golpe por ti.
- **Tienda** de pinturas, estelas y sombreros con las gemas que recoges.
- **Contrarreloj con fantasma** y **códigos de fantasma** para retar a tus amigos.
- **Carrera a 2 jugadores** a pantalla partida (un teclado o dos mandos).
- Reto diario, 3 dificultades, avisos de obstáculos configurables y opciones de accesibilidad.
- Mando, teclado y táctil. Español e inglés.

**Controles:** Espacio/W saltar · S frenar · E cambiar de vía · Esc pausa. Mando: A saltar, B/RT frenar, Y/RB cambiar de vía.

## Page — English

**Raíl Salvaje** ("Wild Rail") is an arcade mine-cart roller coaster. Jump, brake and switch tracks at full speed through 5 worlds painted entirely in code: a copper mine, a jungle, a glacier, a volcano and a neon city. Every lap each world changes its mood (day, night, cataclysm), and every third lap brings a faster remix.

- 5 worlds × 3 moods, with bosses on your tail: the rolling boulder, the serpent queen, the avalanche, the lava worm and the patrol drone.
- Underwater stretches, pitch-black tunnels where you switch the lights on, runaway carts, track forks and parallel lanes.
- Secret barrels that blast you into **bonus rooms** full of gems against the clock.
- **Pico** the parrot sidekick: warns you about hazards, grants a double jump and takes a hit for you.
- **Shop** with cart paints, trails and hats bought with the gems you collect.
- **Time trial with ghosts** and shareable **ghost codes** to challenge your friends.
- **2-player split-screen race** (one keyboard or two gamepads).
- Daily challenge, 3 difficulties, configurable hazard warnings and accessibility options.
- Gamepad, keyboard and touch. English and Spanish.

**Controls:** Space/W jump · S brake · E switch track · Esc pause. Gamepad: A jump, B/RT brake, Y/RB switch track.
