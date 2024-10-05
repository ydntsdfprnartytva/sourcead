## Create Window
```
local yonathUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/ydntsdfprnartytva/sourcead/refs/heads/main/source"))()
local yonath = yonathUI:CreateWindow("Yonath.cc", "Football Fushion 2", true)
```
## Create Tab
```lua
local tab1 = yonath:CreatePage("Main")
```
## Create Section
```lua
local sec1 = tab1:CreateSection("Custom Mags")
```
## Create Button
```lua
sec1:CreateButton("Button Example", function ()
   print("Button Cliked!")
end)
```
## Create Toggle
```lua
sec1:CreateToggle("Toggle Example", {Toggled=false , Description = false}, function(Value)
   print(Value)
end)
```
## Create Slider
```lua
sec1:CreateSlider("Slider Example", {Min = 16, Max = 500, DefaultValue = 30}, function(Value)
   print(Value)
end)
```
## Create Dropdown
```lua
sec1:CreateDropdown("Dropdown ", {
   List = {"Value1", "Value2", "Value3", "Value4"},
   Default = "None"}, function(value)
       print(value)
end)
```
## Create TextBox
```lua
sec1:CreateTextbox("TextBox", false, function (vv)
   print(vv)
end)
```
## Create ColorPicker
```lua
sec1:CreateColorPicker("Color Picker", Color3.fromRGB(255, 255, 255), function ()
   print("fsf")
end)
```
