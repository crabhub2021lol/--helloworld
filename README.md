-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScriptGui = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")
local UICorner_2 = Instance.new("UICorner")
local Fly = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local KickYourself = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local JumpV2t = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local GodMode = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local ComingSoon = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local ComingSoon_2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local ComingSoon_3 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local ComingSoon_4 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local ComingSoon_5 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local ComingSoon_6 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local ComingSoon_7 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local ComingSoon_8 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local ComingSoon_9 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local Reset = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Speedm = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local Speed = Instance.new("TextLabel")
local Speedt = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local jumpm = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local Jump = Instance.new("TextLabel")
local Jumpt = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local jumpV2m = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local Jumpe = Instance.new("TextLabel")
local e = Instance.new("TextLabel")
local r = Instance.new("TextLabel")
local r_2 = Instance.new("TextLabel")
local r_3 = Instance.new("TextLabel")
local r_4 = Instance.new("TextLabel")
local r_5 = Instance.new("TextLabel")
local r_6 = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local OpenSpectate = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local SpecLabel = Instance.new("TextLabel")
local UICorner_23 = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Title = Instance.new("TextLabel")
local UIGridLayout = Instance.new("UIGridLayout")
local Toggle = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local TeleportFrame = Instance.new("Frame")
local Player = Instance.new("TextBox")
local Title_2 = Instance.new("TextLabel")
local Teleportn = Instance.new("TextButton")
local Error = Instance.new("TextLabel")

--Properties:

ScriptGui.Name = "ScriptGui"
ScriptGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScriptGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Open.Name = "Open"
Open.Parent = ScriptGui
Open.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Open.BorderColor3 = Color3.fromRGB(80, 80, 80)
Open.Position = UDim2.new(0.919698775, 0, 0.858816743, 0)
Open.Size = UDim2.new(0.0587045699, 0, 0.0330450647, 0)
Open.Font = Enum.Font.SourceSansSemibold
Open.Text = "Lab S"
Open.TextColor3 = Color3.fromRGB(213, 28, 28)
Open.TextScaled = true
Open.TextSize = 20.000
Open.TextWrapped = true

UICorner.Parent = Open

Main.Name = "Main"
Main.Parent = ScriptGui
Main.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Main.Position = UDim2.new(0.273611814, 0, 0.10226021, 0)
Main.Size = UDim2.new(0.424999982, 0, 0.845108151, 0)

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(217, 217, 217)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(7.24581923e-08, 0, -0.00283076847, 0)
TextLabel.Size = UDim2.new(0.999999762, 0, 0.159999996, 0)
TextLabel.Font = Enum.Font.Ubuntu
TextLabel.Text = "Lab Scriptz"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 50.000

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.49, Color3.fromRGB(49, 245, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 0, 0))}
UIGradient.Parent = TextLabel

UICorner_2.Parent = Main

Fly.Name = "Fly"
Fly.Parent = Main
Fly.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
Fly.Position = UDim2.new(0.0174674187, 0, 0.271493196, 0)
Fly.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
Fly.Font = Enum.Font.GothamBold
Fly.Text = "Fly"
Fly.TextColor3 = Color3.fromRGB(0, 0, 0)
Fly.TextSize = 14.000

UICorner_3.Parent = Fly

KickYourself.Name = "Kick Yourself"
KickYourself.Parent = Main
KickYourself.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
KickYourself.Position = UDim2.new(0.510971904, 0, 0.271493196, 0)
KickYourself.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
KickYourself.Font = Enum.Font.GothamBold
KickYourself.Text = "Kick Yourself"
KickYourself.TextColor3 = Color3.fromRGB(0, 0, 0)
KickYourself.TextSize = 14.000

UICorner_4.Parent = KickYourself

JumpV2t.Name = "JumpV2t"
JumpV2t.Parent = Main
JumpV2t.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
JumpV2t.Position = UDim2.new(0.267174959, 0, 0.406373829, 0)
JumpV2t.Size = UDim2.new(0.0784165561, 0, 0.0904977471, 0)
JumpV2t.Font = Enum.Font.GothamBold
JumpV2t.Text = "-"
JumpV2t.TextColor3 = Color3.fromRGB(0, 0, 0)
JumpV2t.TextSize = 14.000

