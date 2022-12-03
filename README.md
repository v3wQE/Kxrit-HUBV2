local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Kxrit HUBV2 :)", "Midnight")


local Tab = Window:NewTab("Avatars")
local Section = Tab:NewSection("Avatars")
Section:NewButton("Steal Other Avartras", "Very OP Enjoin:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/Steal-Avatars/main/README.md"))();
end)

Section:NewButton("Fake Limited", "Very OP Enjoin:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/Fake-limited/main/README.md"))();
end)
