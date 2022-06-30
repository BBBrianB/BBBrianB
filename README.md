-- Gui to Lua
-- Version: 3.2

-- Instances:

local Menu = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame_3 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Minimanize = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local Frame2 = Instance.new("Frame")
local Players = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local TextButton = Instance.new("TextButton")
local Hacks = Instance.new("Frame")
local UIGradient_2 = Instance.new("UIGradient")
local TextButton_2 = Instance.new("TextButton")
local PlayersMenu = Instance.new("Frame")
local ScrollingFrame = Instance.new("ScrollingFrame")
local UIListLayout = Instance.new("UIListLayout")
local Back = Instance.new("TextButton")
local CloseMenu = Instance.new("Frame")
local Frame_4 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local Yes = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local No = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local HacksMenu = Instance.new("Frame")
local GodModeButton = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Back_2 = Instance.new("TextButton")
local WallHack = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Template = Instance.new("Frame")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UICorner_8 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local TextButton_3 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local BillboardGui = Instance.new("BillboardGui")
local Template_2 = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local ImageLabel_2 = Instance.new("ImageLabel")
local TextButton_4 = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")

--Properties:

Menu.Name = "Menu"
Menu.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Menu.Enabled = false
Menu.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Menu.ResetOnSpawn = false

Frame.Parent = Menu
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Size = UDim2.new(1, 0, 1, 0)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Frame_2.Position = UDim2.new(0.380703032, 0, 0.189718485, 0)
Frame_2.Size = UDim2.new(0.238218531, 0, 0.619339049, 0)

UICorner.CornerRadius = UDim.new(0, 2)
UICorner.Parent = Frame_2

Frame_3.Parent = Frame_2
Frame_3.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Frame_3.Position = UDim2.new(0, 0, -0.000718158204, 0)
Frame_3.Size = UDim2.new(1.00000012, 0, 0.0920490474, 0)

UICorner_2.CornerRadius = UDim.new(0, 2)
UICorner_2.Parent = Frame_3

TextLabel.Parent = Frame_3
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel.Size = UDim2.new(0.767843425, 0, 1, 0)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "REALISTICS HOOD - MOD MENU"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Minimanize.Name = "Minimanize"
Minimanize.Parent = Frame_3
Minimanize.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Minimanize.BackgroundTransparency = 1.000
Minimanize.Position = UDim2.new(0.721580148, 0, 0.0644097328, 0)
Minimanize.Size = UDim2.new(0.123416677, 0, 0.841471851, 0)
Minimanize.Font = Enum.Font.SourceSans
Minimanize.Text = "-"
Minimanize.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimanize.TextScaled = true
Minimanize.TextSize = 14.000
Minimanize.TextWrapped = true

Close.Name = "Close"
Close.Parent = Frame_3
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.847050309, 0, 0.0644097254, 0)
Close.Size = UDim2.new(0.123416677, 0, 0.841471851, 0)
Close.Font = Enum.Font.SourceSans
Close.Text = "x"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

Frame2.Name = "Frame2"
Frame2.Parent = Frame_2
Frame2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame2.BackgroundTransparency = 1.000
Frame2.Position = UDim2.new(0, 0, 0.0913308784, 0)
Frame2.Size = UDim2.new(1, 0, 0.908669114, 0)

Players.Name = "Players"
Players.Parent = Frame2
Players.BackgroundColor3 = Color3.fromRGB(218, 218, 218)
Players.BorderSizePixel = 0
Players.Position = UDim2.new(0.0753536522, 0, 0.0173993781, 0)
Players.Size = UDim2.new(0.843910813, 0, 0.0800079554, 0)

UIGradient.Transparency = NumberSequence.new{NumberSequenceKeypoint.new(0.00, 1.00), NumberSequenceKeypoint.new(0.50, 0.00), NumberSequenceKeypoint.new(1.00, 1.00)}
UIGradient.Parent = Players

TextButton.Parent = Players
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Size = UDim2.new(1, 0, 1, 0)
TextButton.Font = Enum.Font.SourceSansBold
TextButton.Text = "Players"
TextButton.TextColor3 = Color3.fromRGB(218, 68, 68)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

Hacks.Name = "Hacks"
Hacks.Parent = Frame2
Hacks.BackgroundColor3 = Color3.fromRGB(218, 218, 218)
Hacks.BorderSizePixel = 0
Hacks.Position = UDim2.new(0.0753536522, 0, 0.128320411, 0)
Hacks.Size = UDim2.new(0.843910813, 0, 0.0800079554, 0)