UICorner_5.Parent = JumpV2t

GodMode.Name = "GodMode"
GodMode.Parent = Main
GodMode.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
GodMode.Position = UDim2.new(0.510971904, 0, 0.407239825, 0)
GodMode.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
GodMode.Font = Enum.Font.GothamBold
GodMode.Text = "GodMode"
GodMode.TextColor3 = Color3.fromRGB(0, 0, 0)
GodMode.TextSize = 14.000

UICorner_6.Parent = GodMode

ComingSoon.Name = "Coming Soon"
ComingSoon.Parent = Main
ComingSoon.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon.Position = UDim2.new(0.752049923, 0, 0.407239825, 0)
ComingSoon.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon.Font = Enum.Font.GothamBold
ComingSoon.Text = "Coming Soon"
ComingSoon.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon.TextSize = 14.000

UICorner_7.Parent = ComingSoon

ComingSoon_2.Name = "Coming Soon"
ComingSoon_2.Parent = Main
ComingSoon_2.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_2.Position = UDim2.new(0.265585989, 0, 0.542986453, 0)
ComingSoon_2.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_2.Font = Enum.Font.GothamBold
ComingSoon_2.Text = "Coming Soon"
ComingSoon_2.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_2.TextSize = 14.000

UICorner_8.Parent = ComingSoon_2

ComingSoon_3.Name = "Coming Soon"
ComingSoon_3.Parent = Main
ComingSoon_3.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_3.Position = UDim2.new(0.510971904, 0, 0.542986453, 0)
ComingSoon_3.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_3.Font = Enum.Font.GothamBold
ComingSoon_3.Text = "Coming Soon"
ComingSoon_3.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_3.TextSize = 14.000

UICorner_9.Parent = ComingSoon_3

ComingSoon_4.Name = "Coming Soon"
ComingSoon_4.Parent = Main
ComingSoon_4.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_4.Position = UDim2.new(0.7537117, 0, 0.542986453, 0)
ComingSoon_4.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_4.Font = Enum.Font.GothamBold
ComingSoon_4.Text = "Coming Soon"
ComingSoon_4.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_4.TextSize = 14.000

UICorner_10.Parent = ComingSoon_4

ComingSoon_5.Name = "Coming Soon"
ComingSoon_5.Parent = Main
ComingSoon_5.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_5.Position = UDim2.new(0.510972142, 0, 0.681749642, 0)
ComingSoon_5.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_5.Font = Enum.Font.GothamBold
ComingSoon_5.Text = "Coming Soon"
ComingSoon_5.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_5.TextSize = 14.000

UICorner_11.Parent = ComingSoon_5

ComingSoon_6.Name = "Coming Soon"
ComingSoon_6.Parent = Main
ComingSoon_6.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_6.Position = UDim2.new(0.266680628, 0, 0.681749642, 0)
ComingSoon_6.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_6.Font = Enum.Font.GothamBold
ComingSoon_6.Text = "Coming Soon"
ComingSoon_6.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_6.TextSize = 14.000

UICorner_12.Parent = ComingSoon_6

ComingSoon_7.Name = "Coming Soon"
ComingSoon_7.Parent = Main
ComingSoon_7.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_7.Position = UDim2.new(0.75481391, 0, 0.681749701, 0)
ComingSoon_7.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_7.Font = Enum.Font.GothamBold
ComingSoon_7.Text = "Coming Soon"
ComingSoon_7.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_7.TextSize = 14.000

UICorner_13.Parent = ComingSoon_7

ComingSoon_8.Name = "Coming Soon"
ComingSoon_8.Parent = Main
ComingSoon_8.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_8.Position = UDim2.new(0.0185855776, 0, 0.681749642, 0)
ComingSoon_8.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_8.Font = Enum.Font.GothamBold
ComingSoon_8.Text = "Coming Soon"
ComingSoon_8.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_8.TextSize = 14.000

UICorner_14.Parent = ComingSoon_8

ComingSoon_9.Name = "Coming Soon"
ComingSoon_9.Parent = Main
ComingSoon_9.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
ComingSoon_9.Position = UDim2.new(0.0174674243, 0, 0.542986453, 0)
ComingSoon_9.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
ComingSoon_9.Font = Enum.Font.GothamBold
ComingSoon_9.Text = "Coming Soon"
ComingSoon_9.TextColor3 = Color3.fromRGB(0, 0, 0)
ComingSoon_9.TextSize = 14.000

