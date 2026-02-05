# Placeholder Scenes (Xogot 3D Tutorial)

This project contains the example scenes and assets used in the **Xogot 3D Modular Series – Introduction to Placeholder Scenes** tutorial by **Erin Uptegrove**.

It demonstrates how to build **placeholder scenes** in **Xogot** — the iPad and iPhone port of the Godot Engine — using scene instancing to create reusable players, environment pieces, and obstacles that can be easily replaced later with final art.

The project focuses on structuring scenes correctly from the start so gameplay can be developed and tested early, while making it straightforward to swap placeholder geometry for finished models without breaking existing levels.

---

## Features

* Create reusable **placeholder scenes** for players, environments, and obstacles
* Use **scene instancing** to share changes across multiple levels
* Build placeholder scenes with physics bodies and collision shapes
* Resize and align placeholder meshes and colliders correctly
* Use **CSG** to prototype more complex placeholder shapes
* Bake CSG to **MeshInstance3D** for improved performance
* Add and configure collision shapes for placeholder geometry
* Replace placeholder models with final assets while preserving gameplay
* Update all instances automatically by modifying the original scene

---

## Notes

This project builds on concepts introduced in the **Placeholder Models** tutorial and focuses on **scene structure and reuse**, rather than individual geometry creation.

Key ideas demonstrated include:

* Keeping placeholder scenes centered and aligned to the grid
* Separating visuals, collisions, and scripts for easier replacement
* Avoiding performance-heavy collision types for moving objects
* Using instancing to safely replace placeholder content later

---

## Video Tutorial

Watch the full walkthrough on the [Xogot YouTube Channel](https://youtube.com/@xogot):

[Introduction to Placeholder Models in Xogot – 3D Game Development in Godot on iPad](https://youtu.be/hc7MlyQYMdQ)

[Introduction to Placeholder Scenes in Xogot – Reusable Players and Objects](https://youtu.be/CfEWURgQuW0)

---

## How to Use

1. Download or clone this repository:

   ```bash
   git clone https://github.com/xogot-projects/Xogot-Placeholders.git
   ```

2. Open the project in **Xogot** on iPad or iPhone.

3. Explore the included placeholder scenes:

   * Player placeholder scenes
   * Environment and obstacle placeholders
   * CSG-based placeholder examples

4. Add the placeholder scenes to a level as **instances**, adjust their transform as needed, and preview the game.

5. Replace placeholder geometry in the original scenes to see changes propagate automatically to all instances.
