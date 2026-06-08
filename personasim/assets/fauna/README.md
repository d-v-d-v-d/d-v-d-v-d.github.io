# SimSafari Fauna Sprites

Animal sprites extracted from SimSafari, organized for Phaser 3.
Each animal's frames are individual PNGs covering multiple directions and actions.
All frames within a species share consistent dimensions.

## Animals

| Animal     | Frames | Dimensions (px) | Notes                                    |
|------------|--------|------------------|------------------------------------------|
| Lion       | 20     | 88 x 68          | Walk cycle, multiple directions          |
| Elephant   | 44     | 155 x 108         | Walk cycle, multiple directions/actions  |
| Baboon     | 46     | 59 x 46           | Walk cycle, multiple directions/actions  |
| Ostrich    | 32     | 77 x 71           | Walk cycle, multiple directions          |
| Crocodile  | 24     | 154 x 89          | Walk/swim cycle, multiple directions     |

## File Naming

Frames are named `{animal}_{NN}.png` (zero-padded, starting at 00), preserving
the original sort order from the source sprite sheets.

## Source

Sprites from [The Spriters Resource](https://www.spriters-resource.com/) -
PC / Computer - SimSafari - Fauna sheets. Research demo use only.
