-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local mainlabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Gamehub = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Trollhub = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Fescripts = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local gameframe = Instance.new("Frame")
local v1 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local v2 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local v3 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local v4 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local v5 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local v6 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local trollhub = Instance.new("Frame")
local legacyv1 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local legacyv2 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local spyx = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local synapse = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local walkspeed = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local nuke = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local _1x = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local kick = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local scriptshub = Instance.new("Frame")
local petblock = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local ratpet = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local jetpack = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local HOME = Instance.new("Frame")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.Position = UDim2.new(0.302030444, 0, 0.309297919, 0)
main.Size = UDim2.new(0, 312, 0, 200)
main.Active = true
main.Draggable = true

UICorner.Parent = main

mainlabel.Name = "mainlabel"
mainlabel.Parent = main
mainlabel.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
mainlabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
mainlabel.Size = UDim2.new(0, 312, 0, 36)
mainlabel.Font = Enum.Font.SourceSansBold
mainlabel.Text = "Prozo Hub"
mainlabel.TextColor3 = Color3.fromRGB(0, 0, 0)
mainlabel.TextSize = 41.000
mainlabel.TextStrokeColor3 = Color3.fromRGB(170, 0, 0)

UICorner_2.Parent = mainlabel

Gamehub.Name = "Gamehub"
Gamehub.Parent = main
Gamehub.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Gamehub.Position = UDim2.new(0.060897436, 0, 0.239999995, 0)
Gamehub.Size = UDim2.new(0, 85, 0, 29)
Gamehub.Font = Enum.Font.SourceSansBold
Gamehub.Text = "Game Hubs"
Gamehub.TextColor3 = Color3.fromRGB(0, 0, 0)
Gamehub.TextSize = 14.000

UICorner_3.Parent = Gamehub

Trollhub.Name = "Trollhub"
Trollhub.Parent = main
Trollhub.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Trollhub.Position = UDim2.new(0.362179458, 0, 0.239999995, 0)
Trollhub.Size = UDim2.new(0, 85, 0, 29)
Trollhub.Font = Enum.Font.SourceSansBold
Trollhub.Text = "Troll Hubs"
Trollhub.TextColor3 = Color3.fromRGB(0, 0, 0)
Trollhub.TextSize = 14.000

UICorner_4.Parent = Trollhub

Fescripts.Name = "Fescripts"
Fescripts.Parent = main
Fescripts.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Fescripts.Position = UDim2.new(0.666666627, 0, 0.239999995, 0)
Fescripts.Size = UDim2.new(0, 85, 0, 29)
Fescripts.Font = Enum.Font.SourceSansBold
Fescripts.Text = "FE Scripts"
Fescripts.TextColor3 = Color3.fromRGB(0, 0, 0)
Fescripts.TextSize = 14.000

UICorner_5.Parent = Fescripts

gameframe.Name = "gameframe"
gameframe.Parent = main
gameframe.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
gameframe.BorderColor3 = Color3.fromRGB(255, 0, 0)
gameframe.Position = UDim2.new(0.060897436, 0, 0.435000002, 0)
gameframe.Size = UDim2.new(0, 274, 0, 100)
gameframe.Visible = false

v1.Name = "v1"
v1.Parent = gameframe
v1.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
v1.Position = UDim2.new(0.0291970801, 0, 0.0827713013, 0)
v1.Size = UDim2.new(0, 44, 0, 25)
v1.Font = Enum.Font.SourceSansBold
v1.Text = "v1"
v1.TextColor3 = Color3.fromRGB(0, 0, 0)
v1.TextSize = 14.000
v1.Parent.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://pastebin.pl/view/raw/508e515c"), true))()
end)

UICorner_6.Parent = v1

v2.Name = "v2"
v2.Parent = gameframe
v2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
v2.Position = UDim2.new(0.19378306, 0, 0.0827713013, 0)
v2.Size = UDim2.new(0, 40, 0, 25)
v2.Font = Enum.Font.SourceSansBold
v2.Text = "v2"
v2.TextColor3 = Color3.fromRGB(0, 0, 0)
v2.TextSize = 14.000
v2.Parent.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/cKdbXX8F'))()
end)

UICorner_7.Parent = v2

