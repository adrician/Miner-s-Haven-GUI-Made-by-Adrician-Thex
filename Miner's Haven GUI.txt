-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = {
	ScreenGui = Instance.new("ScreenGui"),
	MainFrame = Instance.new("Frame"),
	MainPage = Instance.new("Frame"),
	Menu = Instance.new("TextButton"),
	UICorner = Instance.new("UICorner"),
	Credits = Instance.new("TextButton"),
	UICorner_2 = Instance.new("UICorner"),
	UICorner_3 = Instance.new("UICorner"),
	Top = Instance.new("Frame"),
	Title = Instance.new("TextLabel"),
	UICorner_4 = Instance.new("UICorner"),
	UICorner_5 = Instance.new("UICorner"),
	Title_2 = Instance.new("TextLabel"),
	UICorner_6 = Instance.new("UICorner"),
	Credits_2 = Instance.new("Frame"),
	GUICredits = Instance.new("TextButton"),
	UICorner_7 = Instance.new("UICorner"),
	ScriptCredits = Instance.new("TextButton"),
	UICorner_8 = Instance.new("UICorner"),
	UICorner_9 = Instance.new("UICorner"),
	CBack = Instance.new("TextButton"),
	UICorner_10 = Instance.new("UICorner"),
	MenuPage = Instance.new("Frame"),
	Misc = Instance.new("TextButton"),
	UICorner_11 = Instance.new("UICorner"),
	CrateOpener = Instance.new("TextButton"),
	UICorner_12 = Instance.new("UICorner"),
	UICorner_13 = Instance.new("UICorner"),
	Locations = Instance.new("TextButton"),
	UICorner_14 = Instance.new("UICorner"),
	MBack = Instance.new("TextButton"),
	UICorner_15 = Instance.new("UICorner"),
	AutoFarm = Instance.new("TextButton"),
	UICorner_16 = Instance.new("UICorner"),
	MiscPage = Instance.new("Frame"),
	Noclip = Instance.new("TextButton"),
	UICorner_17 = Instance.new("UICorner"),
	AntiAFK = Instance.new("TextButton"),
	UICorner_18 = Instance.new("UICorner"),
	UICorner_19 = Instance.new("UICorner"),
	MSBack = Instance.new("TextButton"),
	UICorner_20 = Instance.new("UICorner"),
	pumpkins = Instance.new("TextButton"),
	UICorner_21 = Instance.new("UICorner"),
	UICorner_22 = Instance.new("UICorner"),
	locationsPage = Instance.new("Frame"),
	ship = Instance.new("TextButton"),
	UICorner_23 = Instance.new("UICorner"),
	baron = Instance.new("TextButton"),
	UICorner_24 = Instance.new("UICorner"),
	UICorner_25 = Instance.new("UICorner"),
	phantasm = Instance.new("TextButton"),
	UICorner_26 = Instance.new("UICorner"),
	daegel = Instance.new("TextButton"),
	UICorner_27 = Instance.new("UICorner"),
	LNextPage = Instance.new("TextButton"),
	UICorner_28 = Instance.new("UICorner"),
	LBack = Instance.new("TextButton"),
	UICorner_29 = Instance.new("UICorner"),
	locationsPage2 = Instance.new("Frame"),
	fargield = Instance.new("TextButton"),
	UICorner_30 = Instance.new("UICorner"),
	UICorner_31 = Instance.new("UICorner"),
	tower = Instance.new("TextButton"),
	UICorner_32 = Instance.new("UICorner"),
	MyBase = Instance.new("TextButton"),
	UICorner_33 = Instance.new("UICorner"),
	L2NextPage = Instance.new("TextButton"),
	UICorner_34 = Instance.new("UICorner"),
	L2Back = Instance.new("TextButton"),
	UICorner_35 = Instance.new("UICorner"),
	sporest = Instance.new("TextButton"),
	UICorner_36 = Instance.new("UICorner"),
	locationsPage3 = Instance.new("Frame"),
	factory2 = Instance.new("TextButton"),
	UICorner_37 = Instance.new("UICorner"),
	UICorner_38 = Instance.new("UICorner"),
	factory3 = Instance.new("TextButton"),
	UICorner_39 = Instance.new("UICorner"),
	factory1 = Instance.new("TextButton"),
	UICorner_40 = Instance.new("UICorner"),
	L3Back = Instance.new("TextButton"),
	UICorner_41 = Instance.new("UICorner"),
	factory5 = Instance.new("TextButton"),
	UICorner_42 = Instance.new("UICorner"),
	factory4 = Instance.new("TextButton"),
	UICorner_43 = Instance.new("UICorner"),
	factory6 = Instance.new("TextButton"),
	UICorner_44 = Instance.new("UICorner"),
	CrateOpenerPage = Instance.new("Frame"),
	UICorner_45 = Instance.new("UICorner"),
	InfernoCrate = Instance.new("TextButton"),
	UICorner_46 = Instance.new("UICorner"),
	ICToggle = Instance.new("TextButton"),
	ToggleBtnRound = Instance.new("UICorner"),
	ICToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound = Instance.new("UICorner"),
	ICToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound = Instance.new("UICorner"),
	UnrealCrate = Instance.new("TextButton"),
	UICorner_47 = Instance.new("UICorner"),
	UcToggle = Instance.new("TextButton"),
	ToggleBtnRound_2 = Instance.new("UICorner"),
	UcToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_2 = Instance.new("UICorner"),
	UcToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_2 = Instance.new("UICorner"),
	COBack = Instance.new("TextButton"),
	UICorner_48 = Instance.new("UICorner"),
	RegularCrate = Instance.new("TextButton"),
	UICorner_49 = Instance.new("UICorner"),
	RCToggle = Instance.new("TextButton"),
	ToggleBtnRound_3 = Instance.new("UICorner"),
	RCToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_3 = Instance.new("UICorner"),
	RCToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_3 = Instance.new("UICorner"),
	CONextPage = Instance.new("TextButton"),
	UICorner_50 = Instance.new("UICorner"),
	AutoFarmPage = Instance.new("Frame"),
	UICorner_51 = Instance.new("UICorner"),
	MineClicker = Instance.new("TextButton"),
	UICorner_52 = Instance.new("UICorner"),
	mToggle = Instance.new("TextButton"),
	ToggleBtnRound_4 = Instance.new("UICorner"),
	mToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_4 = Instance.new("UICorner"),
	mToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_4 = Instance.new("UICorner"),
	CandyCollector = Instance.new("TextButton"),
	UICorner_53 = Instance.new("UICorner"),
	cToggle = Instance.new("TextButton"),
	ToggleBtnRound_5 = Instance.new("UICorner"),
	cToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_5 = Instance.new("UICorner"),
	cToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_5 = Instance.new("UICorner"),
	AFBack = Instance.new("TextButton"),
	UICorner_54 = Instance.new("UICorner"),
	Promopt = Instance.new("TextButton"),
	UICorner_55 = Instance.new("UICorner"),
	pToggle = Instance.new("TextButton"),
	ToggleBtnRound_6 = Instance.new("UICorner"),
	pToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_6 = Instance.new("UICorner"),
	pToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_6 = Instance.new("UICorner"),
	AFNextPage = Instance.new("TextButton"),
	UICorner_56 = Instance.new("UICorner"),
	CrateOpenerPage2 = Instance.new("Frame"),
	UICorner_57 = Instance.new("UICorner"),
	MagnificentCrate = Instance.new("TextButton"),
	UICorner_58 = Instance.new("UICorner"),
	mCToggle = Instance.new("TextButton"),
	ToggleBtnRound_7 = Instance.new("UICorner"),
	mCToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_7 = Instance.new("UICorner"),
	mCToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_7 = Instance.new("UICorner"),
	LuxuryCrate = Instance.new("TextButton"),
	UICorner_59 = Instance.new("UICorner"),
	LCToggle = Instance.new("TextButton"),
	ToggleBtnRound_8 = Instance.new("UICorner"),
	LCToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_8 = Instance.new("UICorner"),
	LCToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_8 = Instance.new("UICorner"),
	COBack2 = Instance.new("TextButton"),
	UICorner_60 = Instance.new("UICorner"),
	PumpkinCrate = Instance.new("TextButton"),
	UICorner_61 = Instance.new("UICorner"),
	pCToggle = Instance.new("TextButton"),
	ToggleBtnRound_9 = Instance.new("UICorner"),
	pcToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_9 = Instance.new("UICorner"),
	pcToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_9 = Instance.new("UICorner"),
	AutoFarmPage3 = Instance.new("Frame"),
	UICorner_62 = Instance.new("UICorner"),
	AF3Back = Instance.new("TextButton"),
	UICorner_63 = Instance.new("UICorner"),
	AutoCrateTeleport = Instance.new("TextButton"),
	UICorner_64 = Instance.new("UICorner"),
	actToggle = Instance.new("TextButton"),
	ToggleBtnRound_10 = Instance.new("UICorner"),
	actToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_10 = Instance.new("UICorner"),
	actToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_10 = Instance.new("UICorner"),
	AutoLayout3 = Instance.new("TextButton"),
	UICorner_65 = Instance.new("UICorner"),
	al3Toggle = Instance.new("TextButton"),
	ToggleBtnRound_11 = Instance.new("UICorner"),
	al3ToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_11 = Instance.new("UICorner"),
	al3ToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_11 = Instance.new("UICorner"),
	AutoFarmPage2 = Instance.new("Frame"),
	UICorner_66 = Instance.new("UICorner"),
	AF2Back = Instance.new("TextButton"),
	UICorner_67 = Instance.new("UICorner"),
	AutoRebirth = Instance.new("TextButton"),
	UICorner_68 = Instance.new("UICorner"),
	arToggle = Instance.new("TextButton"),
	ToggleBtnRound_12 = Instance.new("UICorner"),
	arToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_12 = Instance.new("UICorner"),
	arToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_12 = Instance.new("UICorner"),
	AutoLayout = Instance.new("TextButton"),
	UICorner_69 = Instance.new("UICorner"),
	alToggle = Instance.new("TextButton"),
	ToggleBtnRound_13 = Instance.new("UICorner"),
	alToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_13 = Instance.new("UICorner"),
	alToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_13 = Instance.new("UICorner"),
	AutoLayout2 = Instance.new("TextButton"),
	UICorner_70 = Instance.new("UICorner"),
	al2Toggle = Instance.new("TextButton"),
	ToggleBtnRound_14 = Instance.new("UICorner"),
	al2ToggleIndicator = Instance.new("TextButton"),
	ToggleincdiatorRound_14 = Instance.new("UICorner"),
	al2ToggleStatus = Instance.new("TextButton"),
	ToggleStatusRound_14 = Instance.new("UICorner"),
	AF2NextPage = Instance.new("TextButton"),
	UICorner_71 = Instance.new("UICorner"),
}

