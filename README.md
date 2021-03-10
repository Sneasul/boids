# boids

Implementation of a flocking algorithm based on this paper: https://www.red3d.com/cwr/papers/1987/SIGGRAPH87.pdf

## Usage

```lua
local Flock = require(game:GetService("ReplicatedStorage"):WaitForChild("Flock"))

Flock.new(100) -- Number of "boids"
```

