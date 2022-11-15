# colour-combine

Tower defence game with coloured blocks

Press Space to start

Basic colours:

- White - Enemies
- Red - Moves forward and turns enemies into pink blocks
- Green - Lowers block cooldown
- Blue - Blocks enemies for a period of time
- Black - Erases blocks that you placed

Created colours:

- Pink - Duplicates blocks placed on it in its top and bottom

Combined colours:

- Magenta - Slowly moves forward and turns enemies into red blocks
- Yellow - Slowly moves forward and turns enemies into green blocks
- Cyan - Absorbs up to 3 enemies and lowers block cooldown

Detailed stats (g/s = grids per second)

- Screen refresh rate: 10 per second
- Cooldown
  - Cooldown rate: 50 per second (max 170)
  - Natural cooldown time: 3.4s
- White
  - Move speed: 0.83 g/s
  - Spawn rate: 0.4 => 0.5 => 0.67 => 1 => 1.43
- Red
  - Move speed: 3.3 g/s
- Green
  - Accelerate cooldown: +10 per second
- Blue
  - Deterioration speed: -33.3 per second (max 235)
  - Lifetime under deterioration: 7.05s
- Magenta/Yellow
  - Move speed: 0.67 g/s
- Pink
  - Deterioration speed: -2 per second (max 8)
  - Lifetime: 4s
