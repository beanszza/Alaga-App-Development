# ALAGA

A Unity-based gardening game project where players manage plants, tend to a garden, and participate in a market system.

## Project Structure

### Assets
The core game assets organized by type:

- **Scripts/** - Game logic and functionality
  - `Dialogue/` - Dialogue system implementation
  - `Managers/` - Game managers (audio, UI, game state)
  - `Navigation/` - Scene navigation and UI navigation
  - `Plantsandfunctions/` - Plant mechanics and garden functions
  - `Sound/` - Audio management
  - `UI/` - User interface components
  - `game_gold.cs` - Main game script

- **Scenes/** - Game levels and environments
  - `MENU.unity` - Main menu
  - `GARDEN.unity` - Primary garden/gameplay scene
  - `MarketScene.unity` - Market/trading scene

- **Prefabs/** - Reusable game objects
  - `Plant.prefab` - Plant prefab
  - `Pot.prefab` - Pot/planter prefab
  - `AudioManager.prefab` - Audio management system
  - `HarvestIndicator 1.prefab` - Harvest readiness indicator
  - `waterIndicator.prefab` - Water status indicator
  - `Plants/` - Plant variant prefabs

- **Sprites/** - 2D visual assets
- **Fonts (FOR GAME)/** - Pixel font assets for UI
- **Sounds/** - Audio files and music
- **TextMesh Pro/** - TMP font assets

### Configuration
- `InputSystem_Actions.inputactions` - Input system configuration
- `ProjectSettings/` - Unity project configuration

## Getting Started

### Prerequisites
- Unity 2020.3 LTS or later
- TextMesh Pro
- Input System package

### Opening the Project
1. Clone or download the project
2. Open with Unity
3. Load the `Assets/Scenes/MENU.unity` scene to start

## Features

- **Garden Management** - Plant, water, and harvest crops
- **Dialogue System** - NPC interactions and quest text
- **Audio System** - Background music and sound effects
- **UI System** - Menu navigation and in-game UI
- **Input System** - Keyboard and controller support
- **Market System** - Trade harvested crops

## Scripts Overview

- **Managers** - Handle core game systems (audio, UI state, game flow)
- **Plantsandfunctions** - Define plant growth mechanics and gardening interactions
- **Dialogue** - Manage dialogue trees and character interactions
- **Navigation** - Control scene transitions and menu flow
- **UI** - Display and manage user interface elements
- **Sound** - Audio playback and management

## Building & Running

- **Play in Editor** - Press Play in Unity to test
- **Build** - Use File > Build Settings to create a standalone executable

## Contributing

When adding new features:
1. Place scripts in appropriate `Scripts/` subdirectory
2. Create prefabs in `Prefabs/` folder
3. Add audio to `Sounds/` folder
4. Add sprites to `Sprites/` folder

## License

[Add license information here]

## Contact

[Add contact information here]
