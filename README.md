-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local Title = Instance.new("TextLabel")
local Title_Roundify_12px = Instance.new("ImageLabel")
local Exit = Instance.new("TextButton")
local Exit_Roundify_12px = Instance.new("ImageLabel")
local Med = Instance.new("TextButton")
local TextButton_Roundify_12px = Instance.new("ImageLabel")
local Gem = Instance.new("TextButton")
local TextButton_Roundify_12px_2 = Instance.new("ImageLabel")
local Gun = Instance.new("TextButton")
local TextButton_Roundify_12px_3 = Instance.new("ImageLabel")
local Car = Instance.new("TextButton")
local TextButton_Roundify_12px_4 = Instance.new("ImageLabel")
local Pub = Instance.new("TextButton")
local TextButton_Roundify_12px_5 = Instance.new("ImageLabel")
local InVault = Instance.new("TextButton")
local TextButton_Roundify_12px_6 = Instance.new("ImageLabel")
local OutVault = Instance.new("TextButton")
local TextButton_Roundify_12px_7 = Instance.new("ImageLabel")
local Bank = Instance.new("TextButton")
local TextButton_Roundify_12px_8 = Instance.new("ImageLabel")
local City = Instance.new("TextButton")
local TextButton_Roundify_12px_9 = Instance.new("ImageLabel")
local Rust = Instance.new("TextButton")
local TextButton_Roundify_12px_10 = Instance.new("ImageLabel")
local RemoveD = Instance.new("TextButton")
local TextButton_Roundify_12px_11 = Instance.new("ImageLabel")
local FEAR = Instance.new("TextButton")
local TextButton_Roundify_12px_12 = Instance.new("ImageLabel")
local Cloth = Instance.new("TextButton")
local TextButton_Roundify_12px_13 = Instance.new("ImageLabel")
local RemoveL = Instance.new("TextButton")
local TextButton_Roundify_12px_14 = Instance.new("ImageLabel")
local NoClip = Instance.new("TextButton")
local Toggle = Instance.new("ImageLabel")
local TFrame = Instance.new("ImageLabel")
local TextButton = Instance.new("TextButton")
local TextButton_Roundify_12px_15 = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Name = "Frame"
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.237569049, 0, 0.133489504, 0)
Frame.Size = UDim2.new(0, 649, 0, 456)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(34, 34, 34)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120
Frame.Visible = false
Frame.Draggable = true

Title.Name = "Title"
Title.Parent = Frame
Title.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Title.BackgroundTransparency = 1.000
Title.BorderSizePixel = 0
Title.Size = UDim2.new(0, 649, 0, 50)
Title.ZIndex = 2
Title.Font = Enum.Font.GothamBold
Title.Text = "Dawn of Aurora TP"
Title.TextColor3 = Color3.fromRGB(0, 0, 0)
Title.TextSize = 32.000

Title_Roundify_12px.Name = "Title_Roundify_12px"
Title_Roundify_12px.Parent = Title
Title_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
Title_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_Roundify_12px.BackgroundTransparency = 1.000
Title_Roundify_12px.Position = UDim2.new(0.5, 0, 0.5, 0)
Title_Roundify_12px.Size = UDim2.new(1, 0, 1, 0)
Title_Roundify_12px.Image = "rbxassetid://3570695787"
Title_Roundify_12px.ImageColor3 = Color3.fromRGB(62, 62, 62)
Title_Roundify_12px.ScaleType = Enum.ScaleType.Slice
Title_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
Title_Roundify_12px.SliceScale = 0.120

Exit.Name = "Exit"
Exit.Parent = Title
Exit.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Exit.BackgroundTransparency = 1.000
Exit.BorderSizePixel = 0
Exit.Position = UDim2.new(0.922026455, 0, 0, 0)
Exit.Size = UDim2.new(0, 50, 0, 50)
Exit.ZIndex = 2
Exit.Font = Enum.Font.Cartoon
Exit.Text = "X"
Exit.TextColor3 = Color3.fromRGB(0, 0, 0)
Exit.TextSize = 32.000
Exit.MouseButton1Down:connect(function()
TextButton.Visible = true
Frame.Visible = false
end)


