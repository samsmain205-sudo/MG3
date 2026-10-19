# MG3
## Devlog
1. For integers and floats in the inspector they both started as 0. While the string is empty/NULL and the bool was left unchecked meaning the default value is false.

2. The update runs for every frame. It's called as a method with no parameters or taking in arguments. In Timer.cs we use update() to know how much time passed between each frame. While we also used update() to check if the timer ran out in TimerText.cs .

3.  In TimerText.cs uses Start() to begin the timer based on the max so it can start counting down. Update() is then used too check if the timer ran out through GetTimeLeft if it was then gameover is called if the _gamerTime is finshed (reaching<=0).

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
