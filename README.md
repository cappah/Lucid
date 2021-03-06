## C++ Lucid - 2D Game Engine + Game w/ 3D lighting

### Notes

- Project and librarires (if relevant) built with MSVC 140 (Visual Studio Community 2015)
- Pre-compiled libraries added, but building 3rd party libraries yourself is advised.
- Copy .DLLs from Libs/Pre-compiled DLLs/ over to executable folder or retrieve/compile them yourself.
- Repository is not built around supporting different run-time configurations.

### Lucid

Lucid is the combined effort of creating a game by first creating a custom, organized and well-structured game engine and then building a game on top of it. Lucid is a game about dynamically switching physics state between specific colored block based on whatever colored light the player activates through its lantern. The player is required to influence the correct physics collision states at the exact right time to build a path for moving forward. Requires memory, quick reflexes, and the ability to look ahead.

Lucid is an attempt to experiment with different approaches of designing and building a larger game and game-engine. This includes separating render state from game logic and separating physics state from both the game logic and render logic. Lucid features an entity component system for defining the game logic and uses an event queue system for inter-module communication. The goal of the system was to decouple irrelevant components and finding a strong balance between well-regarded design patterns and the 
system's requirements.

For more information (including media) regarding Lucid: see [joeydevries.com](http://joeydevries.com/#portfolio).

### Features

- Normal mapped 3D lighting simulation of 2D sprites.
- Dynamic physics collision state management.
- Entity-component based system architecture.
- Event-based message queue system for inter-module communication.
- Signed distance field text rendering.
- Fully integrated 2D physics system.
- 2D spritesheet animation.
- 2D particle engine.
- Custom levels can be built by anyone using the [Tiled](http://www.mapeditor.org/) level editor due to Lucid's
seamless integration with the Tiled XML format. See Bin/levels/tutorial.tmx for Lucid's Tiled components.
- Location-based audio falloff.
- Interesting and challenging puzzles.