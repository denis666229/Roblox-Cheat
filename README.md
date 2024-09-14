local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Robojini/Tuturial_UI_Library/main/UI_Template_1"))()

local Window = Library.CreateLib("Tetrix Script", "RJTheme3")

local MainTab = Window:NewTab("Main")

local MainSection = MainTab:NewSection("Main Section")

MainSection:NewButton("Example Button", "This is an example button", function()
    print("Main button clicked")
end)

local CreditTab = Window:NewTab("Credit")

local CreditSection = CreditTab:NewSection("Credits")

CreditSection:NewLabel("Menu: Tetrix Script")
CreditSection:NewLabel("Creator: SenkoSan")
