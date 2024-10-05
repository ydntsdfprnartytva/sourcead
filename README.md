## Create Window
```lua
local yonath = loadstring(game:HttpGet("https://raw.githubusercontent.com/ydntsdfprnartytva/sourcead/refs/heads/main/sourcea"))()
```
## Create Tab
```lua
local tab1 = yonath:CreateTab("Catching")
```
## Create Section
```lua
local sec1 = tab1:CreateSection("Main")
```
## Create Button
```lua
sec1:CreateButton("Click Me!", function()
   print("Boo!")    
end)
```
## Create Label
```lua
sec1:CreateLabel("Namey", "Hello!")
```
## Create Button
```lua
MainSection:CreateButton("Click Me!", function()
   print("Boo!")    
end)
```
## Create Toggle
```lua
sec1:CreateToggle("Aimbot", function(boolean)
   print("Aimbot:", boolean)
end)
```
## Create Slider
```lua
sec1:CreateSlider("Field Of View", 0, 150, 50, false, function(value)
   print("Field of View: " .. value)
end)
```
## Create Dropdown
```lua
ConfigSection:CreateDropdown("Type", {"Mouse", "Character"}, 1, function(option)
   print("Type: " .. option)
end)
```
## Create ColorPicker
```lua
ConfigSection:CreateColorPicker("Field of View Color", Color3.fromRGB(255, 255, 255), function(color)
   print("Field Of View Color:", color)
end)
```
## Create Keybind
```lua
ConfigSection:CreateKeybind("Aimbot Bind", Enum.KeyCode.Unknown, false, true, function(boolean)
   print("Aimbot Active:", boolean)
end)
```
