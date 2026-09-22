# Asset sources

- Reference: https://dogstudio.co/
- Runtime layer: Three.js particles, HUD, scanline and interaction effects in `src/js/main.js`.
- Foreground mini mecha: procedural Three.js geometry in `src/js/main.js`, reshaped around the supplied image's white/navy/red/gold armor palette, V-fin, backpack, shield and rifle silhouette.
- Test aircraft: `glb/star_sparrow_modular_spaceship.glb`, rendered as the foreground GLB when available. Source and license details are copied to `assets/aircraft/star_sparrow_license.txt`.
- User-provided Gundam visual: extracted from `素材/scene.pkg`, whose `project.json` identifies the package as a scene titled `高达`. The browser uses the extracted `gundam-reference.jpg` as the hero visual; the package did not contain a directly loadable glTF model.
- Backup model asset: https://threejs.org/examples/models/gltf/RobotExpressive/RobotExpressive.glb
  - Model README: https://github.com/mrdoob/three.js/blob/dev/examples/models/gltf/RobotExpressive/README.md
  - License: CC0 1.0, by Tomas Laulhe; modifications by Don McCurdy. It is kept locally for future model replacement and is not used by the current scene.
  - Local location: archived at `素材/backup-models/RobotExpressive.glb` together with its license file.
- Matcap texture (no longer referenced by the page): https://github.com/nidorx/matcaps/blob/master/256/070B0C_B2C7CE_728FA3_5B748B-256px.png
  - Repository license note: see `MATCAPS-LICENSE.md`.
  - Local location: archived at `素材/backup-textures/matcap-ice.png` together with its license file. The current scene uses PBR materials instead, so this texture is not bundled.

The page copy and project names in this prototype are original placeholders.
