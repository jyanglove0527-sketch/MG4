# MG4
## Devlog
Write your Devlog here.
## Devlog
The FloatAnimation script makes the fish food move up and down.

The Start() method runs once when the game begins. It sets the _timer variable to _switchSpeed, which is 3 seconds.

The Update() method runs every frame. _up is a bool variable. If _up is true, the food moves up, and if _up is false, the food moves down.

In Update(), _timer also decreases every frame by the amount of time that has passed (Time.deltaTime). When _timer reaches 0 or less, it is reset back to 3 seconds, and _up is set to the opposite value with "_up = !_up". The "!" means "not", so if _up was true it becomes false, and if it was false it becomes true. This makes the food change direction every 3 seconds, so it floats up and down.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)