UIGradient_2.Transparency = NumberSequence.new{NumberSequenceKeypoint.new(0.00, 1.00), NumberSequenceKeypoint.new(0.50, 0.00), NumberSequenceKeypoint.new(1.00, 1.00)}
UIGradient_2.Parent = Hacks

TextButton_2.Parent = Hacks
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.BackgroundTransparency = 1.000
TextButton_2.Size = UDim2.new(1, 0, 1, 0)
TextButton_2.Font = Enum.Font.SourceSansBold
TextButton_2.Text = "Hacks"
TextButton_2.TextColor3 = Color3.fromRGB(218, 68, 68)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

PlayersMenu.Name = "PlayersMenu"
PlayersMenu.Parent = Frame2
PlayersMenu.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
PlayersMenu.Size = UDim2.new(1, 0, 1, 0)
PlayersMenu.Visible = false

ScrollingFrame.Parent = PlayersMenu
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.Position = UDim2.new(0.185244396, 0, 0.0173993781, 0)
ScrollingFrame.Size = UDim2.new(0.814755619, 0, 0.941277087, 0)
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 0, 0)

UIListLayout.Parent = ScrollingFrame
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.Padding = UDim.new(0, 3)

Back.Name = "Back"
Back.Parent = PlayersMenu
Back.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Back.BackgroundTransparency = 1.000
Back.Position = UDim2.new(0.0251178835, 0, 0.0173993781, 0)
Back.Size = UDim2.new(0.0957560167, 0, 0.0669584274, 0)
Back.Font = Enum.Font.SourceSans
Back.Text = "<"
Back.TextColor3 = Color3.fromRGB(255, 255, 255)
Back.TextScaled = true
Back.TextSize = 14.000
Back.TextWrapped = true

CloseMenu.Name = "CloseMenu"
CloseMenu.Parent = Frame2
CloseMenu.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
CloseMenu.BorderColor3 = Color3.fromRGB(27, 42, 53)
CloseMenu.Size = UDim2.new(1, 0, 1, 0)
CloseMenu.Visible = false

Frame_4.Parent = CloseMenu
Frame_4.BackgroundColor3 = Color3.fromRGB(115, 115, 115)
Frame_4.Position = UDim2.new(0.188384131, 0, 0.284914792, 0)
Frame_4.Size = UDim2.new(0.617849827, 0, 0.360572904, 0)

UICorner_3.CornerRadius = UDim.new(0, 20)
UICorner_3.Parent = Frame_4

TextLabel_2.Parent = Frame_4
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(1, 0, 0.547611117, 0)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "Are you sure to close this mod menu ?"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Yes.Name = "Yes"
Yes.Parent = Frame_4
Yes.BackgroundColor3 = Color3.fromRGB(159, 230, 76)
Yes.Position = UDim2.new(0.0762256905, 0, 0.663503647, 0)
Yes.Size = UDim2.new(0.364785731, 0, 0.215859234, 0)
Yes.Font = Enum.Font.SourceSans
Yes.Text = "Yes"
Yes.TextColor3 = Color3.fromRGB(255, 255, 255)
Yes.TextScaled = true
Yes.TextSize = 14.000
Yes.TextWrapped = true

UICorner_4.CornerRadius = UDim.new(0, 20)
UICorner_4.Parent = Yes

No.Name = "No"
No.Parent = Frame_4
No.BackgroundColor3 = Color3.fromRGB(230, 83, 47)
No.Position = UDim2.new(0.569151819, 0, 0.663503647, 0)
No.Size = UDim2.new(0.364785731, 0, 0.215859234, 0)
No.Font = Enum.Font.SourceSans
No.Text = "No"
No.TextColor3 = Color3.fromRGB(255, 255, 255)
No.TextScaled = true
No.TextSize = 14.000
No.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 20)
UICorner_5.Parent = No

HacksMenu.Name = "HacksMenu"
HacksMenu.Parent = Frame2
HacksMenu.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
HacksMenu.Size = UDim2.new(1, 0, 1, 0)