v3.Name = "v3"
v3.Parent = gameframe
v3.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
v3.Position = UDim2.new(0.343065679, 0, 0.0827713013, 0)
v3.Size = UDim2.new(0, 41, 0, 25)
v3.Font = Enum.Font.SourceSansBold
v3.Text = "v3"
v3.TextColor3 = Color3.fromRGB(0, 0, 0)
v3.TextSize = 14.000
v3.Parent.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/r8WFBXKX"))()
end)

UICorner_8.Parent = v3

v4.Name = "v4"
v4.Parent = gameframe
v4.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
v4.Position = UDim2.new(0.493273437, 0, 0.0827713013, 0)
v4.Size = UDim2.new(0, 43, 0, 25)
v4.Font = Enum.Font.SourceSansBold
v4.Text = "v4"
v4.TextColor3 = Color3.fromRGB(0, 0, 0)
v4.TextSize = 14.000
v4.Parent.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/buCsmABy'),true))()
end)

UICorner_9.Parent = v4

v5.Name = "v5"
v5.Parent = gameframe
v5.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
v5.Position = UDim2.new(0.653284669, 0, 0.0869436637, 0)
v5.Size = UDim2.new(0, 43, 0, 25)
v5.Font = Enum.Font.SourceSansBold
v5.Text = "v5"
v5.TextColor3 = Color3.fromRGB(0, 0, 0)
v5.TextSize = 14.000
v5.Parent.MouseButton1Down:connect(function()
	loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\80\114\111\116\111\116\121\112\101\82\66\76\88\47\80\114\111\116\111\45\115\45\72\117\98\47\109\97\105\110\47\82\69\65\68\77\69\46\109\100\39\41\41\40\41\10")()
end)

UICorner_10.Parent = v5

v6.Name = "v6"
v6.Parent = gameframe
v6.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
v6.Position = UDim2.new(0.809659541, 0, 0.0827713013, 0)
v6.Size = UDim2.new(0, 42, 0, 25)
v6.Font = Enum.Font.SourceSansBold
v6.Text = "v6"
v6.TextColor3 = Color3.fromRGB(0, 0, 0)
v6.TextSize = 14.000
v6.Parent.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ProtoRBLX/Proto-sHubV.6/main/README.md", true))()
end)

UICorner_11.Parent = v6

trollhub.Name = "trollhub"
trollhub.Parent = main
trollhub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
trollhub.BorderColor3 = Color3.fromRGB(255, 0, 0)
trollhub.Position = UDim2.new(0.060897436, 0, 0.435000002, 0)
trollhub.Size = UDim2.new(0, 274, 0, 100)
trollhub.Visible = false


legacyv1.Name = "legacyv1"
legacyv1.Parent = trollhub
legacyv1.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
legacyv1.Position = UDim2.new(0.0352437943, 0, 0.0720660388, 0)
legacyv1.Size = UDim2.new(0, 84, 0, 25)
legacyv1.Font = Enum.Font.SourceSansBold
legacyv1.Text = "Legacy Troll v1"
legacyv1.TextColor3 = Color3.fromRGB(0, 0, 0)
legacyv1.TextSize = 14.000
legacyv1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/6RFYw209'))()
end)

UICorner_12.Parent = legacyv1

legacyv2.Name = "legacyv2"
legacyv2.Parent = trollhub
legacyv2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
legacyv2.Position = UDim2.new(0.0315941609, 0, 0.362066031, 0)
legacyv2.Size = UDim2.new(0, 84, 0, 25)
legacyv2.Font = Enum.Font.SourceSansBold
legacyv2.Text = "Legacy Troll v2"
legacyv2.TextColor3 = Color3.fromRGB(0, 0, 0)
legacyv2.TextSize = 14.000
legacyv2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/pysifXbF'))()
end)

UICorner_13.Parent = legacyv2

spyx.Name = "spyx"
spyx.Parent = trollhub
spyx.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
spyx.Position = UDim2.new(0.345462769, 0, 0.0720660388, 0)
spyx.Size = UDim2.new(0, 84, 0, 25)
spyx.Font = Enum.Font.SourceSansBold
spyx.Text = "SpyX"
spyx.TextColor3 = Color3.fromRGB(0, 0, 0)
spyx.TextSize = 14.000
spyx.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/Spy-X-SCRIPT-ROBLOX/main/README.md'),true))()
end)

UICorner_14.Parent = spyx