UICorner_15.Parent = ComingSoon_9

Reset.Name = "Reset"
Reset.Parent = Main
Reset.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
Reset.Position = UDim2.new(0.265585989, 0, 0.271493196, 0)
Reset.Size = UDim2.new(0.227998063, 0, 0.0904977471, 0)
Reset.Font = Enum.Font.GothamBold
Reset.Text = "Reset"
Reset.TextColor3 = Color3.fromRGB(0, 0, 0)
Reset.TextSize = 14.000

UICorner_16.Parent = Reset

Speedm.Name = "Speedm"
Speedm.Parent = Main
Speedm.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
Speedm.Position = UDim2.new(0.901115775, 0, 0.271493226, 0)
Speedm.Size = UDim2.new(0.0784165561, 0, 0.0904977471, 0)
Speedm.Font = Enum.Font.GothamBold
Speedm.Text = "+"
Speedm.TextColor3 = Color3.fromRGB(0, 0, 0)
Speedm.TextSize = 14.000

UICorner_17.Parent = Speedm

Speed.Name = "Speed"
Speed.Parent = Main
Speed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Speed.BackgroundTransparency = 1.000
Speed.Position = UDim2.new(0.833382785, 0, 0.269761175, 0)
Speed.Size = UDim2.new(0.0701073706, 0, 0.090000011, 0)
Speed.Font = Enum.Font.SourceSans
Speed.Text = "16"
Speed.TextColor3 = Color3.fromRGB(0, 0, 0)
Speed.TextSize = 18.000

Speedt.Name = "Speedt"
Speedt.Parent = Main
Speedt.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
Speedt.Position = UDim2.new(0.753908515, 0, 0.271493226, 0)
Speedt.Size = UDim2.new(0.0784165561, 0, 0.0904977471, 0)
Speedt.Font = Enum.Font.GothamBold
Speedt.Text = "-"
Speedt.TextColor3 = Color3.fromRGB(0, 0, 0)
Speedt.TextSize = 14.000

UICorner_18.Parent = Speedt

jumpm.Name = "jumpm"
jumpm.Parent = Main
jumpm.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
jumpm.Position = UDim2.new(0.165079653, 0, 0.406373829, 0)
jumpm.Size = UDim2.new(0.0784165561, 0, 0.0904977471, 0)
jumpm.Font = Enum.Font.GothamBold
jumpm.Text = "+"
jumpm.TextColor3 = Color3.fromRGB(0, 0, 0)
jumpm.TextSize = 14.000

UICorner_19.Parent = jumpm

Jump.Name = "Jump"
Jump.Parent = Main
Jump.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Jump.BackgroundTransparency = 1.000
Jump.Position = UDim2.new(0.0973467007, 0, 0.404641777, 0)
Jump.Size = UDim2.new(0.0701073706, 0, 0.090000011, 0)
Jump.Font = Enum.Font.SourceSans
Jump.Text = "50"
Jump.TextColor3 = Color3.fromRGB(0, 0, 0)
Jump.TextSize = 18.000

Jumpt.Name = "Jumpt"
Jumpt.Parent = Main
Jumpt.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
Jumpt.Position = UDim2.new(0.0178723931, 0, 0.406373829, 0)
Jumpt.Size = UDim2.new(0.0784165561, 0, 0.0904977471, 0)
Jumpt.Font = Enum.Font.GothamBold
Jumpt.Text = "-"
Jumpt.TextColor3 = Color3.fromRGB(0, 0, 0)
Jumpt.TextSize = 14.000

UICorner_20.Parent = Jumpt

jumpV2m.Name = "jumpV2m"
jumpV2m.Parent = Main
jumpV2m.BackgroundColor3 = Color3.fromRGB(190, 0, 3)
jumpV2m.Position = UDim2.new(0.414382219, 0, 0.406373829, 0)
jumpV2m.Size = UDim2.new(0.0784165561, 0, 0.0904977471, 0)
jumpV2m.Font = Enum.Font.GothamBold
jumpV2m.Text = "+"
jumpV2m.TextColor3 = Color3.fromRGB(0, 0, 0)
jumpV2m.TextSize = 14.000