--Properties:

ScreenGui.ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ScreenGui.MainFrame.Name = "MainFrame"
ScreenGui.MainFrame.Parent = ScreenGui.ScreenGui
ScreenGui.MainFrame.Active = true
ScreenGui.MainFrame.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.MainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MainFrame.Position = UDim2.new(0.393964797, 0, 0.24078624, 0)
ScreenGui.MainFrame.Size = UDim2.new(0, 345, 0, 278)

ScreenGui.MainPage.Name = "Main Page"
ScreenGui.MainPage.Parent = ScreenGui.MainFrame
ScreenGui.MainPage.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.MainPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MainPage.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.MainPage.Size = UDim2.new(0, 345, 0, 249)

ScreenGui.Menu.Name = "Menu"
ScreenGui.Menu.Parent = ScreenGui.MainPage
ScreenGui.Menu.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.Menu.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Menu.Position = UDim2.new(0.14782609, 0, 0.0883534104, 0)
ScreenGui.Menu.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.Menu.Font = Enum.Font.Gotham
ScreenGui.Menu.Text = "Menu"
ScreenGui.Menu.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.Menu.TextSize = 14.000

ScreenGui.UICorner.Parent = ScreenGui.Menu

ScreenGui.Credits.Name = "Credits"
ScreenGui.Credits.Parent = ScreenGui.MainPage
ScreenGui.Credits.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.Credits.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Credits.Position = UDim2.new(0.553623199, 0, 0.0883534104, 0)
ScreenGui.Credits.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.Credits.Font = Enum.Font.Gotham
ScreenGui.Credits.Text = "Credits"
ScreenGui.Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.Credits.TextSize = 14.000

ScreenGui.UICorner_2.Parent = ScreenGui.Credits

ScreenGui.UICorner_3.Parent = ScreenGui.MainPage

ScreenGui.Top.Name = "Top"
ScreenGui.Top.Parent = ScreenGui.MainFrame
ScreenGui.Top.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
ScreenGui.Top.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Top.Size = UDim2.new(0, 345, 0, 29)

ScreenGui.Title.Name = "Title"
ScreenGui.Title.Parent = ScreenGui.Top
ScreenGui.Title.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
ScreenGui.Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Title.Size = UDim2.new(0, 345, 0, 29)
ScreenGui.Title.Font = Enum.Font.Gotham
ScreenGui.Title.Text = "Beta Ver | Miner's Haven"
ScreenGui.Title.TextColor3 = Color3.fromRGB(245, 245, 245)
ScreenGui.Title.TextSize = 25.000

ScreenGui.UICorner_4.Parent = ScreenGui.Title

ScreenGui.UICorner_5.Parent = ScreenGui.Top

ScreenGui.Title_2.Name = "Title"
ScreenGui.Title_2.Parent = ScreenGui.Top
ScreenGui.Title_2.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
ScreenGui.Title_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Title_2.Position = UDim2.new(0.031884063, 0, 6.17241383, 0)
ScreenGui.Title_2.Size = UDim2.new(0, 322, 0, 64)
ScreenGui.Title_2.Font = Enum.Font.Gotham
ScreenGui.Title_2.Text = "This GUI is on testing right now if there is any button that doesn't work right now please let us know Adrician#0805 (We are aware of auto layout issues) Part 2 being worked on as soon as possible :)"
ScreenGui.Title_2.TextColor3 = Color3.fromRGB(245, 245, 245)
ScreenGui.Title_2.TextScaled = true
ScreenGui.Title_2.TextSize = 25.000
ScreenGui.Title_2.TextWrapped = true

ScreenGui.UICorner_6.Parent = ScreenGui.Title_2

ScreenGui.Credits_2.Name = "Credits"
ScreenGui.Credits_2.Parent = ScreenGui.MainFrame
ScreenGui.Credits_2.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.Credits_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Credits_2.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.Credits_2.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.Credits_2.Visible = false

ScreenGui.GUICredits.Name = "GUICredits"
ScreenGui.GUICredits.Parent = ScreenGui.Credits_2
ScreenGui.GUICredits.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
ScreenGui.GUICredits.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.GUICredits.Position = UDim2.new(0.197101444, 0, 0.0883534104, 0)
ScreenGui.GUICredits.Size = UDim2.new(0, 208, 0, 33)
ScreenGui.GUICredits.Font = Enum.Font.Gotham
ScreenGui.GUICredits.Text = "GUI Made by Adrician#0805"
ScreenGui.GUICredits.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.GUICredits.TextSize = 14.000

ScreenGui.UICorner_7.Parent = ScreenGui.GUICredits

ScreenGui.ScriptCredits.Name = "ScriptCredits"
ScreenGui.ScriptCredits.Parent = ScreenGui.Credits_2
ScreenGui.ScriptCredits.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
ScreenGui.ScriptCredits.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.ScriptCredits.Position = UDim2.new(0.197101444, 0, 0.301204801, 0)
ScreenGui.ScriptCredits.Size = UDim2.new(0, 208, 0, 33)
ScreenGui.ScriptCredits.Font = Enum.Font.Gotham
ScreenGui.ScriptCredits.Text = "Script made by Thex and Adri"
ScreenGui.ScriptCredits.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.ScriptCredits.TextSize = 14.000

ScreenGui.UICorner_8.Parent = ScreenGui.ScriptCredits

ScreenGui.UICorner_9.Parent = ScreenGui.Credits_2

ScreenGui.CBack.Name = "CBack"
ScreenGui.CBack.Parent = ScreenGui.Credits_2
ScreenGui.CBack.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.CBack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.CBack.Position = UDim2.new(0.368115932, 0, 0.742971897, 0)
ScreenGui.CBack.Size = UDim2.new(0, 90, 0, 36)
ScreenGui.CBack.Font = Enum.Font.Gotham
ScreenGui.CBack.Text = "Go Back"
ScreenGui.CBack.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.CBack.TextSize = 14.000

ScreenGui.UICorner_10.Parent = ScreenGui.CBack

ScreenGui.MenuPage.Name = "Menu Page"
ScreenGui.MenuPage.Parent = ScreenGui.MainFrame
ScreenGui.MenuPage.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.MenuPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MenuPage.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.MenuPage.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.MenuPage.Visible = false

ScreenGui.Misc.Name = "Misc"
ScreenGui.Misc.Parent = ScreenGui.MenuPage
ScreenGui.Misc.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.Misc.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Misc.Position = UDim2.new(0.573913097, 0, 0.34939757, 0)
ScreenGui.Misc.Size = UDim2.new(0, 115, 0, 45)
ScreenGui.Misc.Font = Enum.Font.Gotham
ScreenGui.Misc.Text = "Misc"
ScreenGui.Misc.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.Misc.TextSize = 15.000

ScreenGui.UICorner_11.Parent = ScreenGui.Misc

ScreenGui.CrateOpener.Name = "Crate Opener"
ScreenGui.CrateOpener.Parent = ScreenGui.MenuPage
ScreenGui.CrateOpener.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.CrateOpener.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.CrateOpener.Position = UDim2.new(0.573260844, 0, 0.0879999995, 0)
ScreenGui.CrateOpener.Size = UDim2.new(0, 115, 0, 45)
ScreenGui.CrateOpener.Font = Enum.Font.Gotham
ScreenGui.CrateOpener.Text = "Crate Opener"
ScreenGui.CrateOpener.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.CrateOpener.TextSize = 15.000
ScreenGui.CrateOpener.TextWrapped = true

ScreenGui.UICorner_12.Parent = ScreenGui.CrateOpener

ScreenGui.UICorner_13.Parent = ScreenGui.MenuPage

ScreenGui.Locations.Name = "Locations"
ScreenGui.Locations.Parent = ScreenGui.MenuPage
ScreenGui.Locations.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.Locations.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Locations.Position = UDim2.new(0.1123913, 0, 0.0879558325, 0)
ScreenGui.Locations.Size = UDim2.new(0, 115, 0, 45)
ScreenGui.Locations.Font = Enum.Font.Gotham
ScreenGui.Locations.Text = "Locations"
ScreenGui.Locations.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.Locations.TextSize = 15.000

ScreenGui.UICorner_14.Parent = ScreenGui.Locations

ScreenGui.MBack.Name = "MBack"
ScreenGui.MBack.Parent = ScreenGui.MenuPage
ScreenGui.MBack.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.MBack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MBack.Position = UDim2.new(0.368000001, 0, 0.742999971, 0)
ScreenGui.MBack.Size = UDim2.new(0, 90, 0, 36)
ScreenGui.MBack.Font = Enum.Font.Gotham
ScreenGui.MBack.Text = "Go Back"
ScreenGui.MBack.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.MBack.TextSize = 14.000

ScreenGui.UICorner_15.Parent = ScreenGui.MBack

ScreenGui.AutoFarm.Name = "Auto Farm"
ScreenGui.AutoFarm.Parent = ScreenGui.MenuPage
ScreenGui.AutoFarm.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AutoFarm.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoFarm.Position = UDim2.new(0.110144936, 0, 0.3493976, 0)
ScreenGui.AutoFarm.Size = UDim2.new(0, 115, 0, 45)
ScreenGui.AutoFarm.Font = Enum.Font.Gotham
ScreenGui.AutoFarm.Text = "Auto Farm"
ScreenGui.AutoFarm.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AutoFarm.TextSize = 15.000
ScreenGui.AutoFarm.TextWrapped = true

ScreenGui.UICorner_16.Parent = ScreenGui.AutoFarm

ScreenGui.MiscPage.Name = "Misc Page"
ScreenGui.MiscPage.Parent = ScreenGui.MainFrame
ScreenGui.MiscPage.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.MiscPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MiscPage.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.MiscPage.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.MiscPage.Visible = false

ScreenGui.Noclip.Name = "Noclip"
ScreenGui.Noclip.Parent = ScreenGui.MiscPage
ScreenGui.Noclip.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.Noclip.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Noclip.Position = UDim2.new(0.606000006, 0, 0.0879999995, 0)
ScreenGui.Noclip.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.Noclip.Font = Enum.Font.Gotham
ScreenGui.Noclip.Text = "Noclip"
ScreenGui.Noclip.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.Noclip.TextSize = 14.000

ScreenGui.UICorner_17.Parent = ScreenGui.Noclip

ScreenGui.AntiAFK.Name = "Anti AFK"
ScreenGui.AntiAFK.Parent = ScreenGui.MiscPage
ScreenGui.AntiAFK.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AntiAFK.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AntiAFK.Position = UDim2.new(0.0949999988, 0, 0.0879999995, 0)
ScreenGui.AntiAFK.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.AntiAFK.Font = Enum.Font.Gotham
ScreenGui.AntiAFK.Text = "Anti AFK"
ScreenGui.AntiAFK.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AntiAFK.TextSize = 14.000

ScreenGui.UICorner_18.Parent = ScreenGui.AntiAFK

