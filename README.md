# 🗼 Unreal Tower Climber Demo

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.4-blue?logo=unrealengine)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Mac%20%7C%20Linux-lightgrey)
![Status](https://img.shields.io/badge/Status-Active-success)

A 2D vertical scrolling tower climbing game built with Unreal Engine 5.4. Navigate through procedurally generated rooms filled with obstacles, spikes, and platforms while climbing to the top of an endless tower!

## ✨ Features

- 🎮 **2D Side-Scrolling Gameplay** - Classic platformer mechanics in a modern Unreal Engine environment
- 🏗️ **Procedural Room Generation** - Unique layouts with multiple room types (single, double, and triple platform configurations)
- ⚠️ **Dynamic Obstacles** - Navigate through spikes, buttons, and environmental hazards
- 💖 **Health System** - Hearts-based health tracking with visual UI feedback
- 🎯 **Score Tracking** - Compete for high scores as you climb higher
- 🎨 **Custom 2D Art** - Hand-crafted sprites for characters, platforms, and obstacles
- 🔊 **Audio System** - Integrated sound effects and background music
- 📱 **Complete UI** - Title screen, game over screen, and in-game HUD
- 🤖 **NPC System** - Includes enemy characters and interactions

## 🎯 Game Mechanics

- **Vertical Progression**: Climb through rooms that scroll vertically
- **Obstacle Avoidance**: Navigate through spikes, barriers, and other hazards
- **Platform Navigation**: Jump between single, double, and triple platform configurations
- **Survival Challenge**: Maintain your health while climbing as high as possible

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

- **Unreal Engine 5.4** or later ([Download](https://www.unrealengine.com/download))
- **Visual Studio 2022** (for Windows) or **Xcode** (for Mac) with C++ development tools
- Minimum 8GB RAM (16GB recommended)
- DirectX 11 or 12 compatible graphics card

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/JohnFrancis123/UnrealTowerClimberDemo.git
   cd UnrealTowerClimberDemo
   ```

2. **Open the project**
   - Navigate to `PROG21308ASG2` folder
   - Right-click on `PROG21308ASG2.uproject`
   - Select "Generate Visual Studio project files" (Windows) or "Generate Xcode project" (Mac)
   - Open the generated solution file

3. **Build the project**
   - Build the project in your IDE (Visual Studio/Xcode)
   - Or double-click `PROG21308ASG2.uproject` to open directly in Unreal Editor

4. **Launch the game**
   - In Unreal Editor, click the **Play** button
   - Or use **Standalone Game** mode for full-screen experience

## 🎮 How to Play

1. **Start Screen**: Launch the game to see the title screen
2. **Controls**:
   - Move left/right with arrow keys or A/D
   - Jump with spacebar
   - Navigate menus with mouse
3. **Objective**: Climb as high as possible while avoiding obstacles
4. **Health**: Keep an eye on your hearts - running out means game over!
5. **Score**: Your score increases as you progress upward

## 📁 Project Structure

```
UnrealTowerClimberDemo/
├── PROG21308ASG2/                    # Main tower climber game
│   ├── Content/
│   │   ├── 2DCharacterArt/           # Character sprites and animations
│   │   ├── 2DCharacterBlueprints/    # Player and NPC blueprints
│   │   ├── Audio/                    # Sound effects and music
│   │   ├── BackgroundArt/            # Background artwork
│   │   ├── Health/                   # Health system assets
│   │   ├── LevelArt/                 # Platform and wall sprites
│   │   ├── Levels/                   # Game levels and maps
│   │   ├── ObstacleArt/              # Spike and button sprites
│   │   ├── Obstacles/                # Obstacle blueprints
│   │   ├── Rooms/                    # Room templates
│   │   ├── Spawners/                 # Object spawning systems
│   │   └── UI/                       # User interface widgets
│   ├── Config/                       # Game configuration files
│   └── PROG21308ASG2.uproject        # Main project file
│
└── GameDevTestProject/               # Development testing project
    └── GameDevTestProject.uproject   # Test project file
```

## 🔧 Technical Details

- **Engine Version**: Unreal Engine 5.4
- **Project Type**: Blueprint-based with Paper2D
- **Enabled Plugins**:
  - ModelingToolsEditorMode
  - MultiUserClient
- **Primary Language**: Blueprint Visual Scripting
- **Asset Types**: 2D Sprites, Materials, Blueprints, Audio

## 🎨 Key Components

### Blueprints
- **2dCharacter**: Main player character with movement and physics
- **NPC**: Enemy character implementation
- **ObsRoom Variants**: Single, double, and triple platform room templates
- **Obstacle System**: Spikes, buttons, and barriers with spawning logic
- **UI Widgets**: Title screen, game over screen, HUD, and health display

### Systems
- **Health System**: Visual heart-based health tracking
- **Spawner System**: Dynamic obstacle and room generation
- **Score System**: Points tracking and display
- **Room Management**: Procedural room generation and cleanup

## 🚀 Development

This project was developed as part of PROG21308 coursework, demonstrating:
- 2D game development in Unreal Engine
- Blueprint visual scripting
- Game mechanics implementation
- UI/UX design
- Asset integration and management

## 🤝 Contributing

This is an educational project, but suggestions and feedback are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 License

This project is available for educational purposes. Please respect any third-party assets and their respective licenses.

## 👤 Author

**John Francis**
- GitHub: [@JohnFrancis123](https://github.com/JohnFrancis123)

## 🙏 Acknowledgments

- Unreal Engine and Epic Games for the game engine
- PROG21308 course materials and instructors
- The Unreal Engine community for documentation and support

---

**⭐ If you found this project interesting, please consider giving it a star!**

*Built with ❤️ using Unreal Engine 5.4*
