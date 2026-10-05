# Minigame 1
## Devlog
The scene, GameObjects, and components all work together to create the basis of a game. The scene of a game relates to the environment, which encompasses the GameObjects, and, by extension, the components. The GameObjects make the scene unique; the types of objects used depend on the type of game that’s being created. The components are essentially the part that adds function to a GameObject. As such, the relationship between Components, GameObjects, and Scenes can be described as a Matryoshka doll. The scene would be the outermost doll, as it is the main part of a game that the player sees. The doll inside of the outermost one would be the GameObjects, as they make up the scene. The smallest doll, nestled inside both the GameObjects and scene dolls, would be the components. 

For instance, in this minigame (minigame 1), the scene is, of course, the environment itself. The GameObjects however, could include everything from the spikes to the coins. When the player touches the spikes, they respawn. In a similar fashion, when the player touches a coin, it disappears, and they gain a point. The reason for this is due to the components adding function to the GameObject. In short, the components are the cause of the interactivity of the spikes and coins.
 
## Open-Source Assets
- [Starter first-person assets](https://assetstore.unity.com/packages/essentials/starter-assets-firstperson-updates-in-new-charactercontroller-pa-196525)
- [Low poly platformer kit](https://assetstore.unity.com/packages/3d/environments/lowpoly-platformer-kit-free-modular-stylized-blocks-319018 )
