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

## Creating a Window

```lua
local Window = AlternateX:CreateWindow({
    Name = "Alternate X Hub",
    LoadingTitle = "Alternate X",
    LoadingSubtitle = "Initializing",
    Theme = "Dark",
    KeySystem = true
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
local MainTab = Window:CreateTab("Main")
local SettingsTab = Window:CreateTab("Settings")
```

---

## Adding Buttons

```lua
MainTab:AddButton({
    Name = "Example Button",
    Callback = function()
        print("Button clicked")
    end
})
```

---

## Adding Toggles

```lua
MainTab:AddToggle({
    Name = "Example Toggle",
    Default = false,
    Callback = function(Value)
        print(Value)
    end
})
```

---

## Adding Sliders

```lua
MainTab:AddSlider({
    Name = "Example Slider",
    Min = 0,
    Max = 100,
    Default = 50,
    Callback = function(Value)
        print(Value)
    end
})
```

---

## Key System

Alternate X Hub includes a built-in key system for access control.

```lua
KeySettings = {
    Title = "Alternate X Key System",
    Description = "Enter your key to continue",
    GetKeyURL = "https://discord.gg/yourserver"
}
```

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
