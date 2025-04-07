# Avatar State

**Avatar State** is a turn-based, anime-inspired fighter game developed in Python. Players create characters with elemental specialties and engage in strategic battles using a set of unique moves. The game features a command-line interface with randomized stats, move accuracy, and turn-based combat.

## Features

- **Two-Player Local Battles**: Engage in battles with a friend in a local multiplayer setup.
- **Customizable Fighters**: Name your fighter and select from seven elemental specialties:
  - Fire, Water, Earth, Air, Electric, Light, Dark.
- **Randomized Health Points (HP)**: Fighters start with a randomly assigned HP between 450 and 500.
- **Unique Moves per Specialty**: Each specialty offers four predefined moves with fixed damage values.
- **Elemental Weakness Framework**: A foundational system for elemental weaknesses is in place, with future updates planned to implement dynamic damage scaling.
- **Strategic Combat Mechanics**: Moves have varying damage outputs and hit probabilities, adding a layer of strategy to each battle.
- **Turn-Based Gameplay**: Players alternate turns, selecting moves to deplete their opponent's HP.

## Gameplay Overview

1. **Fighter Creation**
   - Each player inputs a name and selects an elemental specialty.
   - HP is randomly assigned between 450 and 500.

2. **Elemental Specialties & Moves**
   - Each specialty is associated with four unique moves. For example:

     **Fire Specialty Moves**:
     - Fire Punch (75 DMG)
     - Flower Bomb (90 DMG)
     - Lighter Strike (20 DMG)
     - Dragon Snap (150 DMG)

3. **Battle Mechanics**
   - Players take turns selecting moves to attack their opponent.
   - Each move has a specific damage value and a hit probability influenced by its damage output.
   - A missed attack results in no damage dealt.
   - The battle continues until a player's HP reaches zero, resulting in their defeat.

4. **Elemental Weakness System (Planned for Future Release)**
   - A framework for elemental weaknesses is established, with future updates intended to implement dynamic damage multipliers based on these weaknesses. The planned weaknesses are:
     - Fire: Weak to Water, Light, Dark
     - Water: Weak to Electric, Light, Dark
     - Earth: Weak to Air, Light, Dark
     - Air: Weak to Fire, Light, Dark
     - Electric: Weak to Earth, Light, Dark
     - Light: Weak to Dark
     - Dark: Weak to Light

## How to Run

### Prerequisites

- Python 3.x installed on your system.

### Running the Game

1. Clone or download the repository containing the game script.
2. Navigate to the directory containing the script.
3. Execute the script using Python:

   ```bash
   python avatar_state.py
Follow the on-screen prompts to create your fighters and commence the battle.

## File Structure
Copy
Edit
Avatar-State/
├── avatar_state.py
└── README.md
## Class Structure
Fighter: Manages the initialization of a fighter's name and HP.

Specialty: Handles the selection of an elemental specialty and defines associated weaknesses.

Moves: Assigns a set of moves to the fighter based on their chosen specialty.

PlayerSummary: Displays the fighter's statistics prior to the commencement of battle.

Battle: Contains the core game loop, managing turn-based combat and determining the outcome.

## Roadmap
 Implement dynamic damage scaling based on elemental weaknesses.

 Develop an AI opponent for single-player gameplay.

 Introduce move customization options.

 Create a graphical user interface (GUI) using libraries such as tkinter or pygame.

 Implement functionality to save and load fighter data.

Note: This game is inspired by elemental combat themes prevalent in various anime series. It is an independent project and is not affiliated with any specific anime franchise.

pgsql
Copy
Edit

This `README.md` provides a comprehensive overview of **Avatar State**, detailing its features, gameplay mechanics, setup instructions, and future development plans. It is structured to offer clarity and ease of navigation for users and contributors alike.
::contentReference[oaicite:0]{index=0}
 
