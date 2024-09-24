# The Maze Project - MVP
**(A 3D Game created using SDL2)**

The Maze Project is an engaging 3D maze game created using the SDL2 graphics library. Players navigate through a maze, avoiding walls and obstacles while collecting rewards and tracking their progress. The MVP focuses on core functionalities like maze rendering, player controls, movement mechanics, collision detection, and basic textures.

## Key Features:

- **Maze Structure:**  
  - Walls are represented by a 2D array and rendered using SDL2.

- **Player Controls:**  
  - Movement and rotation are controlled by arrow keys, with user input processed via SDL_Event.

- **Movement Mechanics:**  
  - Players can move forward, backward, left, and right within the maze.

- **Collision Detection:**  
  - Prevents players from passing through walls by detecting and blocking collisions.

- **Maze Data Management:**  
  - A parser reads maze data from a text file and stores it in a 2D array.

- **Textures:**  
  - Basic wall textures are rendered to enhance visual appeal.

---

## Progress and Challenges

### Progress Rating: **7/10**

This week has seen significant progress in The Maze Project. Basic movement mechanics are functional, allowing smooth player navigation using arrow keys. Collision detection is partially implemented, ensuring players cannot move through walls. Development of the maze parser for dynamic maze generation is also underway. However, challenges remain with loading textures and integrating full user input functionality.

### Completed Aspects:
- Basic player movement.
- Initial collision detection.
- Maze data parser.

### Incomplete Aspects:
- Wall textures are not yet implemented.
- Full user input handling is still in progress.
- Main menu and save/load functionalities need to be developed.

---

### Challenges

#### Most Difficult Technical Challenge:
The most difficult technical challenge this week was implementing accurate collision detection. Initially, a simple bounding box collision method led to inconsistencies, with the player occasionally colliding with walls incorrectly. To resolve this, I adopted a more robust system that accounts for the dimensions of both the player and walls, recalibrating bounding boxes. After thorough testing and debugging, I successfully implemented a system that accurately detects collisions while allowing smooth player movement.

#### Most Difficult Non-Technical Challenge:
The primary non-technical challenge has been time management. Balancing coursework, personal commitments, and project development led to frequent distractions. I often lost track of time when troubleshooting minor coding issues. To address this, I implemented time-blocking techniques, dedicating specific periods to focused work and eliminating distractions by disabling notifications. This improved my overall concentration and productivity.

---

## Screenshots

**Screenshot 1:**  
Player navigating the maze.  
![Player Navigating Maze](https://i.postimg.cc/RVkMC982/1.png)

**Screenshot 2:**  
Collision detection in action.  
![Collision Detection](https://i.postimg.cc/GmvbHVnt/2.png)

---

Feel Free To Contribute!
