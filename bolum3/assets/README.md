Add custom player assets here:

- player.glb (recommended): GLB/GLTF file with a running animation. Prefer animation named "Run" or provide at least one animation; the loader will pick "Run" if present, otherwise the first animation.
- runner.png (optional): a 2D sprite sheet or single-frame PNG. If you add a sprite sheet, name it `runner.png` and update the frame count in the code if needed.

Tips:
- Export GLTF with embedded textures and animations.
- Recommended vertical scale: model standing height ≈ 1 unit in Three.js so it matches the game ground.
- If you add `player.glb` the game will try to load it automatically; otherwise a simple SVG placeholder runner is used.