UICorner_21.Parent = jumpV2m

Jumpe.Name = "Jumpe"
Jumpe.Parent = Main
Jumpe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Jumpe.BackgroundTransparency = 1.000
Jumpe.Position = UDim2.new(0.346649259, 0, 0.404641777, 0)
Jumpe.Size = UDim2.new(0.0701073706, 0, 0.090000011, 0)
Jumpe.Font = Enum.Font.SourceSans
Jumpe.Text = "50"
Jumpe.TextColor3 = Color3.fromRGB(0, 0, 0)
Jumpe.TextSize = 18.000

e.Name = "e"
e.Parent = Main
e.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
e.BackgroundTransparency = 1.000
e.Position = UDim2.new(0.0166201703, 0, 0.223634347, 0)
e.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
e.Font = Enum.Font.SourceSans
e.Text = "Fly"
e.TextColor3 = Color3.fromRGB(0, 0, 0)
e.TextSize = 18.000

r.Name = "r"
r.Parent = Main
r.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
r.BackgroundTransparency = 1.000
r.Position = UDim2.new(0.263548404, 0, 0.223634347, 0)
r.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
r.Font = Enum.Font.SourceSans
r.Text = "Reset"
r.TextColor3 = Color3.fromRGB(0, 0, 0)
r.TextSize = 18.000

r_2.Name = "r"
r_2.Parent = Main
r_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
r_2.BackgroundTransparency = 1.000
r_2.Position = UDim2.new(0.510476649, 0, 0.223634347, 0)
r_2.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
r_2.Font = Enum.Font.SourceSans
r_2.Text = "Kick Yourself"
r_2.TextColor3 = Color3.fromRGB(0, 0, 0)
r_2.TextSize = 18.000

r_3.Name = "r"
r_3.Parent = Main
r_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
r_3.BackgroundTransparency = 1.000
r_3.Position = UDim2.new(0.75028199, 0, 0.223634347, 0)
r_3.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
r_3.Font = Enum.Font.SourceSans
r_3.Text = "Speed"
r_3.TextColor3 = Color3.fromRGB(0, 0, 0)
r_3.TextSize = 18.000

r_4.Name = "r"
r_4.Parent = Main
r_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
r_4.BackgroundTransparency = 1.000
r_4.Position = UDim2.new(0.0166201591, 0, 0.359513462, 0)
r_4.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
r_4.Font = Enum.Font.SourceSans
r_4.Text = "Jump"
r_4.TextColor3 = Color3.fromRGB(0, 0, 0)
r_4.TextSize = 18.000

r_5.Name = "r"
r_5.Parent = Main
r_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
r_5.BackgroundTransparency = 1.000
r_5.Position = UDim2.new(0.265922725, 0, 0.359513462, 0)
r_5.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
r_5.Font = Enum.Font.SourceSans
r_5.Text = "Jump V2"
r_5.TextColor3 = Color3.fromRGB(0, 0, 0)
r_5.TextSize = 18.000

r_6.Name = "r"
r_6.Parent = Main
r_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
r_6.BackgroundTransparency = 1.000
r_6.Position = UDim2.new(0.510476708, 0, 0.360385865, 0)
r_6.Size = UDim2.new(0.227933764, 0, 0.0651087314, 0)
r_6.Font = Enum.Font.SourceSans
r_6.Text = "GodMode"
r_6.TextColor3 = Color3.fromRGB(0, 0, 0)
r_6.TextSize = 18.000

Close.Name = "Close"
Close.Parent = ScriptGui
Close.BackgroundColor3 = Color3.fromRGB(255, 15, 19)
Close.Position = UDim2.new(0.399459124, 0, 0.915634215, 0)
Close.Size = UDim2.new(0.200000003, 0, 0.0646009371, 0)
Close.Visible = false
Close.Font = Enum.Font.GothamBold
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