synapse.Name = "synapse"
synapse.Parent = trollhub
synapse.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
synapse.Position = UDim2.new(0.345462769, 0, 0.362066031, 0)
synapse.Size = UDim2.new(0, 84, 0, 25)
synapse.Font = Enum.Font.SourceSansBold
synapse.Text = "Fake Synapse X"
synapse.TextColor3 = Color3.fromRGB(0, 0, 0)
synapse.TextSize = 14.000
synapse.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/QmqSgQ3K"))()
end)

UICorner_15.Parent = synapse

walkspeed.Name = "walkspeed"
walkspeed.Parent = trollhub
walkspeed.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
walkspeed.Position = UDim2.new(0.0686678886, 0, 0.68964535, 0)
walkspeed.Size = UDim2.new(0, 104, 0, 25)
walkspeed.Font = Enum.Font.SourceSansBold
walkspeed.Text = "Change Walk Speed"
walkspeed.TextColor3 = Color3.fromRGB(0, 0, 0)
walkspeed.TextSize = 14.000
walkspeed.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/Speed-Script/main/README.md'),true))()
end)

UICorner_16.Parent = walkspeed

nuke.Name = "nuke"
nuke.Parent = trollhub
nuke.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
nuke.Position = UDim2.new(0.550985277, 0, 0.68923521, 0)
nuke.Size = UDim2.new(0, 104, 0, 25)
nuke.Font = Enum.Font.SourceSansBold
nuke.Text = "Nuke Server NON FE"
nuke.TextColor3 = Color3.fromRGB(0, 0, 0)
nuke.TextSize = 14.000
nuke.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/YAMyczqV'),true))()
end)

UICorner_17.Parent = nuke

_1x.Name = "1x"
_1x.Parent = trollhub
_1x.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
_1x.Position = UDim2.new(0.652032137, 0, 0.0720660388, 0)
_1x.Size = UDim2.new(0, 84, 0, 25)
_1x.Font = Enum.Font.SourceSansBold
_1x.Text = "1x1x1x1 GUI"
_1x.TextColor3 = Color3.fromRGB(0, 0, 0)
_1x.TextSize = 14.000
_1x.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/CYye6uA4'),true))()
end)

UICorner_18.Parent = _1x

kick.Name = "kick"
kick.Parent = trollhub
kick.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
kick.Position = UDim2.new(0.652032137, 0, 0.35206604, 0)
kick.Size = UDim2.new(0, 84, 0, 25)
kick.Font = Enum.Font.SourceSansBold
kick.Text = "Kick Troll"
kick.TextColor3 = Color3.fromRGB(0, 0, 0)
kick.TextSize = 14.000
kick.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/6RFYw209'))()
end)

UICorner_19.Parent = kick

scriptshub.Name = "scriptshub"
scriptshub.Parent = main
scriptshub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
scriptshub.BorderColor3 = Color3.fromRGB(255, 0, 0)
scriptshub.Position = UDim2.new(0.060897436, 0, 0.435000002, 0)
scriptshub.Size = UDim2.new(0, 274, 0, 100)
scriptshub.Visible = false

petblock.Name = "petblock"
petblock.Parent = scriptshub
petblock.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
petblock.Position = UDim2.new(0.0242949389, 0, 0.0720660388, 0)
petblock.Size = UDim2.new(0, 84, 0, 25)
petblock.Font = Enum.Font.SourceSansBold
petblock.Text = "FE PET BLOCK"
petblock.TextColor3 = Color3.fromRGB(0, 0, 0)
petblock.TextSize = 14.000
petblock.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/FE-Pet-Block-Script/main/README.md'),true))()
end)

UICorner_20.Parent = petblock

ratpet.Name = "ratpet"
ratpet.Parent = scriptshub
ratpet.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
ratpet.Position = UDim2.new(0.333211303, 0, 0.0805819705, 0)
ratpet.Size = UDim2.new(0, 89, 0, 25)
ratpet.Font = Enum.Font.SourceSansBold
ratpet.Text = "FE PET RAT"
ratpet.TextColor3 = Color3.fromRGB(0, 0, 0)
ratpet.TextSize = 14.000
ratpet.MouseButton1Down:connect(function()
	loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\80\114\111\116\111\82\66\76\88\47\70\69\45\80\69\84\45\86\50\47\109\97\105\110\47\82\69\65\68\77\69\46\109\100\39\41\44\116\114\117\101\41\41\40\41\10")()
end)

