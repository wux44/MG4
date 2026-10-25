# MG4
## Devlog


The `FloatAnimation` script makes the fish food move up and down repeatedly. In the `Start()` method, `_timer` is set to `_switchSpeed`, which controls how long the food moves in one direction. The `Update()` method runs every frame and uses `_up` to decide which direction the food moves. If `_up` is `true`, the food moves up, otherwise, it moves down. Each frame, `_timer` decreases by `Time.deltaTime`. When `_timer` reaches zero, it resets to `_switchSpeed`, and `_up` changes to the opposite value. This makes the food keep moving up and down.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)