OpenSpectate.Name = "OpenSpectate"
OpenSpectate.Parent = ScriptGui
OpenSpectate.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
OpenSpectate.BorderColor3 = Color3.fromRGB(66, 66, 66)
OpenSpectate.Position = UDim2.new(0.944768548, 0, 0.826681018, 0)
OpenSpectate.Size = UDim2.new(0.0505549833, 0, 0.0340000018, 0)
OpenSpectate.Font = Enum.Font.SourceSansSemibold
OpenSpectate.Text = "Spectate"
OpenSpectate.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenSpectate.TextScaled = true
OpenSpectate.TextSize = 14.000
OpenSpectate.TextWrapped = true

UICorner_22.Parent = OpenSpectate

SpecLabel.Name = "SpecLabel"
SpecLabel.Parent = ScriptGui
SpecLabel.BackgroundColor3 = Color3.fromRGB(115, 115, 115)
SpecLabel.Position = UDim2.new(0.399122059, 0, 0.845177472, 0)
SpecLabel.Size = UDim2.new(0.200000003, 0, 0.0700000003, 0)
SpecLabel.Visible = false
SpecLabel.Font = Enum.Font.GothamBold
SpecLabel.Text = "Spectate"
SpecLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
SpecLabel.TextScaled = true
SpecLabel.TextSize = 14.000
SpecLabel.TextWrapped = true

UICorner_23.Parent = SpecLabel

ScrollingFrame.Parent = ScriptGui
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.Position = UDim2.new(0.00731144287, 0, 0.766694963, 0)
ScrollingFrame.Size = UDim2.new(0.116290554, 0, 0.216514528, 0)

Title.Name = "Title"
Title.Parent = ScrollingFrame
Title.BackgroundColor3 = Color3.fromRGB(131, 131, 131)
Title.Size = UDim2.new(0.949999988, 0, 0.138503343, 0)
Title.Font = Enum.Font.GothamBold
Title.Text = "Players"
Title.TextColor3 = Color3.fromRGB(0, 0, 0)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

UIGridLayout.Parent = ScrollingFrame
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellSize = UDim2.new(0.949999988, 0, 0.0299999993, 0)

Toggle.Name = "Toggle"
Toggle.Parent = ScriptGui
Toggle.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
Toggle.Position = UDim2.new(0.893037319, 0, 0.826681018, 0)
Toggle.Size = UDim2.new(0.050999999, 0, 0.0338312052, 0)
Toggle.Font = Enum.Font.SourceSans
Toggle.Text = "Teleport"
Toggle.TextColor3 = Color3.fromRGB(255, 255, 255)
Toggle.TextScaled = true
Toggle.TextSize = 14.000
Toggle.TextWrapped = true

UICorner_24.Parent = Toggle

TeleportFrame.Name = "TeleportFrame"
TeleportFrame.Parent = ScriptGui
TeleportFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TeleportFrame.Position = UDim2.new(0.00807265379, 0, 0.46619615, 0)
TeleportFrame.Size = UDim2.new(0, 114, 0, 111)
TeleportFrame.Visible = false

Player.Name = "Player"
Player.Parent = TeleportFrame
Player.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Player.Position = UDim2.new(0.0526315793, 0, 0.369369388, 0)
Player.Size = UDim2.new(0, 102, 0, 29)
Player.Font = Enum.Font.SourceSans
Player.PlaceholderText = "Player Name"
Player.Text = ""
Player.TextColor3 = Color3.fromRGB(0, 0, 0)
Player.TextSize = 14.000

Title_2.Name = "Title"
Title_2.Parent = TeleportFrame
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.Position = UDim2.new(0.254385978, 0, 0, 0)
Title_2.Size = UDim2.new(0, 57, 0, 18)
Title_2.Font = Enum.Font.SourceSans
Title_2.Text = "Player Teleport"
Title_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Title_2.TextSize = 14.000

Teleportn.Name = "Teleportn"
Teleportn.Parent = TeleportFrame
Teleportn.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Teleportn.Position = UDim2.new(0.210526317, 0, 0.693693638, 0)
Teleportn.Size = UDim2.new(0, 61, 0, 20)
Teleportn.Font = Enum.Font.SourceSans
Teleportn.Text = "Teleport"
Teleportn.TextColor3 = Color3.fromRGB(0, 0, 0)
Teleportn.TextSize = 14.000