ScreenGui.UICorner_19.Parent = ScreenGui.MiscPage

ScreenGui.MSBack.Name = "MSBack"
ScreenGui.MSBack.Parent = ScreenGui.MiscPage
ScreenGui.MSBack.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.MSBack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MSBack.Position = UDim2.new(0.368115932, 0, 0.742971897, 0)
ScreenGui.MSBack.Size = UDim2.new(0, 90, 0, 36)
ScreenGui.MSBack.Font = Enum.Font.Gotham
ScreenGui.MSBack.Text = "Go Back"
ScreenGui.MSBack.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.MSBack.TextSize = 14.000

ScreenGui.UICorner_20.Parent = ScreenGui.MSBack

ScreenGui.pumpkins.Name = "pumpkins"
ScreenGui.pumpkins.Parent = ScreenGui.MiscPage
ScreenGui.pumpkins.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.pumpkins.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.pumpkins.Position = UDim2.new(0.350072443, 0, 0.349044174, 0)
ScreenGui.pumpkins.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.pumpkins.Font = Enum.Font.Gotham
ScreenGui.pumpkins.Text = "Break all Pumpkins"
ScreenGui.pumpkins.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.pumpkins.TextScaled = true
ScreenGui.pumpkins.TextSize = 14.000
ScreenGui.pumpkins.TextWrapped = true

ScreenGui.UICorner_21.Parent = ScreenGui.pumpkins

ScreenGui.UICorner_22.Parent = ScreenGui.MainFrame

ScreenGui.locationsPage.Name = "locations Page"
ScreenGui.locationsPage.Parent = ScreenGui.MainFrame
ScreenGui.locationsPage.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.locationsPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.locationsPage.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.locationsPage.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.locationsPage.Visible = false

ScreenGui.ship.Name = "ship"
ScreenGui.ship.Parent = ScreenGui.locationsPage
ScreenGui.ship.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.ship.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.ship.Position = UDim2.new(0.626289845, 0, 0.0879999995, 0)
ScreenGui.ship.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.ship.Font = Enum.Font.Gotham
ScreenGui.ship.Text = "Pirate Ship"
ScreenGui.ship.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.ship.TextSize = 14.000

ScreenGui.UICorner_23.Parent = ScreenGui.ship

ScreenGui.baron.Name = "baron"
ScreenGui.baron.Parent = ScreenGui.locationsPage
ScreenGui.baron.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.baron.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.baron.Position = UDim2.new(0.0689130425, 0, 0.0879999995, 0)
ScreenGui.baron.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.baron.Font = Enum.Font.Gotham
ScreenGui.baron.Text = "Headless Baron"
ScreenGui.baron.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.baron.TextSize = 14.000
ScreenGui.baron.TextWrapped = true

ScreenGui.UICorner_24.Parent = ScreenGui.baron

ScreenGui.UICorner_25.Parent = ScreenGui.locationsPage

ScreenGui.phantasm.Name = "phantasm"
ScreenGui.phantasm.Parent = ScreenGui.locationsPage
ScreenGui.phantasm.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.phantasm.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.phantasm.Position = UDim2.new(0.0689130425, 0, 0.312759042, 0)
ScreenGui.phantasm.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.phantasm.Font = Enum.Font.Gotham
ScreenGui.phantasm.Text = "Phantasm"
ScreenGui.phantasm.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.phantasm.TextSize = 14.000
ScreenGui.phantasm.TextWrapped = true

ScreenGui.UICorner_26.Parent = ScreenGui.phantasm

ScreenGui.daegel.Name = "daegel"
ScreenGui.daegel.Parent = ScreenGui.locationsPage
ScreenGui.daegel.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.daegel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.daegel.Position = UDim2.new(0.625434756, 0, 0.313036144, 0)
ScreenGui.daegel.Size = UDim2.new(0, 103, 0, 45)
ScreenGui.daegel.Font = Enum.Font.Gotham
ScreenGui.daegel.Text = "Daegel"
ScreenGui.daegel.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.daegel.TextSize = 14.000
ScreenGui.daegel.TextWrapped = true

ScreenGui.UICorner_27.Parent = ScreenGui.daegel

ScreenGui.LNextPage.Name = "LNext Page"
ScreenGui.LNextPage.Parent = ScreenGui.locationsPage
ScreenGui.LNextPage.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.LNextPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.LNextPage.Position = UDim2.new(0.368115932, 0, 0.642570257, 0)
ScreenGui.LNextPage.Size = UDim2.new(0, 90, 0, 44)
ScreenGui.LNextPage.Font = Enum.Font.Gotham
ScreenGui.LNextPage.Text = "Next Page"
ScreenGui.LNextPage.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.LNextPage.TextSize = 14.000

ScreenGui.UICorner_28.Parent = ScreenGui.LNextPage

ScreenGui.LBack.Name = "LBack"
ScreenGui.LBack.Parent = ScreenGui.locationsPage
ScreenGui.LBack.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.LBack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.LBack.Position = UDim2.new(0.0666666701, 0, 0.819277108, 0)
ScreenGui.LBack.Size = UDim2.new(0, 77, 0, 36)
ScreenGui.LBack.Font = Enum.Font.Gotham
ScreenGui.LBack.Text = "Go Back"
ScreenGui.LBack.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.LBack.TextSize = 14.000

ScreenGui.UICorner_29.Parent = ScreenGui.LBack

ScreenGui.locationsPage2.Name = "locationsPage2"
ScreenGui.locationsPage2.Parent = ScreenGui.MainFrame
ScreenGui.locationsPage2.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.locationsPage2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.locationsPage2.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.locationsPage2.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.locationsPage2.Visible = false

ScreenGui.fargield.Name = "fargield"
ScreenGui.fargield.Parent = ScreenGui.locationsPage2
ScreenGui.fargield.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.fargield.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.fargield.Position = UDim2.new(0.626289845, 0, 0.0879999995, 0)
ScreenGui.fargield.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.fargield.Font = Enum.Font.Gotham
ScreenGui.fargield.Text = "Fargield"
ScreenGui.fargield.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.fargield.TextSize = 14.000

ScreenGui.UICorner_30.Parent = ScreenGui.fargield

ScreenGui.UICorner_31.Parent = ScreenGui.locationsPage2

ScreenGui.tower.Name = "tower"
ScreenGui.tower.Parent = ScreenGui.locationsPage2
ScreenGui.tower.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.tower.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.tower.Position = UDim2.new(0.0689131021, 0, 0.313036203, 0)
ScreenGui.tower.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.tower.Font = Enum.Font.Gotham
ScreenGui.tower.Text = "Wizard Tower"
ScreenGui.tower.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.tower.TextSize = 14.000
ScreenGui.tower.TextWrapped = true

ScreenGui.UICorner_32.Parent = ScreenGui.tower

ScreenGui.MyBase.Name = "MyBase"
ScreenGui.MyBase.Parent = ScreenGui.locationsPage2
ScreenGui.MyBase.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.MyBase.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MyBase.Position = UDim2.new(0.0668695867, 0, 0.100048266, 0)
ScreenGui.MyBase.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.MyBase.Font = Enum.Font.Gotham
ScreenGui.MyBase.Text = "My Base"
ScreenGui.MyBase.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.MyBase.TextSize = 14.000
ScreenGui.MyBase.TextWrapped = true

ScreenGui.UICorner_33.Parent = ScreenGui.MyBase

ScreenGui.L2NextPage.Name = "L2NextPage"
ScreenGui.L2NextPage.Parent = ScreenGui.locationsPage2
ScreenGui.L2NextPage.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.L2NextPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.L2NextPage.Position = UDim2.new(0.368115932, 0, 0.654618442, 0)
ScreenGui.L2NextPage.Size = UDim2.new(0, 90, 0, 41)
ScreenGui.L2NextPage.Font = Enum.Font.Gotham
ScreenGui.L2NextPage.Text = "Next Page"
ScreenGui.L2NextPage.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.L2NextPage.TextSize = 14.000

ScreenGui.UICorner_34.Parent = ScreenGui.L2NextPage

ScreenGui.L2Back.Name = "L2Back"
ScreenGui.L2Back.Parent = ScreenGui.locationsPage2
ScreenGui.L2Back.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.L2Back.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.L2Back.Position = UDim2.new(0.0666666701, 0, 0.819277108, 0)
ScreenGui.L2Back.Size = UDim2.new(0, 71, 0, 36)
ScreenGui.L2Back.Font = Enum.Font.Gotham
ScreenGui.L2Back.Text = "Go Back"
ScreenGui.L2Back.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.L2Back.TextSize = 14.000

ScreenGui.UICorner_35.Parent = ScreenGui.L2Back

ScreenGui.sporest.Name = "sporest"
ScreenGui.sporest.Parent = ScreenGui.locationsPage2
ScreenGui.sporest.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.sporest.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.sporest.Position = UDim2.new(0.625999987, 0, 0.312999994, 0)
ScreenGui.sporest.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.sporest.Font = Enum.Font.Gotham
ScreenGui.sporest.Text = "Sporest"
ScreenGui.sporest.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.sporest.TextSize = 14.000

ScreenGui.UICorner_36.Parent = ScreenGui.sporest

ScreenGui.locationsPage3.Name = "locationsPage3"
ScreenGui.locationsPage3.Parent = ScreenGui.MainFrame
ScreenGui.locationsPage3.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.locationsPage3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.locationsPage3.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.locationsPage3.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.locationsPage3.Visible = false

ScreenGui.factory2.Name = "factory2"
ScreenGui.factory2.Parent = ScreenGui.locationsPage3
ScreenGui.factory2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.factory2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.factory2.Position = UDim2.new(0.0668695569, 0, 0.31289959, 0)
ScreenGui.factory2.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.factory2.Font = Enum.Font.Gotham
ScreenGui.factory2.Text = "Factory 2"
ScreenGui.factory2.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.factory2.TextSize = 14.000

ScreenGui.UICorner_37.Parent = ScreenGui.factory2

ScreenGui.UICorner_38.Parent = ScreenGui.locationsPage3

ScreenGui.factory3.Name = "factory3"
ScreenGui.factory3.Parent = ScreenGui.locationsPage3
ScreenGui.factory3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.factory3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.factory3.Position = UDim2.new(0.0660145581, 0, 0.525887549, 0)
ScreenGui.factory3.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.factory3.Font = Enum.Font.Gotham
ScreenGui.factory3.Text = "Factory 3"
ScreenGui.factory3.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.factory3.TextSize = 14.000
ScreenGui.factory3.TextWrapped = true

ScreenGui.UICorner_39.Parent = ScreenGui.factory3

ScreenGui.factory1.Name = "factory1"
ScreenGui.factory1.Parent = ScreenGui.locationsPage3
ScreenGui.factory1.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.factory1.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.factory1.Position = UDim2.new(0.0668695867, 0, 0.100048266, 0)
ScreenGui.factory1.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.factory1.Font = Enum.Font.Gotham
ScreenGui.factory1.Text = "Factory 1"
ScreenGui.factory1.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.factory1.TextSize = 14.000
ScreenGui.factory1.TextWrapped = true

