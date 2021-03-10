![image](https://user-images.githubusercontent.com/80429347/110706352-9f9d8700-81ef-11eb-85b0-f3528f033978.png)

# boids

Implementation of a flocking algorithm based on this paper: https://www.red3d.com/cwr/papers/1987/SIGGRAPH87.pdf

## Usage

```lua
local Flock = require(game:GetService("ReplicatedStorage"):WaitForChild("Flock"))

Flock.new(100) -- Number of "boids"
```

