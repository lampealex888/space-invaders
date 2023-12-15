# Space Invaders

Welcome to Space Invaders, a classic arcade game brought to life in Python using the Pygame library. Defend Earth against the relentless onslaught of alien invaders in this nostalgic and thrilling gaming experience.

### Architecture 

Space Invaders follows a simple yet effective architecture, leveraging the Pygame library for game development. The main components include:

1. Game Loop:
   - The core of the game is driven by the main game loop found in the SpaceInvaders class, where user input, updates to game entities, and rendering are handled.
2. Entities:
   - Entities such as the player's spaceship, alien invaders, bullets, and barriers are implemented as distinct classes. Each entity has its logic for movement, collision detection, and rendering.
3. Collision Detection:
   - Collision detection is a crucial aspect of the game, ensuring that bullets hit their targets and that the player's spaceship interacts appropriately with the alien invaders and barriers.
4. Game State Management:
   - The game state is managed to handle transitions between different phases, such as the start screen, gameplay, and game over screen.
  
### Technical Details

- Language: Python
- Library: Pygame
- Compatibility: Python 3.x