ScreenGui.UICorner_40.Parent = ScreenGui.factory1

ScreenGui.L3Back.Name = "L3Back"
ScreenGui.L3Back.Parent = ScreenGui.locationsPage3
ScreenGui.L3Back.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.L3Back.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.L3Back.Position = UDim2.new(0.397101462, 0, 0.759036183, 0)
ScreenGui.L3Back.Size = UDim2.new(0, 71, 0, 40)
ScreenGui.L3Back.Font = Enum.Font.Gotham
ScreenGui.L3Back.Text = "Go Back"
ScreenGui.L3Back.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.L3Back.TextSize = 14.000

ScreenGui.UICorner_41.Parent = ScreenGui.L3Back

ScreenGui.factory5.Name = "factory5"
ScreenGui.factory5.Parent = ScreenGui.locationsPage3
ScreenGui.factory5.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.factory5.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.factory5.Position = UDim2.new(0.622623146, 0, 0.309132576, 0)
ScreenGui.factory5.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.factory5.Font = Enum.Font.Gotham
ScreenGui.factory5.Text = "Factory 5"
ScreenGui.factory5.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.factory5.TextSize = 14.000
ScreenGui.factory5.TextWrapped = true

ScreenGui.UICorner_42.Parent = ScreenGui.factory5

ScreenGui.factory4.Name = "factory4"
ScreenGui.factory4.Parent = ScreenGui.locationsPage3
ScreenGui.factory4.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.factory4.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.factory4.Position = UDim2.new(0.623101473, 0, 0.100148574, 0)
ScreenGui.factory4.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.factory4.Font = Enum.Font.Gotham
ScreenGui.factory4.Text = "Factory 4"
ScreenGui.factory4.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.factory4.TextSize = 14.000

ScreenGui.UICorner_43.Parent = ScreenGui.factory4

ScreenGui.factory6.Name = "factory6"
ScreenGui.factory6.Parent = ScreenGui.locationsPage3
ScreenGui.factory6.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.factory6.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.factory6.Position = UDim2.new(0.623101413, 0, 0.521983922, 0)
ScreenGui.factory6.Size = UDim2.new(0, 103, 0, 38)
ScreenGui.factory6.Font = Enum.Font.Gotham
ScreenGui.factory6.Text = "Factory 6"
ScreenGui.factory6.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.factory6.TextSize = 14.000

ScreenGui.UICorner_44.Parent = ScreenGui.factory6

ScreenGui.CrateOpenerPage.Name = "Crate Opener Page"
ScreenGui.CrateOpenerPage.Parent = ScreenGui.MainFrame
ScreenGui.CrateOpenerPage.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.CrateOpenerPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.CrateOpenerPage.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.CrateOpenerPage.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.CrateOpenerPage.Visible = false

ScreenGui.UICorner_45.Parent = ScreenGui.CrateOpenerPage

ScreenGui.InfernoCrate.Name = "Inferno Crate"
ScreenGui.InfernoCrate.Parent = ScreenGui.CrateOpenerPage
ScreenGui.InfernoCrate.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.InfernoCrate.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.InfernoCrate.Position = UDim2.new(0, 0, 0.570281148, 0)
ScreenGui.InfernoCrate.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.InfernoCrate.Font = Enum.Font.Gotham
ScreenGui.InfernoCrate.Text = "Inferno Crate Opener"
ScreenGui.InfernoCrate.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.InfernoCrate.TextSize = 14.000

ScreenGui.UICorner_46.Parent = ScreenGui.InfernoCrate

ScreenGui.ICToggle.Name = "ICToggle"
ScreenGui.ICToggle.Parent = ScreenGui.InfernoCrate
ScreenGui.ICToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.ICToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.ICToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.ICToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.ICToggle.Font = Enum.Font.Gotham
ScreenGui.ICToggle.Text = ""
ScreenGui.ICToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.ICToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound.Parent = ScreenGui.ICToggle

ScreenGui.ICToggleIndicator.Name = "ICToggleIndicator"
ScreenGui.ICToggleIndicator.Parent = ScreenGui.ICToggle
ScreenGui.ICToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.ICToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.ICToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.ICToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.ICToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.ICToggleIndicator.Text = ""
ScreenGui.ICToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.ICToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound.Parent = ScreenGui.ICToggleIndicator

ScreenGui.ICToggleStatus.Name = "ICToggleStatus"
ScreenGui.ICToggleStatus.Parent = ScreenGui.ICToggleIndicator
ScreenGui.ICToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.ICToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.ICToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0, 0)
ScreenGui.ICToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.ICToggleStatus.Font = Enum.Font.Gotham
ScreenGui.ICToggleStatus.Text = ""
ScreenGui.ICToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.ICToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound.Parent = ScreenGui.ICToggleStatus

ScreenGui.UnrealCrate.Name = "Unreal Crate"
ScreenGui.UnrealCrate.Parent = ScreenGui.CrateOpenerPage
ScreenGui.UnrealCrate.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.UnrealCrate.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.UnrealCrate.Position = UDim2.new(0, 0, 0.309236944, 0)
ScreenGui.UnrealCrate.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.UnrealCrate.Font = Enum.Font.Gotham
ScreenGui.UnrealCrate.Text = "Unreal Crate Opener"
ScreenGui.UnrealCrate.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.UnrealCrate.TextSize = 14.000

ScreenGui.UICorner_47.Parent = ScreenGui.UnrealCrate

ScreenGui.UcToggle.Name = "UcToggle"
ScreenGui.UcToggle.Parent = ScreenGui.UnrealCrate
ScreenGui.UcToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.UcToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.UcToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.UcToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.UcToggle.Font = Enum.Font.Gotham
ScreenGui.UcToggle.Text = ""
ScreenGui.UcToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.UcToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_2.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_2.Parent = ScreenGui.UcToggle

ScreenGui.UcToggleIndicator.Name = "UcToggleIndicator"
ScreenGui.UcToggleIndicator.Parent = ScreenGui.UcToggle
ScreenGui.UcToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.UcToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.UcToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.UcToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.UcToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.UcToggleIndicator.Text = ""
ScreenGui.UcToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.UcToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_2.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_2.Parent = ScreenGui.UcToggleIndicator

ScreenGui.UcToggleStatus.Name = "UcToggleStatus"
ScreenGui.UcToggleStatus.Parent = ScreenGui.UcToggleIndicator
ScreenGui.UcToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.UcToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.UcToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.UcToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.UcToggleStatus.Font = Enum.Font.Gotham
ScreenGui.UcToggleStatus.Text = ""
ScreenGui.UcToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.UcToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_2.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_2.Parent = ScreenGui.UcToggleStatus

ScreenGui.COBack.Name = "COBack"
ScreenGui.COBack.Parent = ScreenGui.CrateOpenerPage
ScreenGui.COBack.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.COBack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.COBack.Position = UDim2.new(0.0347826108, 0, 0.859437704, 0)
ScreenGui.COBack.Size = UDim2.new(0, 65, 0, 29)
ScreenGui.COBack.Font = Enum.Font.Gotham
ScreenGui.COBack.Text = "Go Back"
ScreenGui.COBack.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.COBack.TextSize = 14.000

ScreenGui.UICorner_48.Parent = ScreenGui.COBack

ScreenGui.RegularCrate.Name = "Regular Crate"
ScreenGui.RegularCrate.Parent = ScreenGui.CrateOpenerPage
ScreenGui.RegularCrate.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.RegularCrate.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.RegularCrate.Position = UDim2.new(0, 0, 0.0562248975, 0)
ScreenGui.RegularCrate.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.RegularCrate.Font = Enum.Font.Gotham
ScreenGui.RegularCrate.Text = "Regular Crate Opener"
ScreenGui.RegularCrate.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.RegularCrate.TextSize = 14.000

ScreenGui.UICorner_49.Parent = ScreenGui.RegularCrate

ScreenGui.RCToggle.Name = "RCToggle"
ScreenGui.RCToggle.Parent = ScreenGui.RegularCrate
ScreenGui.RCToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.RCToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.RCToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.RCToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.RCToggle.Font = Enum.Font.Gotham
ScreenGui.RCToggle.Text = ""
ScreenGui.RCToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.RCToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_3.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_3.Parent = ScreenGui.RCToggle

ScreenGui.RCToggleIndicator.Name = "RCToggleIndicator"
ScreenGui.RCToggleIndicator.Parent = ScreenGui.RCToggle
ScreenGui.RCToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.RCToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.RCToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.RCToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.RCToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.RCToggleIndicator.Text = ""
ScreenGui.RCToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.RCToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_3.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_3.Parent = ScreenGui.RCToggleIndicator

ScreenGui.RCToggleStatus.Name = "RCToggleStatus"
ScreenGui.RCToggleStatus.Parent = ScreenGui.RCToggleIndicator
ScreenGui.RCToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.RCToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.RCToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.RCToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.RCToggleStatus.Font = Enum.Font.Gotham
ScreenGui.RCToggleStatus.Text = ""
ScreenGui.RCToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.RCToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_3.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_3.Parent = ScreenGui.RCToggleStatus

ScreenGui.CONextPage.Name = "CONext Page"
ScreenGui.CONextPage.Parent = ScreenGui.CrateOpenerPage
ScreenGui.CONextPage.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.CONextPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.CONextPage.Position = UDim2.new(0.368115932, 0, 0.791164637, 0)
ScreenGui.CONextPage.Size = UDim2.new(0, 90, 0, 34)
ScreenGui.CONextPage.Font = Enum.Font.Gotham
ScreenGui.CONextPage.Text = "Next Page"
ScreenGui.CONextPage.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.CONextPage.TextSize = 14.000

ScreenGui.UICorner_50.Parent = ScreenGui.CONextPage

ScreenGui.AutoFarmPage.Name = "Auto Farm Page"
ScreenGui.AutoFarmPage.Parent = ScreenGui.MainFrame
ScreenGui.AutoFarmPage.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.AutoFarmPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoFarmPage.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.AutoFarmPage.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.AutoFarmPage.Visible = false

ScreenGui.UICorner_51.Parent = ScreenGui.AutoFarmPage

ScreenGui.MineClicker.Name = "MineClicker"
ScreenGui.MineClicker.Parent = ScreenGui.AutoFarmPage
ScreenGui.MineClicker.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.MineClicker.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MineClicker.Position = UDim2.new(0, 0, 0.570281148, 0)
ScreenGui.MineClicker.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.MineClicker.Font = Enum.Font.Gotham
ScreenGui.MineClicker.Text = "Mine Clicker"
ScreenGui.MineClicker.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.MineClicker.TextSize = 14.000

