# Unreal Degree
Unreal Engine Project

## Table of Contents

- [Installation](#installation)
- [Resources](#resources)
- [License](#license)

## Installation

To run the project locally on your machine, follow these steps:

1. Clone the repository to your local system using the following command:

   ```shell
   git clone https://github.com/Panuh404/UnrealDegree.git
   ```

2. Navigate to the project directory:

   ```shell
   cd UnrealDegree
   ```

3. Right click on UnrealDegree.uproject and Generate Visual Studio project files

4. Run ProjectMP.uproject on Unreal Engine 5.3

## Resources

+ [UPROPERTY Guide](https://benui.ca/unreal/uproperty/)
+ [Console Variables C++](https://docs.unrealengine.com/5.2/en-US/console-varaibles-cplusplus-in-unreal-engine/)

### Introduction
- Naming Conventions:
   + [Allar's Guide](https://github.com/Allar/ue5-style-guide)
   + Consistent naming allow quick Ctrl+P asset searches
- Comprehending Projects and File Structure:
   + [Introduction to the Launcher](https://dev.epicgames.com/community/learning/courses/qpR/unreal-engine-comprehending-projects-and-file-structure/jR8/introduction-to-the-launcher)

### Project Start

- Class Hierarchy: Object -> Actor -> Pawn -> Character -> MyCharacter (Example: SCharacter)
  - More -> [Gameplay Framework Guide](https://www.tomlooman.com/unreal-engine-gameplay-framework/)
- Class Prefixes:
  - U: Classes deriving from UObject
  - A: deriving from Actor
  - F: Structs
  - E: Enums
  - I: Interfaces
- Unreal Property System:
  - Unreal Macros: UPROPERTY, UFUNCTION, UCLASS, USTRUCT, UENUM
  - More:
    * [Unreal Property System](https://www.unrealengine.com/en-US/blog/unreal-property-system-reflection)
    * [UFUNCTION Examples](https://www.tomlooman.com/unreal-engine-ufunction-specifiers/)
    * [All Property Specifiers](https://docs.unrealengine.com/5.2/en-US/unreal-engine-uproperty-specifiers/)
    * [All Function Specifiers](https://docs.unrealengine.com/5.2/en-US/function-specifiers/)

## License

**Game Assets:** Licensed for use with the Unreal Engine only. Without a custom license you cannot use to create sequels, remasters, or otherwise emulate the original game or use the original game’s trademarks, character names, or other IP to advertise or name your game. (Unreal Engine EULA applies) (Please note this applies to the Game Assets that refer to Epic's Paragon, you can still use the project code and content to build your own Unreal Engine game)