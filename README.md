Function Overview
The function processes a series of operations to manage obstacles and attempt block building on a grid. It returns a string indicating the success or failure of each building operation.
How It Works
Obstacle Management:
When operation === 1, an obstacle is added at position operation[1].
Obstacles are stored in a Set for efficient lookup.
Block Building:
When operation === 2, it attempts to build a block.
Parameters: x (starting position) and size (length of the block).
Checks if any obstacles exist in the range [x, x + size).
Result Generation:
Appends '1' to the result if block building is possible.
Appends '0' if an obstacle prevents building.