Exit_Roundify_12px.Name = "Exit_Roundify_12px"
Exit_Roundify_12px.Parent = Exit
Exit_Roundify_12px.Active = true
Exit_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
Exit_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Exit_Roundify_12px.BackgroundTransparency = 1.000
Exit_Roundify_12px.Position = UDim2.new(0.5, 0, 0.5, 0)
Exit_Roundify_12px.Selectable = true
Exit_Roundify_12px.Size = UDim2.new(1, 0, 1, 0)
Exit_Roundify_12px.Image = "rbxassetid://3570695787"
Exit_Roundify_12px.ImageColor3 = Color3.fromRGB(255, 0, 0)
Exit_Roundify_12px.ScaleType = Enum.ScaleType.Slice
Exit_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
Exit_Roundify_12px.SliceScale = 0.120

Med.Name = "Med"
Med.Parent = Frame
Med.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Med.BackgroundTransparency = 1.000
Med.BorderSizePixel = 0
Med.Position = UDim2.new(0.383667201, 0, 0.502192914, 0)
Med.Size = UDim2.new(0, 150, 0, 50)
Med.ZIndex = 2
Med.Font = Enum.Font.SourceSans
Med.Text = "Med Shop"
Med.TextColor3 = Color3.fromRGB(0, 0, 0)
Med.TextSize = 20.000

TextButton_Roundify_12px.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px.Parent = Med
TextButton_Roundify_12px.Active = true
TextButton_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px.BackgroundTransparency = 1.000
TextButton_Roundify_12px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px.Selectable = true
TextButton_Roundify_12px.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px.SliceScale = 0.120

Gem.Name = "Gem"
Gem.Parent = Frame
Gem.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Gem.BackgroundTransparency = 1.000
Gem.BorderSizePixel = 0
Gem.Position = UDim2.new(0.383667201, 0, 0.324561357, 0)
Gem.Size = UDim2.new(0, 150, 0, 50)
Gem.ZIndex = 2
Gem.Font = Enum.Font.SourceSans
Gem.Text = "Gem Shop"
Gem.TextColor3 = Color3.fromRGB(0, 0, 0)
Gem.TextSize = 20.000

TextButton_Roundify_12px_2.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_2.Parent = Gem
TextButton_Roundify_12px_2.Active = true
TextButton_Roundify_12px_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_2.BackgroundTransparency = 1.000
TextButton_Roundify_12px_2.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_2.Selectable = true
TextButton_Roundify_12px_2.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_2.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_2.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_2.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_2.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_2.SliceScale = 0.120

Gun.Name = "Gun"
Gun.Parent = Frame
Gun.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Gun.BackgroundTransparency = 1.000
Gun.BorderSizePixel = 0
Gun.Position = UDim2.new(0.383667201, 0, 0.149122745, 0)
Gun.Size = UDim2.new(0, 150, 0, 50)
Gun.ZIndex = 2
Gun.Font = Enum.Font.SourceSans
Gun.Text = "Gun Shop"
Gun.TextColor3 = Color3.fromRGB(0, 0, 0)
Gun.TextSize = 20.000

TextButton_Roundify_12px_3.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_3.Parent = Gun
TextButton_Roundify_12px_3.Active = true
TextButton_Roundify_12px_3.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_3.BackgroundTransparency = 1.000
TextButton_Roundify_12px_3.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_3.Selectable = true
TextButton_Roundify_12px_3.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_3.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_3.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_3.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_3.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_3.SliceScale = 0.120

Car.Name = "Car"
Car.Parent = Frame
Car.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Car.BackgroundTransparency = 1.000
Car.BorderSizePixel = 0
Car.Position = UDim2.new(0.383667201, 0, 0.675438523, 0)
Car.Size = UDim2.new(0, 150, 0, 50)
Car.ZIndex = 2
Car.Font = Enum.Font.SourceSans
Car.Text = "Car Shop"
Car.TextColor3 = Color3.fromRGB(0, 0, 0)
Car.TextSize = 20.000