GodModeButton.Name = "GodModeButton"
GodModeButton.Parent = HacksMenu
GodModeButton.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
GodModeButton.Position = UDim2.new(0.0627947152, 0, 0.0326238349, 0)
GodModeButton.Size = UDim2.new(0.875308216, 0, 0.0952324197, 0)
GodModeButton.Font = Enum.Font.SourceSans
GodModeButton.Text = "God Mode: nil"
GodModeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
GodModeButton.TextScaled = true
GodModeButton.TextSize = 14.000
GodModeButton.TextWrapped = true

UICorner_6.CornerRadius = UDim.new(0, 20)
UICorner_6.Parent = GodModeButton

Back_2.Name = "Back"
Back_2.Parent = HacksMenu
Back_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Back_2.BackgroundTransparency = 1.000
Back_2.Size = UDim2.new(0.0957560167, 0, 0.0669584274, 0)
Back_2.Font = Enum.Font.SourceSans
Back_2.Text = "<"
Back_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Back_2.TextScaled = true
Back_2.TextSize = 14.000
Back_2.TextWrapped = true

WallHack.Name = "WallHack"
WallHack.Parent = HacksMenu
WallHack.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
WallHack.Position = UDim2.new(0.0627947152, 0, 0.167469025, 0)
WallHack.Size = UDim2.new(0.875308216, 0, 0.0952324197, 0)
WallHack.Font = Enum.Font.SourceSans
WallHack.Text = "Wall Hack: nil"
WallHack.TextColor3 = Color3.fromRGB(255, 255, 255)
WallHack.TextScaled = true
WallHack.TextSize = 14.000
WallHack.TextWrapped = true

UICorner_7.CornerRadius = UDim.new(0, 20)
UICorner_7.Parent = WallHack

Template.Name = "Template"
Template.Parent = Menu
Template.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Template.Position = UDim2.new(0.100471541, 0, 0.0369736776, 0)
Template.Size = UDim2.new(0.788307786, 0, 0.115270838, 0)
Template.Visible = false

UIAspectRatioConstraint.Parent = Template
UIAspectRatioConstraint.AspectRatio = 6.000

UICorner_8.CornerRadius = UDim.new(0, 2)
UICorner_8.Parent = Template

ImageLabel.Parent = Template
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0, 0, 0.0293306131, 0)
ImageLabel.Size = UDim2.new(0.168965816, 0, 1, 0)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

TextButton_3.Parent = Template
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.BackgroundTransparency = 1.000
TextButton_3.Position = UDim2.new(0.166206807, 0, 0, 0)
TextButton_3.Size = UDim2.new(0.83099997, 0, 0.618701994, 0)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "DISPLAYNAME"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

TextLabel_3.Parent = Template
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.168965802, 0, 0.618702471, 0)
TextLabel_3.Size = UDim2.new(0.831034124, 0, 0.381298423, 0)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "@REALNAME"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

BillboardGui.Parent = Menu
BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
BillboardGui.Active = true
BillboardGui.AlwaysOnTop = true
BillboardGui.LightInfluence = 1.000
BillboardGui.Size = UDim2.new(4, 0, 1, 0)

Template_2.Name = "Template"
Template_2.Parent = BillboardGui
Template_2.BackgroundColor3 = Color3.fromRGB(206, 8, 8)
Template_2.Size = UDim2.new(1, 0, 1, 0)

UICorner_9.CornerRadius = UDim.new(0, 2)
UICorner_9.Parent = Template_2

ImageLabel_2.Parent = Template_2
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BackgroundTransparency = 1.000
ImageLabel_2.Position = UDim2.new(0, 0, 0.0293306131, 0)
ImageLabel_2.Size = UDim2.new(0.168965816, 0, 1, 0)
ImageLabel_2.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

TextButton_4.Parent = Template_2
TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.BackgroundTransparency = 1.000
TextButton_4.Position = UDim2.new(0.166206807, 0, 0, 0)
TextButton_4.Size = UDim2.new(0.83099997, 0, 0.618701994, 0)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "DISPLAYNAME"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

TextLabel_4.Parent = Template_2
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.168965802, 0, 0.618702471, 0)
TextLabel_4.Size = UDim2.new(0.831034124, 0, 0.381298423, 0)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "@REALNAME"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

-- Scripts:

local function NHSEMAD_fake_script() -- Frame_2.LocalScript 
	local script = Instance.new('LocalScript', Frame_2)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(NHSEMAD_fake_script)()
local function MTATJ_fake_script() -- Menu.LocalScript 
	local script = Instance.new('LocalScript', Menu)

