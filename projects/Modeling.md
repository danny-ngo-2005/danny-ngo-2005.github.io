---
layout: project
type: project
image: img/vacay/cropped-image (3).png
title: "Modeling Maps"
date: 2018
published: true
labels:
  - Lua
  - Roblox Studio
  - Blender
  - Modeling
summary: "Modeling projects that I created in Roblox Studio"
---

<img class="img-fluid" src="https://i.imgur.com/pRc04iH.png">
<img class="img-fluid" src="https://i.imgur.com/QzfueXE.png">

Modeling was a personal project that I practice in order to utilize my models in the game. This project introduced me to coding as well developing my creativity in both gameplay and design.

Many of these model were developed in an environment known as Roblox Studio, a Lua application platform. As a challenge I made for myself, I wanted to include several obstacle courses that were unique to each other, with each of them having distinct themes.

These projects allowed me to learn the basic structures of coding with Lua, as well as becoming a foundation for learning about Blender as well. I also refined my creativity and artistic skills through each project that I designed.

A sample of a code in the map that lowers the player's health to 0:

```lua
function onTouch(part) 
	local humanoid = part.Parent:FindFirstChild("Humanoid") 
	if (humanoid ~= nil) then	-- if a humanoid exists, then
	humanoid.Health = 0	-- damage the humanoid
end 
end

script.Parent.Touched:connect(onTouch)
```
 
If you would like to view my projects, you can go to this link. However, you must sign up if you do not have an account: <a href="https://www.roblox.com/games/4794833247/dannyngo05s-Obby-Squad-Maps">Showcase/ObbySquad</a>
