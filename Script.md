-- TEST SCRIPT BY ZETOX
-- NOT EDIT MY TEXT
-- Instances:

local Cheat = Instance.new("ScreenGui")
local Teleport = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Title_Teleport = Instance.new("TextLabel")
local Open = Instance.new("TextButton")
local Functions = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Lobby = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Close = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")

--Properties:

Cheat.Name = "Cheat"
Cheat.Parent = game.Workspace
Cheat.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Teleport.Name = "Teleport"
Teleport.Parent = Cheat
Teleport.BackgroundColor3 = Color3.fromRGB(117, 117, 117)
Teleport.Position = UDim2.new(0.145772591, 0, 0.0324675329, 0)
Teleport.Size = UDim2.new(0, 162, 0, 38)

UICorner.Parent = Teleport

Title_Teleport.Name = "Title_Teleport"
Title_Teleport.Parent = Teleport
Title_Teleport.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_Teleport.BackgroundTransparency = 1.000
Title_Teleport.Position = UDim2.new(-0.117283948, 0, -0.157894731, 0)
Title_Teleport.Size = UDim2.new(0, 200, 0, 50)
Title_Teleport.Font = Enum.Font.GothamBold
Title_Teleport.Text = "Teleport"
Title_Teleport.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_Teleport.TextSize = 14.000

Open.Name = "Open"
Open.Parent = Teleport
Open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Open.BackgroundTransparency = 1.000
Open.Position = UDim2.new(0.802469134, 0, 0, 0)
Open.Size = UDim2.new(0, 32, 0, 38)
Open.Font = Enum.Font.GothamBold
Open.Text = "+"
Open.TextColor3 = Color3.fromRGB(255, 255, 255)
Open.TextSize = 18.000

Functions.Name = "Functions"
Functions.Parent = Teleport
Functions.BackgroundColor3 = Color3.fromRGB(109, 109, 109)
Functions.Position = UDim2.new(0, 0, 1.15789473, 0)
Functions.Size = UDim2.new(0, 162, 0, 362)
Functions.Visible = false

UICorner_2.Parent = Functions

Lobby.Name = "Lobby"
Lobby.Parent = Functions
Lobby.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
Lobby.Position = UDim2.new(0, 0, 0.0276243091, 0)
Lobby.Size = UDim2.new(0, 162, 0, 37)
Lobby.Font = Enum.Font.GothamBold
Lobby.Text = "Lobby"
Lobby.TextColor3 = Color3.fromRGB(255, 255, 255)
Lobby.TextSize = 18.000

UICorner_3.Parent = Lobby

Close.Name = "Close"
Close.Parent = Functions
Close.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
Close.Position = UDim2.new(0, 0, 0.897790074, 0)
Close.Size = UDim2.new(0, 162, 0, 37)
Close.Font = Enum.Font.GothamBold
Close.Text = "Close"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextSize = 18.000

UICorner_4.Parent = Close

-- Scripts:

local function ASXWK_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	script.Parent.MouseButton1Click:Connect(function(open)
		game.Players.LocalPlayer.PlayerGui.Cheat.Teleport.Functions.Visible = true
	end)
	
end
coroutine.wrap(ASXWK_fake_script)()
local function MBKT_fake_script() -- Lobby.LocalScript 
	local script = Instance.new('LocalScript', Lobby)

	
end
coroutine.wrap(MBKT_fake_script)()
local function YRVYN_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Click:Connect(function(open)
		game.Players.LocalPlayer.PlayerGui.Cheat.Teleport.Functions.Visible = false
	end)
	
	
end
coroutine.wrap(YRVYN_fake_script)()

