# NOTICE — third-party material and attribution

This project ("Anatomesh" — 3D Anatomy Practical Quiz: `index.html`, `src/bones.html`, `src/muscles.html`, `src/nerves.html`) is licensed under the
**Creative Commons Attribution-ShareAlike 4.0 International** licence (see `LICENSE`).
Copyright of the original quiz design, code, question text and terminology tables: © [LIN SIA SHENG], [2026].

It incorporates and modifies the following third-party works. Each remains the property of its
authors and is credited as they request.

## BodyParts3D
> BodyParts3D, © The Database Center for Life Science, licensed under CC Attribution-Share Alike 2.1 Japan.

- Source: https://lifesciencedb.jp/bp3d/
- Licence: https://creativecommons.org/licenses/by-sa/2.1/jp/
- Used for: the 3D bone meshes (skull, vertebrae, ribs, sternum, pectoral and pelvic girdles, limbs, hands and feet) in `bones.html`, and the bone context shown in `muscles.html` and `nerves.html`.
- Modifications: converted to a compact binary format, re-oriented, joined/split where needed (e.g. sacrum and coccyx), smoothed, and — for the skull — cranial canals were carved into the meshes.
- Parts of this project derived from BodyParts3D remain subject to the CC BY-SA 2.1 Japan terms (attribution and share-alike).

## Z-Anatomy
> Z-Anatomy, licensed under CC BY-SA 4.0 — https://www.z-anatomy.com/

- Licence: https://creativecommons.org/licenses/by-sa/4.0/
- Used for: muscle meshes and muscle origin/insertion areas (`muscles.html`); nerve centre-lines (curves) and the muscle meshes shown as "supplied muscles" (`nerves.html`); ligament, meniscus and joint-capsule meshes, anatomical label positions, and nerve/vessel centre-lines used to place and carve cranial canals (`bones.html`).
- Modifications: re-registered onto the BodyParts3D bones, simplified/quantised, smoothed and re-coloured; origin/insertion areas re-classified and side-corrected; centre-lines converted into canal cut-outs; nerve curves re-registered and rebuilt as thin tubes. The inferior gluteal nerve is not present in Z-Anatomy and is drawn as a schematic path by the author.

## Course material
Structure names follow the course lab list; origin/insertion/action/innervation and nerve root/course/supply/injury texts were written by the author from standard anatomy references. Lecturer slide images are **not** included.

## Software
- [three.js](https://threejs.org/) — MIT License, © three.js authors (bundled in each HTML file).
- Build/test tooling (esbuild, Playwright, three-mesh-bvh, Blender `bpy`, trimesh) is used only to produce the files and is not redistributed.

## Disclaimer
Provided "as is" for education only. Anatomical positions of some structures are approximate and the models are not suitable for clinical or diagnostic use.