Error.Name = "Error"
Error.Parent = TeleportFrame
Error.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Error.BackgroundTransparency = 1.000
Error.Position = UDim2.new(0.254385978, 0, 0.207207203, 0)
Error.Size = UDim2.new(0, 57, 0, 18)
Error.Visible = false
Error.Font = Enum.Font.SourceSans
Error.Text = "Error"
Error.TextColor3 = Color3.fromRGB(255, 0, 0)
Error.TextSize = 14.000

-- Scripts:

local function YGHU_fake_script() -- Open.open script 
	local script = Instance.new('LocalScript', Open)

	local frame = script.Parent.Parent.Main
	local open = false
	
	script.Parent.MouseButton1Click:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		else
			frame.Visible = false
		end
	end)
end
coroutine.wrap(YGHU_fake_script)()
local function FCLBNSL_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(FCLBNSL_fake_script)()
local function EPHIU_fake_script() -- Main.LocalScript 
	local script = Instance.new('LocalScript', Main)

	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(EPHIU_fake_script)()
local function IYPD_fake_script() -- Fly.LocalScript 
	local script = Instance.new('LocalScript', Fly)

	speed = 300
	
	repeat wait() until game.Players.LocalPlayer.Character
	--Variables--
	local button = script.Parent
	local plr = game.Players.LocalPlayer
	local char = plr.Character
	local hum = char:WaitForChild("Humanoid")
	local Torso = char:WaitForChild("HumanoidRootPart")
	local Mouse = plr:GetMouse()
	local toggle = false
	
	--Function--
	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.MouseButton1Click then
			if toggle == false then
				toggle = true
				local Anim = Instance.new("Animation")
				Anim.AnimationId = "rbxassetid://7007982251"
				local PlayAnim = hum:LoadAnimation(Anim)
				PlayAnim:Play()
				local BV = Instance.new("BodyVelocity",Torso)
				BV.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
				while toggle == true do
					BV.Velocity = Mouse.Hit.lookVector*speed
					wait()
				end
			end
			if toggle == false then
				toggle = true
				local Anim = Instance.new("Animation")
				Anim.AnimationId = "rbxassetid://7007982251" --Animation While Flying (You Can Change This).
				local PlayAnim = hum:LoadAnimation(Anim)
				PlayAnim:Play()
				local BV = Instance.new("BodyVelocity",Torso)
				BV.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
				while toggle == true do
					BV.Velocity = Mouse.Hit.lookVector*speed
					wait()
				end
			end
			if toggle == true then
				toggle = false
				Torso:FindFirstChildOfClass("BodyVelocity"):Destroy()
				local tracks = hum:GetPlayingAnimationTracks()
				for i, stoptracks in pairs(tracks) do
					stoptracks:Stop()
				end
				local Anim = Instance.new("Animation")
				Anim.AnimationId = "rbxassetid://0" --Idle Flying Animation( Recommend Not Changing This).
				local PlayAnim = hum:LoadAnimation(Anim)
				PlayAnim:Play()
			end
		end
	end)
end
coroutine.wrap(IYPD_fake_script)()
local function VENVGQ_fake_script() -- KickYourself.LocalScript 
	local script = Instance.new('LocalScript', KickYourself)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer:Kick("Kicked yourself haha funny number 69")
	end)
end
coroutine.wrap(VENVGQ_fake_script)()
local function SFFO_fake_script() -- JumpV2t.LocalScript 
	local script = Instance.new('LocalScript', JumpV2t)

	local label = script.Parent.Parent.Jumpe
	
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.character.Humanoid.JumpHeight= game.Players.LocalPlayer.character.Humanoid.JumpHeight -10
		label.Text = game.Players.LocalPlayer.character.Humanoid.JumpHeight
	end)
end
coroutine.wrap(SFFO_fake_script)()
local function XAOII_fake_script() -- GodMode.LocalScript 
	local script = Instance.new('LocalScript', GodMode)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.Health = 100000
		game.Players.LocalPlayer.Character.Humanoid.MaxHealth = 100000
	end)
end
coroutine.wrap(XAOII_fake_script)()
local function YRLJ_fake_script() -- Reset.LocalScript 
	local script = Instance.new('LocalScript', Reset)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
		game.Players.LocalPlayer.Character.Humanoid.MaxHealth = 0
	end)