ScreenGui.UICorner_52.Parent = ScreenGui.MineClicker

ScreenGui.mToggle.Name = "mToggle"
ScreenGui.mToggle.Parent = ScreenGui.MineClicker
ScreenGui.mToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.mToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.mToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.mToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.mToggle.Font = Enum.Font.Gotham
ScreenGui.mToggle.Text = ""
ScreenGui.mToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.mToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_4.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_4.Parent = ScreenGui.mToggle

ScreenGui.mToggleIndicator.Name = "mToggleIndicator"
ScreenGui.mToggleIndicator.Parent = ScreenGui.mToggle
ScreenGui.mToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.mToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.mToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.mToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.mToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.mToggleIndicator.Text = ""
ScreenGui.mToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.mToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_4.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_4.Parent = ScreenGui.mToggleIndicator

ScreenGui.mToggleStatus.Name = "mToggleStatus"
ScreenGui.mToggleStatus.Parent = ScreenGui.mToggleIndicator
ScreenGui.mToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.mToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.mToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0, 0)
ScreenGui.mToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.mToggleStatus.Font = Enum.Font.Gotham
ScreenGui.mToggleStatus.Text = ""
ScreenGui.mToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.mToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_4.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_4.Parent = ScreenGui.mToggleStatus

ScreenGui.CandyCollector.Name = "Candy Collector"
ScreenGui.CandyCollector.Parent = ScreenGui.AutoFarmPage
ScreenGui.CandyCollector.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.CandyCollector.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.CandyCollector.Position = UDim2.new(0, 0, 0.309236944, 0)
ScreenGui.CandyCollector.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.CandyCollector.Font = Enum.Font.Gotham
ScreenGui.CandyCollector.Text = "Candy Collector"
ScreenGui.CandyCollector.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.CandyCollector.TextSize = 14.000

ScreenGui.UICorner_53.Parent = ScreenGui.CandyCollector

ScreenGui.cToggle.Name = "cToggle"
ScreenGui.cToggle.Parent = ScreenGui.CandyCollector
ScreenGui.cToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.cToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.cToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.cToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.cToggle.Font = Enum.Font.Gotham
ScreenGui.cToggle.Text = ""
ScreenGui.cToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.cToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_5.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_5.Parent = ScreenGui.cToggle

ScreenGui.cToggleIndicator.Name = "cToggleIndicator"
ScreenGui.cToggleIndicator.Parent = ScreenGui.cToggle
ScreenGui.cToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.cToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.cToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.cToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.cToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.cToggleIndicator.Text = ""
ScreenGui.cToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.cToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_5.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_5.Parent = ScreenGui.cToggleIndicator

ScreenGui.cToggleStatus.Name = "cToggleStatus"
ScreenGui.cToggleStatus.Parent = ScreenGui.cToggleIndicator
ScreenGui.cToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.cToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.cToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.cToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.cToggleStatus.Font = Enum.Font.Gotham
ScreenGui.cToggleStatus.Text = ""
ScreenGui.cToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.cToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_5.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_5.Parent = ScreenGui.cToggleStatus

ScreenGui.AFBack.Name = "AFBack"
ScreenGui.AFBack.Parent = ScreenGui.AutoFarmPage
ScreenGui.AFBack.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.AFBack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AFBack.Position = UDim2.new(0.0347826108, 0, 0.859437704, 0)
ScreenGui.AFBack.Size = UDim2.new(0, 65, 0, 29)
ScreenGui.AFBack.Font = Enum.Font.Gotham
ScreenGui.AFBack.Text = "Go Back"
ScreenGui.AFBack.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AFBack.TextSize = 14.000

ScreenGui.UICorner_54.Parent = ScreenGui.AFBack

ScreenGui.Promopt.Name = "Promopt"
ScreenGui.Promopt.Parent = ScreenGui.AutoFarmPage
ScreenGui.Promopt.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.Promopt.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.Promopt.Position = UDim2.new(0, 0, 0.0562248975, 0)
ScreenGui.Promopt.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.Promopt.Font = Enum.Font.Gotham
ScreenGui.Promopt.Text = "Promopt"
ScreenGui.Promopt.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.Promopt.TextSize = 14.000

ScreenGui.UICorner_55.Parent = ScreenGui.Promopt

ScreenGui.pToggle.Name = "pToggle"
ScreenGui.pToggle.Parent = ScreenGui.Promopt
ScreenGui.pToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.pToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.pToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.pToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.pToggle.Font = Enum.Font.Gotham
ScreenGui.pToggle.Text = ""
ScreenGui.pToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.pToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_6.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_6.Parent = ScreenGui.pToggle

ScreenGui.pToggleIndicator.Name = "pToggleIndicator"
ScreenGui.pToggleIndicator.Parent = ScreenGui.pToggle
ScreenGui.pToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.pToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.pToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.pToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.pToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.pToggleIndicator.Text = ""
ScreenGui.pToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.pToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_6.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_6.Parent = ScreenGui.pToggleIndicator

ScreenGui.pToggleStatus.Name = "pToggleStatus"
ScreenGui.pToggleStatus.Parent = ScreenGui.pToggleIndicator
ScreenGui.pToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.pToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.pToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.pToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.pToggleStatus.Font = Enum.Font.Gotham
ScreenGui.pToggleStatus.Text = ""
ScreenGui.pToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.pToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_6.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_6.Parent = ScreenGui.pToggleStatus

ScreenGui.AFNextPage.Name = "AFNext Page"
ScreenGui.AFNextPage.Parent = ScreenGui.AutoFarmPage
ScreenGui.AFNextPage.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.AFNextPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AFNextPage.Position = UDim2.new(0.368115932, 0, 0.791164637, 0)
ScreenGui.AFNextPage.Size = UDim2.new(0, 90, 0, 34)
ScreenGui.AFNextPage.Font = Enum.Font.Gotham
ScreenGui.AFNextPage.Text = "Next Page"
ScreenGui.AFNextPage.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AFNextPage.TextSize = 14.000

ScreenGui.UICorner_56.Parent = ScreenGui.AFNextPage

ScreenGui.CrateOpenerPage2.Name = "Crate Opener Page2"
ScreenGui.CrateOpenerPage2.Parent = ScreenGui.MainFrame
ScreenGui.CrateOpenerPage2.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.CrateOpenerPage2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.CrateOpenerPage2.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.CrateOpenerPage2.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.CrateOpenerPage2.Visible = false

ScreenGui.UICorner_57.Parent = ScreenGui.CrateOpenerPage2

ScreenGui.MagnificentCrate.Name = "Magnificent Crate"
ScreenGui.MagnificentCrate.Parent = ScreenGui.CrateOpenerPage2
ScreenGui.MagnificentCrate.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.MagnificentCrate.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.MagnificentCrate.Position = UDim2.new(0, 0, 0.570281148, 0)
ScreenGui.MagnificentCrate.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.MagnificentCrate.Font = Enum.Font.Gotham
ScreenGui.MagnificentCrate.Text = "Magnificent Crate Opener"
ScreenGui.MagnificentCrate.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.MagnificentCrate.TextSize = 14.000

ScreenGui.UICorner_58.Parent = ScreenGui.MagnificentCrate

ScreenGui.mCToggle.Name = "mCToggle"
ScreenGui.mCToggle.Parent = ScreenGui.MagnificentCrate
ScreenGui.mCToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.mCToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.mCToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.mCToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.mCToggle.Font = Enum.Font.Gotham
ScreenGui.mCToggle.Text = ""
ScreenGui.mCToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.mCToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_7.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_7.Parent = ScreenGui.mCToggle

ScreenGui.mCToggleIndicator.Name = "mCToggleIndicator"
ScreenGui.mCToggleIndicator.Parent = ScreenGui.mCToggle
ScreenGui.mCToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.mCToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.mCToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.mCToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.mCToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.mCToggleIndicator.Text = ""
ScreenGui.mCToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.mCToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_7.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_7.Parent = ScreenGui.mCToggleIndicator

ScreenGui.mCToggleStatus.Name = "mCToggleStatus"
ScreenGui.mCToggleStatus.Parent = ScreenGui.mCToggleIndicator
ScreenGui.mCToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.mCToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.mCToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0, 0)
ScreenGui.mCToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.mCToggleStatus.Font = Enum.Font.Gotham
ScreenGui.mCToggleStatus.Text = ""
ScreenGui.mCToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.mCToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_7.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_7.Parent = ScreenGui.mCToggleStatus

ScreenGui.LuxuryCrate.Name = "Luxury Crate"
ScreenGui.LuxuryCrate.Parent = ScreenGui.CrateOpenerPage2
ScreenGui.LuxuryCrate.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.LuxuryCrate.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.LuxuryCrate.Position = UDim2.new(0, 0, 0.309236944, 0)
ScreenGui.LuxuryCrate.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.LuxuryCrate.Font = Enum.Font.Gotham
ScreenGui.LuxuryCrate.Text = "Luxury Crate Opener"
ScreenGui.LuxuryCrate.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.LuxuryCrate.TextSize = 14.000

ScreenGui.UICorner_59.Parent = ScreenGui.LuxuryCrate

ScreenGui.LCToggle.Name = "LCToggle"
ScreenGui.LCToggle.Parent = ScreenGui.LuxuryCrate
ScreenGui.LCToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.LCToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.LCToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.LCToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.LCToggle.Font = Enum.Font.Gotham
ScreenGui.LCToggle.Text = ""
ScreenGui.LCToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.LCToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_8.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_8.Parent = ScreenGui.LCToggle

ScreenGui.LCToggleIndicator.Name = "LCToggleIndicator"
ScreenGui.LCToggleIndicator.Parent = ScreenGui.LCToggle
ScreenGui.LCToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.LCToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.LCToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.LCToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.LCToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.LCToggleIndicator.Text = ""
ScreenGui.LCToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.LCToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_8.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_8.Parent = ScreenGui.LCToggleIndicator

ScreenGui.LCToggleStatus.Name = "LCToggleStatus"
ScreenGui.LCToggleStatus.Parent = ScreenGui.LCToggleIndicator
ScreenGui.LCToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.LCToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.LCToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.LCToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.LCToggleStatus.Font = Enum.Font.Gotham
ScreenGui.LCToggleStatus.Text = ""
ScreenGui.LCToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.LCToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_8.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_8.Parent = ScreenGui.LCToggleStatus