TextButton_Roundify_12px_4.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_4.Parent = Car
TextButton_Roundify_12px_4.Active = true
TextButton_Roundify_12px_4.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_4.BackgroundTransparency = 1.000
TextButton_Roundify_12px_4.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_4.Selectable = true
TextButton_Roundify_12px_4.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_4.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_4.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_4.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_4.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_4.SliceScale = 0.120

Pub.Name = "Pub"
Pub.Parent = Frame
Pub.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Pub.BackgroundTransparency = 1.000
Pub.BorderSizePixel = 0
Pub.Position = UDim2.new(0.383667201, 0, 0.850877106, 0)
Pub.Size = UDim2.new(0, 150, 0, 50)
Pub.ZIndex = 2
Pub.Font = Enum.Font.SourceSans
Pub.Text = "Pub Shop"
Pub.TextColor3 = Color3.fromRGB(0, 0, 0)
Pub.TextSize = 20.000

TextButton_Roundify_12px_5.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_5.Parent = Pub
TextButton_Roundify_12px_5.Active = true
TextButton_Roundify_12px_5.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_5.BackgroundTransparency = 1.000
TextButton_Roundify_12px_5.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_5.Selectable = true
TextButton_Roundify_12px_5.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_5.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_5.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_5.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_5.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_5.SliceScale = 0.120

InVault.Name = "InVault"
InVault.Parent = Frame
InVault.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
InVault.BackgroundTransparency = 1.000
InVault.BorderSizePixel = 0
InVault.Position = UDim2.new(0.0847457722, 0, 0.502192914, 0)
InVault.Size = UDim2.new(0, 150, 0, 50)
InVault.ZIndex = 2
InVault.Font = Enum.Font.SourceSans
InVault.Text = "In Vault"
InVault.TextColor3 = Color3.fromRGB(0, 0, 0)
InVault.TextSize = 20.000

TextButton_Roundify_12px_6.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_6.Parent = InVault
TextButton_Roundify_12px_6.Active = true
TextButton_Roundify_12px_6.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_6.BackgroundTransparency = 1.000
TextButton_Roundify_12px_6.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_6.Selectable = true
TextButton_Roundify_12px_6.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_6.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_6.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_6.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_6.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_6.SliceScale = 0.120

OutVault.Name = "OutVault"
OutVault.Parent = Frame
OutVault.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
OutVault.BackgroundTransparency = 1.000
OutVault.BorderSizePixel = 0
OutVault.Position = UDim2.new(0.0847457722, 0, 0.326754332, 0)
OutVault.Size = UDim2.new(0, 150, 0, 50)
OutVault.ZIndex = 2
OutVault.Font = Enum.Font.SourceSans
OutVault.Text = "Out Vault"
OutVault.TextColor3 = Color3.fromRGB(0, 0, 0)
OutVault.TextSize = 20.000

TextButton_Roundify_12px_7.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_7.Parent = OutVault
TextButton_Roundify_12px_7.Active = true
TextButton_Roundify_12px_7.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_7.BackgroundTransparency = 1.000
TextButton_Roundify_12px_7.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_7.Selectable = true
TextButton_Roundify_12px_7.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_7.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_7.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_7.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_7.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_7.SliceScale = 0.120

Bank.Name = "Bank"
Bank.Parent = Frame
Bank.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Bank.BackgroundTransparency = 1.000
Bank.BorderSizePixel = 0
Bank.Position = UDim2.new(0.0847457722, 0, 0.151315734, 0)
Bank.Size = UDim2.new(0, 150, 0, 50)
Bank.ZIndex = 2
Bank.Font = Enum.Font.SourceSans
Bank.Text = "Out Bank"
Bank.TextColor3 = Color3.fromRGB(0, 0, 0)
Bank.TextSize = 20.000