end
coroutine.wrap(YRLJ_fake_script)()
local function EGPPRS_fake_script() -- Speedm.LocalScript 
	local script = Instance.new('LocalScript', Speedm)

	local label = script.Parent.Parent.Speed
	
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.character.Humanoid.WalkSpeed = game.Players.LocalPlayer.character.Humanoid.WalkSpeed +50
		label.Text = game.Players.LocalPlayer.character.Humanoid.WalkSpeed
	end)
end
coroutine.wrap(EGPPRS_fake_script)()
local function IMXSTYG_fake_script() -- Speedt.LocalScript 
	local script = Instance.new('LocalScript', Speedt)

	local label = script.Parent.Parent.Speed
	
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.character.Humanoid.WalkSpeed = game.Players.LocalPlayer.character.Humanoid.WalkSpeed -10
		label.Text = game.Players.LocalPlayer.character.Humanoid.WalkSpeed
	end)
end
coroutine.wrap(IMXSTYG_fake_script)()
local function PSNYQ_fake_script() -- jumpm.LocalScript 
	local script = Instance.new('LocalScript', jumpm)

	local label = script.Parent.Parent.Jump
	
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.character.Humanoid.JumpPower = game.Players.LocalPlayer.character.Humanoid.JumpPower +25
		label.Text = game.Players.LocalPlayer.character.Humanoid.JumpPower
	end)
end
coroutine.wrap(PSNYQ_fake_script)()
local function SXYVS_fake_script() -- Jumpt.LocalScript 
	local script = Instance.new('LocalScript', Jumpt)

	local label = script.Parent.Parent.Jump
	
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.character.Humanoid.JumpPower = game.Players.LocalPlayer.character.Humanoid.JumpPower -10
		label.Text = game.Players.LocalPlayer.character.Humanoid.JumpPower
	end)
end
coroutine.wrap(SXYVS_fake_script)()
local function VHZS_fake_script() -- jumpV2m.LocalScript 
	local script = Instance.new('LocalScript', jumpV2m)

	local label = script.Parent.Parent.Jumpe
	
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.character.Humanoid.JumpHeight = game.Players.LocalPlayer.character.Humanoid.JumpHeight+25
		label.Text = game.Players.LocalPlayer.character.Humanoid.JumpHeight
	end)
end
coroutine.wrap(VHZS_fake_script)()
local function MZNIAB_fake_script() -- OpenSpectate.LocalScript 
	local script = Instance.new('LocalScript', OpenSpectate)

	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(MZNIAB_fake_script)()
local function DOVKDV_fake_script() -- ScrollingFrame.LocalScript 
	local script = Instance.new('LocalScript', ScrollingFrame)

	local frame = script.Parent
	local open = frame.Parent.OpenSpectate
	local close = frame.Parent.Close
	local specLabel = frame.Parent.SpecLabel
	local player = game.Players.LocalPlayer
	frame.Visible = false
	close.Visible = false
	specLabel.Visible = false
	local function spec()
		frame.Visible = not frame.Visible
		for _, button in pairs(frame:GetChildren()) do
			if button:IsA('TextButton') then
				button:Destroy()
			end
		end
		for _, plr in pairs(game.Players:GetChildren()) do
			if plr.Name ~= player.Name then
				local name = Instance.new('TextButton')
				name.Parent = frame
				name.Text = plr.Name
				name.TextScaled = true
				name.MouseButton1Click:Connect(function()
					local person = game.Players:FindFirstChild(name.Text)
					game.Workspace.CurrentCamera.CameraSubject = person.Character
					specLabel.Visible = true
					specLabel.Text = 'Spectating '..name.Text
					frame.Visible = false
					close.Visible = true
				end)
			end
		end
	end
	close.MouseButton1Click:Connect(function()
		game.Workspace.CurrentCamera.CameraSubject = player.Character
		specLabel.Visible = false
		close.Visible = false
	end)
	open.MouseButton1Click:Connect(spec)
end
coroutine.wrap(DOVKDV_fake_script)()
-- Toggle.open script is disabled.
-- Teleportn.LocalScript is disabled.
-- TeleportFrame.LocalScript is disabled.
-- TeleportFrame.Script is disabled.