ScreenGui.COBack2.Name = "COBack2"
ScreenGui.COBack2.Parent = ScreenGui.CrateOpenerPage2
ScreenGui.COBack2.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.COBack2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.COBack2.Position = UDim2.new(0.376811594, 0, 0.819277108, 0)
ScreenGui.COBack2.Size = UDim2.new(0, 86, 0, 29)
ScreenGui.COBack2.Font = Enum.Font.Gotham
ScreenGui.COBack2.Text = "Go Back"
ScreenGui.COBack2.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.COBack2.TextSize = 14.000

ScreenGui.UICorner_60.Parent = ScreenGui.COBack2

ScreenGui.PumpkinCrate.Name = "Pumpkin Crate"
ScreenGui.PumpkinCrate.Parent = ScreenGui.CrateOpenerPage2
ScreenGui.PumpkinCrate.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.PumpkinCrate.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.PumpkinCrate.Position = UDim2.new(0, 0, 0.0562248975, 0)
ScreenGui.PumpkinCrate.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.PumpkinCrate.Font = Enum.Font.Gotham
ScreenGui.PumpkinCrate.Text = "Pumpkin Crate Opener"
ScreenGui.PumpkinCrate.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.PumpkinCrate.TextSize = 14.000

ScreenGui.UICorner_61.Parent = ScreenGui.PumpkinCrate

ScreenGui.pCToggle.Name = "pCToggle"
ScreenGui.pCToggle.Parent = ScreenGui.PumpkinCrate
ScreenGui.pCToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.pCToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.pCToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.pCToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.pCToggle.Font = Enum.Font.Gotham
ScreenGui.pCToggle.Text = ""
ScreenGui.pCToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.pCToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_9.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_9.Parent = ScreenGui.pCToggle

ScreenGui.pcToggleIndicator.Name = "pcToggleIndicator"
ScreenGui.pcToggleIndicator.Parent = ScreenGui.pCToggle
ScreenGui.pcToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.pcToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.pcToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.pcToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.pcToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.pcToggleIndicator.Text = ""
ScreenGui.pcToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.pcToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_9.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_9.Parent = ScreenGui.pcToggleIndicator

ScreenGui.pcToggleStatus.Name = "pcToggleStatus"
ScreenGui.pcToggleStatus.Parent = ScreenGui.pcToggleIndicator
ScreenGui.pcToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.pcToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.pcToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.pcToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.pcToggleStatus.Font = Enum.Font.Gotham
ScreenGui.pcToggleStatus.Text = ""
ScreenGui.pcToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.pcToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_9.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_9.Parent = ScreenGui.pcToggleStatus

ScreenGui.AutoFarmPage3.Name = "Auto Farm Page3"
ScreenGui.AutoFarmPage3.Parent = ScreenGui.MainFrame
ScreenGui.AutoFarmPage3.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.AutoFarmPage3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoFarmPage3.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.AutoFarmPage3.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.AutoFarmPage3.Visible = false

ScreenGui.UICorner_62.Parent = ScreenGui.AutoFarmPage3

ScreenGui.AF3Back.Name = "AF3Back"
ScreenGui.AF3Back.Parent = ScreenGui.AutoFarmPage3
ScreenGui.AF3Back.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.AF3Back.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AF3Back.Position = UDim2.new(0.347826064, 0, 0.787148595, 0)
ScreenGui.AF3Back.Size = UDim2.new(0, 104, 0, 37)
ScreenGui.AF3Back.Font = Enum.Font.Gotham
ScreenGui.AF3Back.Text = "Go Back"
ScreenGui.AF3Back.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AF3Back.TextSize = 14.000

ScreenGui.UICorner_63.Parent = ScreenGui.AF3Back

ScreenGui.AutoCrateTeleport.Name = "Auto Crate Teleport"
ScreenGui.AutoCrateTeleport.Parent = ScreenGui.AutoFarmPage3
ScreenGui.AutoCrateTeleport.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AutoCrateTeleport.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoCrateTeleport.Position = UDim2.new(0, 0, 0.297188759, 0)
ScreenGui.AutoCrateTeleport.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.AutoCrateTeleport.Font = Enum.Font.Gotham
ScreenGui.AutoCrateTeleport.Text = "Auto Crate Teleport"
ScreenGui.AutoCrateTeleport.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AutoCrateTeleport.TextSize = 14.000

ScreenGui.UICorner_64.Parent = ScreenGui.AutoCrateTeleport

ScreenGui.actToggle.Name = "actToggle"
ScreenGui.actToggle.Parent = ScreenGui.AutoCrateTeleport
ScreenGui.actToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.actToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.actToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.actToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.actToggle.Font = Enum.Font.Gotham
ScreenGui.actToggle.Text = ""
ScreenGui.actToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.actToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_10.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_10.Parent = ScreenGui.actToggle

ScreenGui.actToggleIndicator.Name = "actToggleIndicator"
ScreenGui.actToggleIndicator.Parent = ScreenGui.actToggle
ScreenGui.actToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.actToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.actToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.actToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.actToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.actToggleIndicator.Text = ""
ScreenGui.actToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.actToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_10.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_10.Parent = ScreenGui.actToggleIndicator

ScreenGui.actToggleStatus.Name = "actToggleStatus"
ScreenGui.actToggleStatus.Parent = ScreenGui.actToggleIndicator
ScreenGui.actToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.actToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.actToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.actToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.actToggleStatus.Font = Enum.Font.Gotham
ScreenGui.actToggleStatus.Text = ""
ScreenGui.actToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.actToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_10.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_10.Parent = ScreenGui.actToggleStatus

ScreenGui.AutoLayout3.Name = "Auto Layout3"
ScreenGui.AutoLayout3.Parent = ScreenGui.AutoFarmPage3
ScreenGui.AutoLayout3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AutoLayout3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoLayout3.Position = UDim2.new(0, 0, 0.0682730824, 0)
ScreenGui.AutoLayout3.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.AutoLayout3.Font = Enum.Font.Gotham
ScreenGui.AutoLayout3.Text = "Auto Layout 3"
ScreenGui.AutoLayout3.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AutoLayout3.TextSize = 14.000

ScreenGui.UICorner_65.Parent = ScreenGui.AutoLayout3

ScreenGui.al3Toggle.Name = "al3Toggle"
ScreenGui.al3Toggle.Parent = ScreenGui.AutoLayout3
ScreenGui.al3Toggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.al3Toggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.al3Toggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.al3Toggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.al3Toggle.Font = Enum.Font.Gotham
ScreenGui.al3Toggle.Text = ""
ScreenGui.al3Toggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.al3Toggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_11.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_11.Parent = ScreenGui.al3Toggle

ScreenGui.al3ToggleIndicator.Name = "al3ToggleIndicator"
ScreenGui.al3ToggleIndicator.Parent = ScreenGui.al3Toggle
ScreenGui.al3ToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.al3ToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.al3ToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.al3ToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.al3ToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.al3ToggleIndicator.Text = ""
ScreenGui.al3ToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.al3ToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_11.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_11.Parent = ScreenGui.al3ToggleIndicator

ScreenGui.al3ToggleStatus.Name = "al3ToggleStatus"
ScreenGui.al3ToggleStatus.Parent = ScreenGui.al3ToggleIndicator
ScreenGui.al3ToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.al3ToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.al3ToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.al3ToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.al3ToggleStatus.Font = Enum.Font.Gotham
ScreenGui.al3ToggleStatus.Text = ""
ScreenGui.al3ToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.al3ToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_11.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_11.Parent = ScreenGui.al3ToggleStatus

ScreenGui.AutoFarmPage2.Name = "Auto Farm Page2"
ScreenGui.AutoFarmPage2.Parent = ScreenGui.MainFrame
ScreenGui.AutoFarmPage2.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
ScreenGui.AutoFarmPage2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoFarmPage2.Position = UDim2.new(0, 0, 0.104316548, 0)
ScreenGui.AutoFarmPage2.Size = UDim2.new(0, 345, 0, 249)
ScreenGui.AutoFarmPage2.Visible = false

ScreenGui.UICorner_66.Parent = ScreenGui.AutoFarmPage2

ScreenGui.AF2Back.Name = "AF2Back"
ScreenGui.AF2Back.Parent = ScreenGui.AutoFarmPage2
ScreenGui.AF2Back.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.AF2Back.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AF2Back.Position = UDim2.new(0.0463768132, 0, 0.855421662, 0)
ScreenGui.AF2Back.Size = UDim2.new(0, 86, 0, 29)
ScreenGui.AF2Back.Font = Enum.Font.Gotham
ScreenGui.AF2Back.Text = "Go Back"
ScreenGui.AF2Back.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AF2Back.TextSize = 14.000

ScreenGui.UICorner_67.Parent = ScreenGui.AF2Back

ScreenGui.AutoRebirth.Name = "Auto Rebirth"
ScreenGui.AutoRebirth.Parent = ScreenGui.AutoFarmPage2
ScreenGui.AutoRebirth.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AutoRebirth.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoRebirth.Position = UDim2.new(0, 0, 0.0562248975, 0)
ScreenGui.AutoRebirth.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.AutoRebirth.Font = Enum.Font.Gotham
ScreenGui.AutoRebirth.Text = "Auto Rebirth"
ScreenGui.AutoRebirth.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AutoRebirth.TextSize = 14.000

ScreenGui.UICorner_68.Parent = ScreenGui.AutoRebirth

ScreenGui.arToggle.Name = "arToggle"
ScreenGui.arToggle.Parent = ScreenGui.AutoRebirth
ScreenGui.arToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.arToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.arToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.arToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.arToggle.Font = Enum.Font.Gotham
ScreenGui.arToggle.Text = ""
ScreenGui.arToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.arToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_12.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_12.Parent = ScreenGui.arToggle

ScreenGui.arToggleIndicator.Name = "arToggleIndicator"
ScreenGui.arToggleIndicator.Parent = ScreenGui.arToggle
ScreenGui.arToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.arToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.arToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.arToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.arToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.arToggleIndicator.Text = ""
ScreenGui.arToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.arToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_12.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_12.Parent = ScreenGui.arToggleIndicator

ScreenGui.arToggleStatus.Name = "arToggleStatus"
ScreenGui.arToggleStatus.Parent = ScreenGui.arToggleIndicator
ScreenGui.arToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.arToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.arToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.arToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.arToggleStatus.Font = Enum.Font.Gotham
ScreenGui.arToggleStatus.Text = ""
ScreenGui.arToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.arToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_12.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_12.Parent = ScreenGui.arToggleStatus

ScreenGui.AutoLayout.Name = "Auto Layout"
ScreenGui.AutoLayout.Parent = ScreenGui.AutoFarmPage2
ScreenGui.AutoLayout.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AutoLayout.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoLayout.Position = UDim2.new(0, 0, 0.277108431, 0)
ScreenGui.AutoLayout.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.AutoLayout.Font = Enum.Font.Gotham
ScreenGui.AutoLayout.Text = "Auto Layout"
ScreenGui.AutoLayout.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AutoLayout.TextSize = 14.000