TextButton_Roundify_12px_8.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_8.Parent = Bank
TextButton_Roundify_12px_8.Active = true
TextButton_Roundify_12px_8.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_8.BackgroundTransparency = 1.000
TextButton_Roundify_12px_8.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_8.Selectable = true
TextButton_Roundify_12px_8.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_8.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_8.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_8.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_8.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_8.SliceScale = 0.120

City.Name = "City"
City.Parent = Frame
City.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
City.BackgroundTransparency = 1.000
City.BorderSizePixel = 0
City.Position = UDim2.new(0.0847457722, 0, 0.677631497, 0)
City.Size = UDim2.new(0, 150, 0, 50)
City.ZIndex = 2
City.Font = Enum.Font.SourceSans
City.Text = "City Crim Base"
City.TextColor3 = Color3.fromRGB(0, 0, 0)
City.TextSize = 20.000

TextButton_Roundify_12px_9.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_9.Parent = City
TextButton_Roundify_12px_9.Active = true
TextButton_Roundify_12px_9.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_9.BackgroundTransparency = 1.000
TextButton_Roundify_12px_9.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_9.Selectable = true
TextButton_Roundify_12px_9.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_9.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_9.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_9.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_9.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_9.SliceScale = 0.120

Rust.Name = "Rust"
Rust.Parent = Frame
Rust.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Rust.BackgroundTransparency = 1.000
Rust.BorderSizePixel = 0
Rust.Position = UDim2.new(0.0847457722, 0, 0.85307008, 0)
Rust.Size = UDim2.new(0, 150, 0, 50)
Rust.ZIndex = 2
Rust.Font = Enum.Font.SourceSans
Rust.Text = "Rust Crim Base"
Rust.TextColor3 = Color3.fromRGB(0, 0, 0)
Rust.TextSize = 20.000

TextButton_Roundify_12px_10.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_10.Parent = Rust
TextButton_Roundify_12px_10.Active = true
TextButton_Roundify_12px_10.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_10.BackgroundTransparency = 1.000
TextButton_Roundify_12px_10.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_10.Selectable = true
TextButton_Roundify_12px_10.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_10.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_10.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_10.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_10.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_10.SliceScale = 0.120

RemoveD.Name = "RemoveD"
RemoveD.Parent = Frame
RemoveD.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
RemoveD.BackgroundTransparency = 1.000
RemoveD.BorderSizePixel = 0
RemoveD.Position = UDim2.new(0.683000028, 0, 0.501999974, 0)
RemoveD.Size = UDim2.new(0, 150, 0, 50)
RemoveD.ZIndex = 2
RemoveD.Font = Enum.Font.SourceSans
RemoveD.Text = "Remove Doors"
RemoveD.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveD.TextSize = 20.000

TextButton_Roundify_12px_11.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_11.Parent = RemoveD
TextButton_Roundify_12px_11.Active = true
TextButton_Roundify_12px_11.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_11.BackgroundTransparency = 1.000
TextButton_Roundify_12px_11.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_11.Selectable = true
TextButton_Roundify_12px_11.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_11.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_11.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_11.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_11.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_11.SliceScale = 0.120

FEAR.Name = "FEAR"
FEAR.Parent = Frame
FEAR.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
FEAR.BackgroundTransparency = 1.000
FEAR.BorderSizePixel = 0
FEAR.Position = UDim2.new(0.682588577, 0, 0.324561357, 0)
FEAR.Size = UDim2.new(0, 150, 0, 50)
FEAR.ZIndex = 2
FEAR.Font = Enum.Font.SourceSans
FEAR.Text = "F.E.A.R. Base"
FEAR.TextColor3 = Color3.fromRGB(0, 0, 0)
FEAR.TextSize = 20.000

TextButton_Roundify_12px_12.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_12.Parent = FEAR
TextButton_Roundify_12px_12.Active = true
TextButton_Roundify_12px_12.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_12.BackgroundTransparency = 1.000
TextButton_Roundify_12px_12.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_12.Selectable = true
TextButton_Roundify_12px_12.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_12.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_12.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_12.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_12.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_12.SliceScale = 0.120

