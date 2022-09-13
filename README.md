## how to use (lua example)

```local words = game:HttpGet("https://raw.githubusercontent.com/6ce/random-word-lua/main/random.lua")

local randomWord = words[math.random(1, #words)]
print(randomWord)```
