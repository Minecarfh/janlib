
# Doc janlib




## Add Lib
```lua
loadstring(game:HttpGet('https://garfieldscripts.xyz/ui-libs/janlib.lua'))()
```

## AddTab

```lua
library:AddTab("Legit")
```

## AddColumn

```lua
App:AddColumn()
```

## AddSection

```lua
App2:AddSection("Aim Assist")
```
## AddDivider

```lua
App3:AddDivider("Main")
```

## AddToggle

```lua
App3:AddToggle{text = "Enabled", 
flag = "AimbotEnabled" ,
callback = function(Value)
    print(Value)
end}
```

## AddSlider

```lua
App3:AddSlider{text = "Aimbot FOV",
 flag = "AimbotFov",
  min = 0, 
  max = 750, 
  value = 105, 
  suffix = "°",
  callback = function()

  end}
```

## AddDropDown

```lua
App3:AddList({text = "Hit Box", 
flag = "AimbotHitbox", 
value = "Head", 
values = {"Head", "Torso"}
callback = function (Value)

end});
```


## AddDropDown

```lua
App3:AddList({text = "Hit Box", 
flag = "AimbotHitbox", 
value = "Head", 
values = {"Head", "Torso"}
callback = function (Value)

end});
```
## AddButton

```lua
App3::AddButton({text = "Discord", 
callback = function()

end});
```

## AddButton

```lua
App3::AddButton({text = "Discord", 
callback = function()

end});
```