Cloth.Name = "Cloth"
Cloth.Parent = Frame
Cloth.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Cloth.BackgroundTransparency = 1.000
Cloth.BorderSizePixel = 0
Cloth.Position = UDim2.new(0.682588577, 0, 0.149122745, 0)
Cloth.Size = UDim2.new(0, 150, 0, 50)
Cloth.ZIndex = 2
Cloth.Font = Enum.Font.SourceSans
Cloth.Text = "Clothes Shop"
Cloth.TextColor3 = Color3.fromRGB(0, 0, 0)
Cloth.TextSize = 20.000

TextButton_Roundify_12px_13.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_13.Parent = Cloth
TextButton_Roundify_12px_13.Active = true
TextButton_Roundify_12px_13.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_13.BackgroundTransparency = 1.000
TextButton_Roundify_12px_13.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_13.Selectable = true
TextButton_Roundify_12px_13.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_13.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_13.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_13.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_13.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_13.SliceScale = 0.120

RemoveL.Name = "RemoveL"
RemoveL.Parent = Frame
RemoveL.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
RemoveL.BackgroundTransparency = 1.000
RemoveL.BorderSizePixel = 0
RemoveL.Position = UDim2.new(0.682588577, 0, 0.675438523, 0)
RemoveL.Size = UDim2.new(0, 150, 0, 50)
RemoveL.ZIndex = 2
RemoveL.Font = Enum.Font.SourceSans
RemoveL.Text = "Remove Lasers"
RemoveL.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveL.TextSize = 20.000

TextButton_Roundify_12px_14.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_14.Parent = RemoveL
TextButton_Roundify_12px_14.Active = true
TextButton_Roundify_12px_14.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_14.BackgroundTransparency = 1.000
TextButton_Roundify_12px_14.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_14.Selectable = true
TextButton_Roundify_12px_14.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_14.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_14.ImageColor3 = Color3.fromRGB(62, 62, 62)
TextButton_Roundify_12px_14.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_14.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_14.SliceScale = 0.120

NoClip.Name = "NoClip"
NoClip.Parent = Frame
NoClip.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
NoClip.BackgroundTransparency = 1.000
NoClip.BorderSizePixel = 0
NoClip.Position = UDim2.new(0.682588577, 0, 0.850877106, 0)
NoClip.Size = UDim2.new(0, 150, 0, 50)
NoClip.ZIndex = 2
NoClip.Font = Enum.Font.SourceSans
NoClip.Text = "No Clip"
NoClip.TextColor3 = Color3.fromRGB(0, 0, 0)
NoClip.TextSize = 20.000

Toggle.Name = "Toggle"
Toggle.Parent = NoClip
Toggle.Active = true
Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Toggle.BackgroundTransparency = 1.000
Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
Toggle.Selectable = true
Toggle.Size = UDim2.new(1, 0, 1, 0)
Toggle.Image = "rbxassetid://3570695787"
Toggle.ImageColor3 = Color3.fromRGB(62, 62, 62)
Toggle.ScaleType = Enum.ScaleType.Slice
Toggle.SliceCenter = Rect.new(100, 100, 100, 100)
Toggle.SliceScale = 0.120

TFrame.Name = "TFrame"
TFrame.Parent = NoClip
TFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TFrame.BackgroundTransparency = 1.000
TFrame.Position = UDim2.new(0.861780167, 0, 0, 0)
TFrame.Size = UDim2.new(0, 20, 0, 50)
TFrame.Image = "rbxassetid://3570695787"
TFrame.ImageColor3 = Color3.fromRGB(255, 0, 0)
TFrame.ScaleType = Enum.ScaleType.Slice
TFrame.SliceCenter = Rect.new(100, 100, 100, 100)
TFrame.SliceScale = 0.120

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
TextButton.BackgroundTransparency = 1.000
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.538279414, 0, 0.0245901644, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.ZIndex = 2
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "Open TP"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 32.000
TextButton.MouseButton1Down:connect(function()
Frame.Visible = true
TextButton.Visible = false
end)

