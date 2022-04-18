--Made By Empathy--

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Name = Instance.new("TextLabel")
local Credits = Instance.new("TextLabel")
local Morescriptscomingsoon = Instance.new("TextLabel")
local Script1 = Instance.new("TextButton")
local script2 = Instance.new("TextButton")
local script3 = Instance.new("TextButton")
local script4 = Instance.new("TextButton")
local Script5 = Instance.new("TextButton")
local script6 = Instance.new("TextButton")
local script7 = Instance.new("TextButton")
local script8 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Main.Position = UDim2.new(0.381212115, 0, 0.263940543, 0)
Main.Size = UDim2.new(0, 482, 0, 297)
Main.Active = true
Main.Draggable = true

Name.Name = "Name"
Name.Parent = Main
Name.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Name.Size = UDim2.new(0, 142, 0, 43)
Name.Font = Enum.Font.SourceSans
Name.Text = "Empathy's Script Hub"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextSize = 14.000
Main.Active = true

Credits.Name = "Credits"
Credits.Parent = Main
Credits.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Credits.Position = UDim2.new(0.292531133, 0, 0, 0)
Credits.Size = UDim2.new(0, 341, 0, 43)
Credits.Font = Enum.Font.SourceSans
Credits.Text = "---Made By Empathy---"
Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits.TextSize = 14.000
Main.Active = true

Morescriptscomingsoon.Name = "More scripts coming soon"
Morescriptscomingsoon.Parent = Main
Morescriptscomingsoon.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Morescriptscomingsoon.Position = UDim2.new(0, 0, 0.902356923, 0)
Morescriptscomingsoon.Size = UDim2.new(0, 482, 0, 29)
Morescriptscomingsoon.Font = Enum.Font.SourceSans
Morescriptscomingsoon.Text = "More Scripts Coming Soon"
Morescriptscomingsoon.TextColor3 = Color3.fromRGB(255, 255, 255)
Morescriptscomingsoon.TextSize = 14.000
Main.Active = true

Script1.Name = "Script 1"
Script1.Parent = Main
Script1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Script1.Position = UDim2.new(0.0456431545, 0, 0.245791227, 0)
Script1.Size = UDim2.new(0, 97, 0, 21)
Script1.Font = Enum.Font.SourceSans
Script1.Text = "DomainHub"
Script1.TextColor3 = Color3.fromRGB(255, 255, 255)
Script1.TextSize = 14.000
Main.Active = true
Script1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/DomainX/main/source',true))()
end)

script2.Name = "script 2"
script2.Parent = Main
script2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
script2.Position = UDim2.new(0.292531133, 0, 0.245791242, 0)
script2.Size = UDim2.new(0, 98, 0, 21)
script2.Font = Enum.Font.SourceSans
script2.Text = "OwlHub"
script2.TextColor3 = Color3.fromRGB(255, 255, 255)
script2.TextSize = 14.000
Main.Active = true
script2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)

script3.Name = "script 3"
script3.Parent = Main
script3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
script3.Position = UDim2.new(0.543568432, 0, 0.245791242, 0)
script3.Size = UDim2.new(0, 98, 0, 21)
script3.Font = Enum.Font.SourceSans
script3.Text = "Dex V4"
script3.TextColor3 = Color3.fromRGB(255, 255, 255)
script3.TextSize = 14.000
Main.Active = true
script3.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://controlc.com/548a5a33", true))()
end)

script4.Name = "script 4"
script4.Parent = Main
script4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
script4.Position = UDim2.new(0.773858905, 0, 0.245791242, 0)
script4.Size = UDim2.new(0, 90, 0, 21)
script4.Font = Enum.Font.SourceSans
script4.Text = "MoonUI"
script4.TextColor3 = Color3.fromRGB(255, 255, 255)
script4.TextSize = 14.000
Main.Active = true
script4.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)

Script5.Name = "Script 5"
Script5.Parent = Main
Script5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Script5.Position = UDim2.new(0.0456431545, 0, 0.457912445, 0)
Script5.Size = UDim2.new(0, 97, 0, 19)
Script5.Font = Enum.Font.SourceSans
Script5.Text = "SubHub (JailBreak)"
Script5.TextColor3 = Color3.fromRGB(255, 255, 255)
Script5.TextSize = 14.000
Main.Active = true
Script5.MouseButton1Down:connect(function()
	pcall(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Kw6m/Subbers-scripts/main/jailbreak", true))()
	end)
end)

script6.Name = "script 6"
script6.Parent = Main
script6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
script6.Position = UDim2.new(0.294605821, 0, 0.457912445, 0)
script6.Size = UDim2.new(0, 97, 0, 19)
script6.Font = Enum.Font.SourceSans
script6.Text = "TopKek V3"
script6.TextColor3 = Color3.fromRGB(255, 255, 255)
script6.TextSize = 14.000
Main.Active = true
script6.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://gitlab.com/legohackingroblox/helios/-/raw/main/topkekv3'))()
end)

script7.Name = "script 7"
script7.Parent = Main
script7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
script7.Position = UDim2.new(0.543568492, 0, 0.457912445, 0)
script7.Size = UDim2.new(0, 98, 0, 19)
script7.Font = Enum.Font.SourceSans
script7.Text = "ZyrexHub"
script7.TextColor3 = Color3.fromRGB(255, 255, 255)
script7.TextSize = 14.000
Main.Active = true
script7.MouseButton1Down:connect(function()
	_G.Toggle_GUI = Enum.KeyCode.RightControl

	loadstring(game:HttpGet(("https://raw.githubusercontent.com/NotZyrex/Zyrex-Hub/master/Main.lua"),true))()
end)

script8.Name = "script 8"
script8.Parent = Main
script8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
script8.Position = UDim2.new(0.773858905, 0, 0.457912445, 0)
script8.Size = UDim2.new(0, 90, 0, 19)
script8.Font = Enum.Font.SourceSans
script8.Text = "Faded (Da Hood)"
script8.TextColor3 = Color3.fromRGB(255, 255, 255)
script8.TextSize = 14.000
Main.Active = true
script8.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/nighter132/Faded/main/YesEpic", true))()
end)