UICorner_21.Parent = ratpet

jetpack.Name = "jetpack"
jetpack.Parent = scriptshub
jetpack.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
jetpack.Position = UDim2.new(0.659331441, 0, 0.0720660388, 0)
jetpack.Size = UDim2.new(0, 84, 0, 25)
jetpack.Font = Enum.Font.SourceSansBold
jetpack.Text = "FE JETPACK"
jetpack.TextColor3 = Color3.fromRGB(0, 0, 0)
jetpack.TextSize = 14.000
jetpack.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/FE-JetPack-Script/main/README.md'),true))()
end)

UICorner_22.Parent = jetpack

TextLabel.Parent = scriptshub
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.Position = UDim2.new(0.0260803886, 0, 0.430935681, 0)
TextLabel.Size = UDim2.new(0, 257, 0, 13)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Philippine Fedora Hat For FE Pet Block"
TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextSize = 14.000

TextLabel_2.Parent = scriptshub
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.Position = UDim2.new(0.0260803886, 0, 0.560935676, 0)
TextLabel_2.Size = UDim2.new(0, 257, 0, 13)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "New Year Rat Accesory For FE Pet Rat"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.TextSize = 14.000

TextLabel_3.Parent = scriptshub
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.Position = UDim2.new(0.0278099775, 0, 0.690326214, 0)
TextLabel_3.Size = UDim2.new(0, 257, 0, 25)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Russia, Philippine Fedora, Blue Flame Samurai, Medieval Hood - Thats The Hat You Need For FE Jetpack"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 6.000
TextLabel_3.TextWrapped = true

HOME.Name = "HOME"
HOME.Parent = main
HOME.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
HOME.BorderColor3 = Color3.fromRGB(255, 0, 0)
HOME.Position = UDim2.new(0.060897436, 0, 0.435000002, 0)
HOME.Size = UDim2.new(0, 274, 0, 100)

TextLabel_4.Parent = HOME
TextLabel_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_4.Position = UDim2.new(0.0852869451, 0, 0.072600089, 0)
TextLabel_4.Size = UDim2.new(0, 225, 0, 64)
TextLabel_4.Font = Enum.Font.SourceSansBold
TextLabel_4.Text = "These Are The Scripts I Made!"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

TextLabel_5.Parent = HOME
TextLabel_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_5.Position = UDim2.new(0.0846721306, 0, 0.802915335, 0)
TextLabel_5.Size = UDim2.new(0, 225, 0, 14)
TextLabel_5.Font = Enum.Font.SourceSansBold
TextLabel_5.Text = "Sub 2 Prototype_RBLX"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

TextButton.Parent = main
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.858974338, 0, -0.0199999996, 0)
TextButton.Size = UDim2.new(0, 44, 0, 43)
TextButton.Font = Enum.Font.SourceSansBold
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

-- Scripts:

local function COATYB_fake_script() -- Gamehub.LocalScript 
	local script = Instance.new('LocalScript', Gamehub)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.gameframe.Visible = true
		script.Parent.Parent.HOME.Visible = false
		script.Parent.Parent.trollhub.Visible = false
		script.Parent.Parent.scriptshub.Visible = false
		wait(0.1)
	end)
end
coroutine.wrap(COATYB_fake_script)()
local function HWQTD_fake_script() -- Trollhub.LocalScript 
	local script = Instance.new('LocalScript', Trollhub)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.gameframe.Visible = false
		script.Parent.Parent.HOME.Visible = false
		script.Parent.Parent.trollhub.Visible = true
		script.Parent.Parent.scriptshub.Visible = false
		wait(0.1)
	end)
end
coroutine.wrap(HWQTD_fake_script)()
local function QNER_fake_script() -- Fescripts.LocalScript 
	local script = Instance.new('LocalScript', Fescripts)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.gameframe.Visible = false
		script.Parent.Parent.HOME.Visible = false
		script.Parent.Parent.trollhub.Visible = false
		script.Parent.Parent.scriptshub.Visible = true
		wait(0.1)
	end)
end
coroutine.wrap(QNER_fake_script)()
local function TZSNKAF_fake_script() -- TextButton.Script 
	local script = Instance.new('Script', TextButton)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible=false
	end)
end
coroutine.wrap(TZSNKAF_fake_script)()