ScreenGui.UICorner_69.Parent = ScreenGui.AutoLayout

ScreenGui.alToggle.Name = "alToggle"
ScreenGui.alToggle.Parent = ScreenGui.AutoLayout
ScreenGui.alToggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.alToggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.alToggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.alToggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.alToggle.Font = Enum.Font.Gotham
ScreenGui.alToggle.Text = ""
ScreenGui.alToggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.alToggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_13.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_13.Parent = ScreenGui.alToggle

ScreenGui.alToggleIndicator.Name = "alToggleIndicator"
ScreenGui.alToggleIndicator.Parent = ScreenGui.alToggle
ScreenGui.alToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.alToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.alToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.alToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.alToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.alToggleIndicator.Text = ""
ScreenGui.alToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.alToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_13.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_13.Parent = ScreenGui.alToggleIndicator

ScreenGui.alToggleStatus.Name = "alToggleStatus"
ScreenGui.alToggleStatus.Parent = ScreenGui.alToggleIndicator
ScreenGui.alToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.alToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.alToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.alToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.alToggleStatus.Font = Enum.Font.Gotham
ScreenGui.alToggleStatus.Text = ""
ScreenGui.alToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.alToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_13.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_13.Parent = ScreenGui.alToggleStatus

ScreenGui.AutoLayout2.Name = "Auto Layout 2"
ScreenGui.AutoLayout2.Parent = ScreenGui.AutoFarmPage2
ScreenGui.AutoLayout2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ScreenGui.AutoLayout2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AutoLayout2.Position = UDim2.new(0, 0, 0.49799192, 0)
ScreenGui.AutoLayout2.Size = UDim2.new(0, 345, 0, 45)
ScreenGui.AutoLayout2.Font = Enum.Font.Gotham
ScreenGui.AutoLayout2.Text = "Auto Layout 2"
ScreenGui.AutoLayout2.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AutoLayout2.TextSize = 14.000

ScreenGui.UICorner_70.Parent = ScreenGui.AutoLayout2

ScreenGui.al2Toggle.Name = "al2Toggle"
ScreenGui.al2Toggle.Parent = ScreenGui.AutoLayout2
ScreenGui.al2Toggle.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.al2Toggle.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.al2Toggle.Position = UDim2.new(0, 294, 0, 12)
ScreenGui.al2Toggle.Size = UDim2.new(0, 41, 0, 20)
ScreenGui.al2Toggle.Font = Enum.Font.Gotham
ScreenGui.al2Toggle.Text = ""
ScreenGui.al2Toggle.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.al2Toggle.TextSize = 21.000

ScreenGui.ToggleBtnRound_14.Name = "ToggleBtnRound"
ScreenGui.ToggleBtnRound_14.Parent = ScreenGui.al2Toggle

ScreenGui.al2ToggleIndicator.Name = "al2ToggleIndicator"
ScreenGui.al2ToggleIndicator.Parent = ScreenGui.al2Toggle
ScreenGui.al2ToggleIndicator.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ScreenGui.al2ToggleIndicator.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.al2ToggleIndicator.Position = UDim2.new(0.00325170159, 0, -0.0386061668, 0)
ScreenGui.al2ToggleIndicator.Size = UDim2.new(0, 40, 0, 20)
ScreenGui.al2ToggleIndicator.Font = Enum.Font.Gotham
ScreenGui.al2ToggleIndicator.Text = ""
ScreenGui.al2ToggleIndicator.TextColor3 = Color3.fromRGB(159, 159, 159)
ScreenGui.al2ToggleIndicator.TextSize = 21.000

ScreenGui.ToggleincdiatorRound_14.Name = "ToggleincdiatorRound"
ScreenGui.ToggleincdiatorRound_14.Parent = ScreenGui.al2ToggleIndicator

ScreenGui.al2ToggleStatus.Name = "al2ToggleStatus"
ScreenGui.al2ToggleStatus.Parent = ScreenGui.al2ToggleIndicator
ScreenGui.al2ToggleStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.al2ToggleStatus.BorderColor3 = Color3.fromRGB(38, 38, 38)
ScreenGui.al2ToggleStatus.Position = UDim2.new(-2.98023224e-07, 0, 0.0500000007, 0)
ScreenGui.al2ToggleStatus.Size = UDim2.new(0, 25, 0, 20)
ScreenGui.al2ToggleStatus.Font = Enum.Font.Gotham
ScreenGui.al2ToggleStatus.Text = ""
ScreenGui.al2ToggleStatus.TextColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.al2ToggleStatus.TextSize = 21.000

ScreenGui.ToggleStatusRound_14.Name = "ToggleStatusRound"
ScreenGui.ToggleStatusRound_14.Parent = ScreenGui.al2ToggleStatus

ScreenGui.AF2NextPage.Name = "AF2Next Page"
ScreenGui.AF2NextPage.Parent = ScreenGui.AutoFarmPage2
ScreenGui.AF2NextPage.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScreenGui.AF2NextPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScreenGui.AF2NextPage.Position = UDim2.new(0.368115962, 0, 0.763052225, 0)
ScreenGui.AF2NextPage.Size = UDim2.new(0, 90, 0, 34)
ScreenGui.AF2NextPage.Font = Enum.Font.Gotham
ScreenGui.AF2NextPage.Text = "Next Page"
ScreenGui.AF2NextPage.TextColor3 = Color3.fromRGB(255, 255, 255)
ScreenGui.AF2NextPage.TextSize = 14.000

ScreenGui.UICorner_71.Parent = ScreenGui.AF2NextPage


local factorys = workspace.Tycoons:GetChildren()
for i =1, #factorys do
	if factorys[i].Owner.Value == game.Players.LocalPlayer.Name then
		myfac = factorys[i]
	end
end

-- Visibility
ScreenGui.CBack.MouseButton1Click:Connect(function()
	ScreenGui.Credits_2.Visible = false
	ScreenGui.MainPage.Visible = true
end)

ScreenGui.MBack.MouseButton1Down:Connect(function()
	ScreenGui.MainPage.Visible = true
	ScreenGui.MenuPage.Visible = false
end)

ScreenGui.MSBack.MouseButton1Click:Connect(function()
	ScreenGui.MiscPage.Visible = false
	ScreenGui.MenuPage.Visible = true
end)

ScreenGui.LBack.MouseButton1Click:Connect(function()
	ScreenGui.locationsPage.Visible = false
	ScreenGui.MenuPage.Visible = true
end)


ScreenGui.L2Back.MouseButton1Click:Connect(function()
	ScreenGui.locationsPage2.Visible = false
	ScreenGui.locationsPage.Visible = true
end)

ScreenGui.L3Back.MouseButton1Click:Connect(function()
	ScreenGui.locationsPage3.Visible = false
	ScreenGui.locationsPage2.Visible = true
end)

ScreenGui.AF2Back.MouseButton1Click:Connect(function()
	ScreenGui.AutoFarmPage2.Visible = false
	ScreenGui.AutoFarmPage.Visible = true
end)


ScreenGui.AFBack.MouseButton1Click:Connect(function()
	ScreenGui.AutoFarmPage.Visible = false
	ScreenGui.MenuPage.Visible = true
end)

ScreenGui.COBack.MouseButton1Click:Connect(function()
	ScreenGui.CrateOpenerPage.Visible = false
	ScreenGui.MenuPage.Visible = true
end)

ScreenGui.COBack2.MouseButton1Click:Connect(function()
	ScreenGui.CrateOpenerPage2.Visible = false
	ScreenGui.CrateOpenerPage.Visible = true
end)

ScreenGui.CONextPage.MouseButton1Click:Connect(function()
	ScreenGui.CrateOpenerPage.Visible = false
	ScreenGui.CrateOpenerPage2.Visible = true
end)


ScreenGui.LNextPage.MouseButton1Click:Connect(function()
	ScreenGui.locationsPage.Visible = false
	ScreenGui.locationsPage2.Visible = true
end)

ScreenGui.L2NextPage.MouseButton1Click:Connect(function()
	ScreenGui.locationsPage2.Visible = false
	ScreenGui.locationsPage3.Visible = true
end)

ScreenGui.Menu.MouseButton1Click:Connect(function()
	ScreenGui.MenuPage.Visible = true
	ScreenGui.MainPage.Visible = false
end)

ScreenGui.Misc.MouseButton1Click:Connect(function()
	ScreenGui.MenuPage.Visible = false
	ScreenGui.MiscPage.Visible = true
end)

ScreenGui.AutoFarm.MouseButton1Click:Connect(function()
	ScreenGui.MiscPage.Visible = false
	ScreenGui.AutoFarmPage.Visible = true
end)

ScreenGui.AFNextPage.MouseButton1Click:Connect(function()
	ScreenGui.AutoFarmPage.Visible = false
	ScreenGui.AutoFarmPage2.Visible = true
end)

ScreenGui.Locations.MouseButton1Click:connect(function()
	ScreenGui.MenuPage.Visible = false
	ScreenGui.locationsPage.Visible = true
end)

ScreenGui.Credits.MouseButton1Click:Connect(function()
	ScreenGui.Credits_2.Visible = true
	ScreenGui.MainPage.Visible = false
end)

ScreenGui.CrateOpener.MouseButton1Click:Connect(function()
	ScreenGui.MenuPage.Visible = false
	ScreenGui.CrateOpenerPage.Visible = true
end)

ScreenGui.AF2NextPage.MouseButton1Click:Connect(function()
	ScreenGui.AutoFarmPage2.Visible = false
	ScreenGui.AutoFarmPage3.Visible = true
end)

ScreenGui.AF3Back.MouseButton1Click:Connect(function()
	ScreenGui.AutoFarmPage3.Visible = false
	ScreenGui.AutoFarmPage2.Visible = true
end)

-- Visiblity end

-- Toggles Auto Farm
_G.mStat = false
_G.cStat = false
_G.pStat = false
_G.arStat = false
_G.alStat = false
_G.al2Stat = false
_G.al3Stat = false
_G.actStat = false

