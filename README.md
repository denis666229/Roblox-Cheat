local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Robojini/Tuturial_UI_Library/main/UI_Template_1"))()
local Window = Library.CreateLib("Tetrix Script", "RJTheme3")
local MainTab = Window:NewTab("Main")
local MainSection = MainTab:NewSection("Main Section")
 
MainSection:NewSlider("Speed Hack", "Adjust the walk speed", 500, 0, function(value)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value
end)
 
local CreditTab = Window:NewTab("Credit")
local CreditSection = CreditTab:NewSection("Credits")
CreditSection:NewLabel("Menu: Tetrix Script")
CreditSection:NewLabel("Creator: SenkoSan")
