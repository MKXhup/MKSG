local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("MKXHUH", "DarkTheme")

local Tab = Window:NewTab("ฟาม")
local Section = Tab:NewSection("AFK")

Section:NewButton("กด", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/kkeyy-hash/roblox/main/SonicSpeedSimulator.lua'))()
end)