TextButton_Roundify_12px_15.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px_15.Parent = TextButton
TextButton_Roundify_12px_15.Active = true
TextButton_Roundify_12px_15.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px_15.BackgroundTransparency = 1.000
TextButton_Roundify_12px_15.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px_15.Selectable = true
TextButton_Roundify_12px_15.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px_15.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px_15.ImageColor3 = Color3.fromRGB(0, 170, 0)
TextButton_Roundify_12px_15.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px_15.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px_15.SliceScale = 0.120

--Scripts

local UserInputService = game:GetService("UserInputService")

local gui = Frame

local dragging
local dragInput
local dragStart
local startPos

local function update(input)
	local delta = input.Position - dragStart
	gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
end

gui.InputBegan:Connect(function(input)
	if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
		dragging = true
		dragStart = input.Position
		startPos = gui.Position
		
		input.Changed:Connect(function()
			if input.UserInputState == Enum.UserInputState.End then
				dragging = false
			end
		end)
	end
end)

gui.InputChanged:Connect(function(input)
	if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
		dragInput = input
	end
end)

UserInputService.InputChanged:Connect(function(input)
	if input == dragInput and dragging then
		update(input)
	end
end)

function tp(x,y,z)
-- SETTINGS START
local valtomove = 4
-- SETTINGS END

game:getService("RunService"):BindToRenderStep("tp",0,function()
game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):ChangeState(11)
end)


for i=0,2,1 do
if x < game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X then
while x < game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X-valtomove,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z))
end
end
if z < game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z then
while z < game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z-valtomove))
end
end
if x > game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X then
while x > game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X+valtomove,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z))
end
end
if z > game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z then
while z > game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z+valtomove))
end
end
if y < game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y then
while y < game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y-valtomove,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z))
end
end
if y > game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y then
while y > game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Y+valtomove,game.Players.LocalPlayer.Character.HumanoidRootPart.Position.Z))
end
end
end
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(x,y,z))


game:getService("RunService"):UnbindFromRenderStep("tp")
end

InVault.MouseButton1Down:connect(function()
tp(333,111,-3234)
end)

OutVault.MouseButton1Down:connect(function()
tp(392,112,-3221)
end)

Bank.MouseButton1Down:connect(function()
tp(900,142,-3192)
end)

City.MouseButton1Down:connect(function()
tp(-1019,114,-3026)
end)

Rust.MouseButton1Down:connect(function()
tp(895,51,-513)
end)

Gun.MouseButton1Down:connect(function()
tp(670,51,-466)
end)

Car.MouseButton1Down:connect(function()
tp(504,51,-343)
end)

Gem.MouseButton1Down:connect(function()
tp(594,51,-354)
end)

Med.MouseButton1Down:connect(function()
tp(719,51,-522)
end)

Cloth.MouseButton1Down:connect(function()
tp(677,51,-760)
end)

Pub.MouseButton1Down:connect(function()
tp(820,51,-592)
end)

FEAR.MouseButton1Down:connect(function()
tp(-526,109,-1664)
end)

RemoveD.MouseButton1Down:connect(function()
game.Workspace.StaticEntity.PrisonLaserSecuritySystem:Destroy()
game.Workspace.StaticEntity.TeamForcefieldDoors:Destroy()
game.Workspace.StaticEntity.JailCells:Destroy()
end)

RemoveL.MouseButton1Down:connect(function()
game.Workspace.StaticEntity.BankSystem.Lasers:Destroy()
end)

local clip = true

NoClip.MouseButton1Down:connect(function()
	if clip then
		game:getService("RunService"):BindToRenderStep("no clip",0,function()
		game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):ChangeState(11)
		end)
		clip = false
		TFrame.ImageColor3 = Color3.fromRGB(0, 255, 0)
	else
		game:getService("RunService"):UnbindFromRenderStep("no clip")
		clip = true
		TFrame.ImageColor3 = Color3.fromRGB(255, 0, 0)
		
	end
	
end)
