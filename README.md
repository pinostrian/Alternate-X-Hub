# Alternate X Hub

## Introduction

Alternate X Hub is a modern Roblox hub framework designed to provide a clean, responsive, and user-friendly interface.  
It focuses on simplicity, performance, and flexibility for script developers.

---

## Getting Started

Use the loadstring below to initialize Alternate X Hub.

```
local AX = loadstring(game:HttpGet("https://raw.githubusercontent.com/yourname/AlternateX/main/AlternateX.lua"))()
```
---

## Creating a Window & Key System

```lua
local Window = AX:CreateWindow({
    Name = "Alternate X",
    Loading = {
        Title = "Alternate X Premium",
        Subtitle = "Clean • Smooth • Powerful",
        Time = 2
    },
    KeySystem = {
        Enabled = true,
        Key = "AX-1234"
    },
    FloatingIcon = {
        Enabled = true,
        Image = "rbxassetid://124558441880674",
        Size = 52,
        Position = UDim2.fromScale(0.05, 0.5)
    }
})
```

### Window Options

| Option | Description |
|------|------------|
| Name | Title displayed on the window |
| LoadingTitle | Main loading screen text |
| LoadingSubtitle | Secondary loading text |
| Theme | UI color theme |
| KeySystem | Enables the key system |

---

## Creating Tabs

```lua
local Main = Window:CreateTab("Mai
```

---

## Adding Buttons

```lua
Main:AddButton("Test Button", function()
    print("Clicked")
end)
```

---

## Adding Toggles

```lua
Main:AddToggle("God Mode", false, function(v)
    print("Toggle:", v)
end)
```

---
---



---

## Features

- Clean and modern interface  
- Smooth animations  
- Built-in key system  
- Modular tab system  
- Easy-to-use API  
- Lightweight and optimized  

---

## Notes

- Designed for flexibility and customization  
- Intended for educational and development purposes  

---

## Credits

Developed by **pinostrian**