local a = script.Parent local o = script.Parent.Frame local b = o.Frame local k = b.Frame local h = b.Frame2 local d = k.Minimanize local s = false local p = h.Players.TextButton local t = nil local l = h.PlayersMenu local j = script.Parent.Template local g = h.CloseMenu local q = h.Hacks.TextButton local c = h.HacksMenu function i() a:Destroy() end local e = math.random(1,5) if e == 1 then a.Name = "\66\114\105\97\110\32\77\101\110\117" elseif e == 2 then a.Name = "\77\101\110\117\32\67\114\101\97\97\116\101\100\32\98\121\32\66\114\105\97\110" elseif e == 3 then a.Name = "\77\101\110\117\32\66\114\105\97\110" elseif e == 4 then a.Name = "\82\101\97\108\105\115\116\105\99\32\72\111\111\100\32\77\101\110\117" elseif e == 5 then a.Name = "\66\114\105\97\110\32\82\101\97\108\105\115\116\105\99\32\72\111\111\100\32\77\101\110\117" end d.MouseButton1Click:Connect(function() if not s then s = true h.Visible = false b.Transparency = 1 b.UIStroke.Enabled = false elseif s then s = false h.Visible = true b.Transparency = 0 b.UIStroke.Enabled = true end end) function f() if t == "\80\108\97\121\101\114\115" then for i, delete in pairs(l.ScrollingFrame:GetChildren()) do wait() delete:Destroy() end for i, getplayer in pairs(game:GetService("\80\108\97\121\101\114\115"):GetPlayers()) do wait() l.Visible = true if not l.ScrollingFrame:FindFirstChild("\85\73\76\105\115\116\76\97\121\111\117\116") then local n = Instance.new("\85\73\76\105\115\116\76\97\121\111\117\116") n.Parent = l.ScrollingFrame n.Padding = UDim.new(0, 3) end local r = j:Clone() r.Visible = true r.Parent = l.ScrollingFrame l.ScrollingFrame.CanvasSize = UDim2.new(0, 0, 0, l.ScrollingFrame.UIListLayout.AbsoluteContentSize.Y) r.TextButton.Text = getplayer.DisplayName r.TextLabel.Text = "\64"..getplayer.Name r.ImageLabel.Image = game:GetService("\80\108\97\121\101\114\115"):GetUserThumbnailAsync(getplayer.UserId, Enum.ThumbnailType.HeadShot, Enum.ThumbnailSize.Size420x420) end end end p.MouseButton1Click:Connect(function() if not s then t = "\80\108\97\121\101\114\115" f() end end) l.Back.MouseButton1Click:Connect(function() if t == "\80\108\97\121\101\114\115" or l.Visible == true then t = nil l.Visible = false for i, delete in pairs(l.ScrollingFrame:GetChildren()) do wait() delete:Destroy() end end end) k.Close.MouseButton1Click:Connect(function() t = "\67\108\111\115\101\77\101\110\117" g.Visible = true end) g.Frame.Yes.MouseButton1Click:Connect(function() if t == "\67\108\111\115\101\77\101\110\117" or g.Visible == true then i() end end) g.Frame.No.MouseButton1Click:Connect(function() if t == "\67\108\111\115\101\77\101\110\117" or g.Visible == true then t = nil g.Visible = false end end) q.MouseButton1Click:Connect(function() t = "\72\97\99\107\115\77\101\110\117" c.Visible = true end) c.Back.MouseButton1Click:Connect(function() if t == "\72\97\99\107\115\77\101\110\117" or c.Visible == true then t = "" c.Visible = false end end) game:GetService("\80\108\97\121\101\114\115").PlayerAdded:Connect(f) game:GetService("\80\108\97\121\101\114\115").PlayerRemoving:Connect(f) local _ = false c.GodModeButton.MouseButton1Click:Connect(function() local i_ = game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Character.Humanoid local fi = i_.Parent i_.MaxHealth = 100000000 i_.Health = 100000 while true do if i_.Health < 100000000 then i_.Health = 100000000 c.GodModeButton.Text = "\71\111\100\32\77\111\100\101\58\32\82\101\102\105\108\108\32\72\101\97\108\116\104" wait() else wait() c.GodModeButton.Text = "\71\111\100\32\77\111\100\101\58\32\79\110" end wait() end end) 
end
coroutine.wrap(MTATJ_fake_script)()
