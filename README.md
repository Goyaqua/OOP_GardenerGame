# Gameplay Overview
The app features a gardener tasked with arranging 7 garden objects within an 8x6 garden grid to meet specific pollen and color requirements for a target square. The game generates random goals, which can range from simple to complex combinations of pollen types and infused colors.

## Key Features
### Garden Objects:

* GardenPlants: Flowers, Trees, Bushes.
* LightSources: SmallLamps, LargeLamps, Spotlights.
* Statues: 7 predefined statues with unique IDs.

### Storage and Placement:

* GardenObjects are read from a storage_contents.csv file and stored in a shed.
* The gardener selects and carries 7 objects to the garden based on the goal requirements.

### Object Behavior:

* GardenPlants spread pollens with unique patterns.
* LightSources emit light with specific directions and ranges, infusing pollens with colors.
* Statues block both light and pollen spread.

### Searchable Interface:

* Objects can be searched by various attributes like type, ID, name, and area of effect.

### Game Mechanics:

* Pollens and light interact to create combined effects.
* Success is determined by the target square containing the required types of pollens infused with the required colors.
  
## Endgame
The puzzle concludes by revealing the garden grid's state. Success is announced if the target square meets the requirements; otherwise, the result is unsuccessful. Random factors ensure diverse outcomes during testing.