ScreenGui.mToggleStatus.MouseButton1Click:connect(function()
	_G.mStat = not _G.mStat
	game:GetService("TweenService"):Create(ScreenGui.mToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.mStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while true do
		local mines = myfac:GetChildren()
		for i=1, #mines do
			if mines[i].Name == "Pumpkinite Mine" then
				mineName = "Pumpkinite Mine"
			elseif mines[i].Name == "Swintite Mine" then
				mineName = "Swintite Mine"
			elseif mines[i].Name == "Super Swintite Mine" then
				mineName = "Super Swintite Mine"
			end
		end
		local buttons = myfac[mineName].Model:GetChildren()
		for i=1, #buttons do
			if buttons[i].Name == "Button" then
				game.ReplicatedStorage.Click:FireServer(buttons[i])
				wait(0.05)
			end
		end
		if _G.mStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.cToggleStatus.MouseButton1Click:Connect(function()
	_G.cStat = not _G.cStat
	game:GetService("TweenService"):Create(ScreenGui.cToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.cStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while true do
		local text = string.sub(game.Players.LocalPlayer.PlayerGui.GUI.InputPrompt.InputPrompt.Title.Text, 1, 25)
		if text == "Would you like to collect" then
			for i,v in pairs(getconnections(game.Players.LocalPlayer.PlayerGui.GUI.InputPrompt.InputPrompt.Yes.MouseButton1Click)) do
				v:Fire()
			end
		end
		local items = myfac:GetChildren()
		for i=1, #items do
			if items[i].Name == "Candy Center" then
				collectorName = "Candy Center"
			elseif items[i].Name == "Candy Factory" then
				collectorName = "Candy Factory"
			end
		end
		local collect = myfac[collectorName].Model.Button
		game.ReplicatedStorage.Click:FireServer(collect)
		if _G.cStat == false then
			break
		end
		wait(10)
	end
end)

ScreenGui.pToggleStatus.MouseButton1Click:connect(function()
	_G.pStat = not _G.pStat
	print(_G.pStat)
	game:GetService("TweenService"):Create(ScreenGui.pToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.pStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while true do
		if game.Players.LocalPlayer.PlayerGui.GUI.InputPrompt.Absorb.Visible == true then
			local text = string.sub(game.Players.LocalPlayer.PlayerGui.GUI.InputPrompt.InputPrompt.Title.Text, 1, 25)
			if text == "Would you like to collect" then
				for i,v in pairs(getconnections(game.Players.LocalPlayer.PlayerGui.GUI.InputPrompt.InputPrompt.Yes.MouseButton1Click)) do
					v:Fire()
				end
			end
		end
		if _G.pStat == false then
			break
		end
		wait(.1)
	end
end)

ScreenGui.arToggleStatus.MouseButton1Click:Connect(function()
	_G.arStat = not _G.arStat
	game:GetService("TweenService"):Create(ScreenGui.arToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.arStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.arStat do
		wait()
		local args = {
			[1] = 26
		}
		local Event = game:GetService("ReplicatedStorage").Rebirth:InvokeServer(unpack(args))
		if _G.arStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.alToggleStatus.MouseButton1Click:Connect(function()
	_G.alStat = not _G.alStat
	game:GetService("TweenService"):Create(ScreenGui.alToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.alStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
end)

game.Players.LocalPlayer.leaderstats.Life:GetPropertyChangedSignal("Value"):Connect(function()
	if _G.alStat == true then
		wait(2)
		local args = {
			[1] = "Load",
			[2] = "Layout1"
		}
		game:GetService("ReplicatedStorage").Layouts:InvokeServer(unpack(args))
		wait(.05)
	end
end)

ScreenGui.al2ToggleStatus.MouseButton1Click:Connect(function()
	_G.al2Stat = not _G.al2Stat
	game:GetService("TweenService"):Create(ScreenGui.al2ToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.al2Stat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
end)

game.Players.LocalPlayer.leaderstats.Life.Changed:Connect(function(property)
	print("Life Changed")
	print(_G.al2Stat)
	if property == "Value" then
		if _G.al2Stat == true then

			local args = {
				[1] = "Load",
				[2] = "Layout2"
			}
			game:GetService("ReplicatedStorage").Layouts:InvokeServer(unpack(args))
			wait(.05)
		end
	end
end)

ScreenGui.al3ToggleStatus.MouseButton1Click:Connect(function()
	_G.al3Stat = not _G.al3Stat
	game:GetService("TweenService"):Create(ScreenGui.al3ToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.al3Stat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
end)
game.Players.LocalPlayer.leaderstats.Life:GetPropertyChangedSignal("Value"):Connect(function()
	if _G.al3Stat == true then
		local A_1 = "Load"
		local A_2 = "Layout3"
		local Event = game:GetService("ReplicatedStorage").Layouts
		Event:InvokeServer(A_1, A_2)
		wait()
		local A = "Check"
		local Event = game:GetService("ReplicatedStorage").Layouts
		Event:InvokeServer(A)
	end
end)
ScreenGui.actToggleStatus.MouseButton1Click:Connect(function()
	_G.actStat = not _G.actStat
	game:GetService("TweenService"):Create(ScreenGui.actToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.actStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.actStat do
		wait()
		for i,v in pairs(game.workspace:GetChildren()) do
			if v.Name == "Research" or v.Name == "Pumpkin" or v.Name == "CandyCorn" or v.Name == "MegaPumpkin" or v.Name == "Crystal" or v.Name == "Golden" or v.Name == "Lucky" or v.Name == "Shadow" or v.Name == "Diamond" then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame  = v.CFrame
				wait(0.5)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = myfac.Base.CFrame * CFrame.new(0,10,0)
			end
		end
		if _G.actStat == false then
			break
		end
		wait(.05)
	end
end)
-- Auto crate opener 

_G.UcStat = false
_G.ICStat = false
_G.RGStat = false
_G.pCStat = false
_G.mCStat = false
_G.lcStat = false

ScreenGui.RCToggleStatus.MouseButton1Click:Connect(function()
	_G.RGStat = not _G.RGStat
	game:GetService("TweenService"):Create(ScreenGui.RCToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.RGStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.RGStat do
		wait()
		local args = {
			[1] = "Regular"
		}
		game:GetService("ReplicatedStorage").MysteryBox:InvokeServer(unpack(args))
		if _G.RGStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.UcToggleStatus.MouseButton1Click:Connect(function()
	_G.UcStat = not _G.UcStat
	game:GetService("TweenService"):Create(ScreenGui.UcToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.UcStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.UcStat do
		wait()
		local args = {
			[1] = "Unreal"
		}
		game:GetService("ReplicatedStorage").MysteryBox:InvokeServer(unpack(args))
		if _G.UcStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.ICToggleStatus.MouseButton1Click:Connect(function()
	_G.IcStat = not _G.IcStat
	game:GetService("TweenService"):Create(ScreenGui.ICToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.IcStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.IcStat do
		wait()
		local args = {
			[1] = "Inferno"
		}
		game:GetService("ReplicatedStorage").MysteryBox:InvokeServer(unpack(args))
		if _G.IcStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.pcToggleStatus.MouseButton1Click:Connect(function()
	_G.pCStat = not _G.pCStat
	game:GetService("TweenService"):Create(ScreenGui.pcToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.pCStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.pCStat do
		wait()
		local args = {
			[1] = "Pumpkin"
		}
		game:GetService("ReplicatedStorage").MysteryBox:InvokeServer(unpack(args))
		if _G.pCStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.mCToggleStatus.MouseButton1Click:Connect(function()
	_G.mCStat = not _G.mCStat
	game:GetService("TweenService"):Create(ScreenGui.mCToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.mCStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.mCStat do
		wait()
		local args = {
			[1] = "Magnificent"
		}
		game:GetService("ReplicatedStorage").MysteryBox:InvokeServer(unpack(args))
		if _G.mCStat == false then
			break
		end
		wait(.05)
	end
end)

ScreenGui.LCToggleStatus.MouseButton1Click:Connect(function()
	_G.lcStat = not _G.lcStat
	game:GetService("TweenService"):Create(ScreenGui.LCToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.lcStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
	while _G.lcStat do
		wait()
		local args = {
			[1] = "Luxury"
		}
		game:GetService("ReplicatedStorage").MysteryBox:InvokeServer(unpack(args))
		if _G.lcStat == false then
			break
		end
		wait(.05)
	end
end)

game:GetService("TweenService"):Create(ScreenGui.pToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.pStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
game:GetService("TweenService"):Create(ScreenGui.mToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.mStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
game:GetService("TweenService"):Create(ScreenGui.cToggleStatus, TweenInfo.new(0.1, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = _G.cStat and UDim2.new(0.375, 0, 0, 0) or UDim2.new(0, 0, 0, 0)}):Play()
-- Toggles End

--Misc Beginning

ScreenGui.AntiAFK.MouseButton1Click:connect(function()
	game:GetService("Players").LocalPlayer.Idled:connect(function()
		game:GetService("VirtualUser"):CaptureController()
		game:GetService("VirtualUser"):ClickButton2(Vector3.new())
	end)
end)


ScreenGui.pumpkins.MouseButton1Click:connect(function()
	local currentPos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	firetouchinterest(game.Players.LocalPlayer.Character.LeftHand,game.workspace.Map.WeaponGivers.Axe.Giver,0)
	wait(2)
	game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack.Axe)
	wait(2)
	for i,v in pairs(game.workspace.Map:GetDescendants()) do
		if v:FindFirstChild("Mesh") then
			if v.Mesh:FindFirstChild("White") then
				print(v.Name)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Part.CFrame
				wait(1)
			end
		end
	end
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = currentPos
end)



--Misc End

-- Locations
ScreenGui.baron.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Market.Hitfox.CFrame
end)

ScreenGui.ship.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1095.16418, 53.1258812, 4.48487091)
end)

ScreenGui.phantasm.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-225,75,415)
end)

ScreenGui.sporest.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-808,40,-20)
end)

ScreenGui.daegel.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-141.799179, -112.402771, -117.161865)
end)

ScreenGui.MyBase.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = myfac.Base.CFrame * CFrame.new(0,10,0)
end)

ScreenGui.fargield.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Map.Fargield.Toe.CFrame
end)

ScreenGui.tower.MouseButton1Click:connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-138,227,228)
end)

ScreenGui.factory1.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Tycoons.Factory1.Base.CFrame * CFrame.new(0,10,0)
end)

ScreenGui.factory2.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Tycoons.Factory2.Base.CFrame * CFrame.new(0,10,0)
end)

ScreenGui.factory3.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Tycoons.Factory3.Base.CFrame * CFrame.new(0,10,0)
end)

ScreenGui.factory4.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Tycoons.Factory4.Base.CFrame * CFrame.new(0,10,0)
end)

ScreenGui.factory5.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Tycoons.Factory5.Base.CFrame * CFrame.new(0,10,0)
end)

ScreenGui.factory6.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.workspace.Tycoons.Factory6.Base.CFrame * CFrame.new(0,10,0)
end)

local mouse = game.Players.LocalPlayer:GetMouse()

mouse.KeyDown:Connect(function(button)
	if button:lower() == "g" or button:upper() == "G" then
		ScreenGui.ScreenGui.Enabled = not ScreenGui.ScreenGui.Enabled
	end
end)


ScreenGui.MainFrame.Draggable = true
ScreenGui.MainFrame.Selectable = true
ScreenGui.MainFrame.Active = true

game:GetService("StarterGui").ResetPlayerGuiOnSpawn = false