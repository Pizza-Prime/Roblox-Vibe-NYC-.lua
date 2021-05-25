--# Roblox-Vibe-NYC-.lua
--A roblox script I made for Vibe NYC. It gives you all the items in the game.


--Sub to pizza prime :)
-- Took me 1 hour to make this (In class)

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Shotgun = Instance.new("TextButton")
local RGBPan = Instance.new("TextButton")
local Pistol = Instance.new("TextButton")
local Phone = Instance.new("TextButton")
local GravityGun = Instance.new("TextButton")
local Flame = Instance.new("TextButton")
local Tommy = Instance.new("TextButton")
local Camera = Instance.new("TextButton")
local VibeRifle = Instance.new("TextButton")
local ReaperScythe = Instance.new("TextButton")
local VibeGuitar = Instance.new("TextButton")
local RGBkatana = Instance.new("TextButton")
local All = Instance.new("TextButton")
local Label = Instance.new("TextLabel")
local Label_2 = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Frame = Instance.new("Frame")

--Properties:

ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Main.BorderColor3 = Color3.fromRGB(44, 44, 44)
Main.Position = UDim2.new(0.541619778, 0, 0.598014891, 0)
Main.Size = UDim2.new(0, 529, 0, 197)

TextBox.Parent = Main
TextBox.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
TextBox.Position = UDim2.new(0.0189035926, 0, 0.312991679, 0)
TextBox.Size = UDim2.new(0, 200, 0, 29)
TextBox.Font = Enum.Font.Roboto
TextBox.PlaceholderColor3 = Color3.fromRGB(170, 255, 0)
TextBox.PlaceholderText = "Search"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 20.000

ScrollingFrame.Parent = Main
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
ScrollingFrame.BorderColor3 = Color3.fromRGB(40, 40, 40)
ScrollingFrame.Position = UDim2.new(0.438667625, 0, 0.0143161491, 0)
ScrollingFrame.Size = UDim2.new(0, 296, 0, 190)

Shotgun.Name = "Shotgun"
Shotgun.Parent = ScrollingFrame
Shotgun.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Shotgun.Position = UDim2.new(0.0304054096, 0, 0.0260416679, 0)
Shotgun.Size = UDim2.new(0, 117, 0, 21)
Shotgun.Font = Enum.Font.SourceSans
Shotgun.Text = "Shotgun"
Shotgun.TextColor3 = Color3.fromRGB(170, 0, 0)
Shotgun.TextSize = 14.000
Shotgun.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.Shotgun.Parent = game.Players.LocalPlayer.Backpack
end)

RGBPan.Name = "RGB Pan"
RGBPan.Parent = ScrollingFrame
RGBPan.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
RGBPan.Position = UDim2.new(0.496621639, 0, 0.0260416679, 0)
RGBPan.Size = UDim2.new(0, 117, 0, 21)
RGBPan.Font = Enum.Font.SourceSans
RGBPan.Text = "RGB Panda"
RGBPan.TextColor3 = Color3.fromRGB(170, 0, 0)
RGBPan.TextSize = 14.000
RGBPan.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.RainbowPanda.Parent = game.Players.LocalPlayer.Backpack
end)

Pistol.Name = "Pistol"
Pistol.Parent = ScrollingFrame
Pistol.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Pistol.Position = UDim2.new(0.030405432, 0, 0.214930564, 0)
Pistol.Size = UDim2.new(0, 117, 0, 21)
Pistol.Font = Enum.Font.SourceSans
Pistol.Text = "Pistol"
Pistol.TextColor3 = Color3.fromRGB(170, 0, 0)
Pistol.TextSize = 14.000
Pistol.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.Pistol.Parent = game.Players.LocalPlayer.Backpack
end)

Phone.Name = "Phone"
Phone.Parent = ScrollingFrame
Phone.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Phone.Position = UDim2.new(0.496621639, 0, 0.214930564, 0)
Phone.Size = UDim2.new(0, 117, 0, 21)
Phone.Font = Enum.Font.SourceSans
Phone.Text = "Phone"
Phone.TextColor3 = Color3.fromRGB(170, 0, 0)
Phone.TextSize = 14.000
Phone.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.Phone.Parent = game.Players.LocalPlayer.Backpack
end)

GravityGun.Name = "GravityGun"
GravityGun.Parent = ScrollingFrame
GravityGun.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
GravityGun.Position = UDim2.new(0.030405432, 0, 0.414930582, 0)
GravityGun.Size = UDim2.new(0, 117, 0, 21)
GravityGun.Font = Enum.Font.SourceSans
GravityGun.Text = "GravityGun"
GravityGun.TextColor3 = Color3.fromRGB(170, 0, 0)
GravityGun.TextSize = 14.000
GravityGun.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.GravityGun.Parent = game.Players.LocalPlayer.Backpack
end)


Flame.Name = "Flame"
Flame.Parent = ScrollingFrame
Flame.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Flame.Position = UDim2.new(0.496621639, 0, 0.414930582, 0)
Flame.Size = UDim2.new(0, 117, 0, 21)
Flame.Font = Enum.Font.SourceSans
Flame.Text = "Flamethrower"
Flame.TextColor3 = Color3.fromRGB(170, 0, 0)
Flame.TextSize = 14.000
Flame.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.Flamethrower.Parent = game.Players.LocalPlayer.Backpack
end)

Tommy.Name = "Tommy"
Tommy.Parent = ScrollingFrame
Tommy.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Tommy.Position = UDim2.new(0.030405432, 0, 0.61493057, 0)
Tommy.Size = UDim2.new(0, 117, 0, 21)
Tommy.Font = Enum.Font.SourceSans
Tommy.Text = "TommyGun"
Tommy.TextColor3 = Color3.fromRGB(170, 0, 0)
Tommy.TextSize = 14.000
Tommy.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.TommyGun.Parent = game.Players.LocalPlayer.Backpack
end)

Camera.Name = "Camera"
Camera.Parent = ScrollingFrame
Camera.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
Camera.Position = UDim2.new(0.496621639, 0, 0.61493057, 0)
Camera.Size = UDim2.new(0, 117, 0, 21)
Camera.Font = Enum.Font.SourceSans
Camera.Text = "Camera"
Camera.TextColor3 = Color3.fromRGB(170, 0, 0)
Camera.TextSize = 14.000
Camera.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.Camera.Parent = game.Players.LocalPlayer.Backpack
end)

VibeRifle.Name = "VibeRifle"
VibeRifle.Parent = ScrollingFrame
VibeRifle.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
VibeRifle.Position = UDim2.new(0.030405432, 0, 0.780976832, 0)
VibeRifle.Size = UDim2.new(0, 117, 0, 21)
VibeRifle.Font = Enum.Font.SourceSans
VibeRifle.Text = "VibeRifle"
VibeRifle.TextColor3 = Color3.fromRGB(170, 0, 0)
VibeRifle.TextSize = 14.000
VibeRifle.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.VibeRifle.Parent = game.Players.LocalPlayer.Backpack
end)

ReaperScythe.Name = "ReaperScythe"
ReaperScythe.Parent = ScrollingFrame
ReaperScythe.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
ReaperScythe.Position = UDim2.new(0.496621639, 0, 0.780976832, 0)
ReaperScythe.Size = UDim2.new(0, 117, 0, 21)
ReaperScythe.Font = Enum.Font.SourceSans
ReaperScythe.Text = "ReaperScythe"
ReaperScythe.TextColor3 = Color3.fromRGB(170, 0, 0)
ReaperScythe.TextSize = 14.000
ReaperScythe.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.ReaperScythe.Parent = game.Players.LocalPlayer.Backpack
end)

VibeGuitar.Name = "VibeGuitar"
VibeGuitar.Parent = ScrollingFrame
VibeGuitar.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
VibeGuitar.Position = UDim2.new(0.030405432, 0, 0.930723011, 0)
VibeGuitar.Size = UDim2.new(0, 117, 0, 21)
VibeGuitar.Font = Enum.Font.SourceSans
VibeGuitar.Text = "VibeGuitar"
VibeGuitar.TextColor3 = Color3.fromRGB(170, 0, 0)
VibeGuitar.TextSize = 14.000
VibeGuitar.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.VibeGuitar.Parent = game.Players.LocalPlayer.Backpack
end)

RGBkatana.Name = "RGB katana"
RGBkatana.Parent = ScrollingFrame
RGBkatana.BackgroundColor3 = Color3.fromRGB(197, 197, 197)
RGBkatana.Position = UDim2.new(0.496621639, 0, 0.930723011, 0)
RGBkatana.Size = UDim2.new(0, 117, 0, 21)
RGBkatana.Font = Enum.Font.SourceSans
RGBkatana.Text = "RGB katana"
RGBkatana.TextColor3 = Color3.fromRGB(170, 0, 0)
RGBkatana.TextSize = 14.000
RGBkatana.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.RainbowKatana.Parent = game.Players.LocalPlayer.Backpack
end)

All.Name = "All"
All.Parent = Main
All.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
All.BorderColor3 = Color3.fromRGB(0, 0, 0)
All.Position = UDim2.new(0.0189035926, 0, 0.503455162, 0)
All.Size = UDim2.new(0, 200, 0, 44)
All.Font = Enum.Font.Roboto
All.Text = "Give all Items"
All.TextColor3 = Color3.fromRGB(170, 255, 0)
All.TextSize = 20.000
All.MouseButton1Down:connect(function()
	game.ReplicatedStorage.Tools.Shotgun.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.RainbowPanda.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.RainbowKatana.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.Popcorn.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.Pistol.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.Phone.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.VibeGuitar.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.ReaperScythe.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.VibeRifle.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.Camera.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.TommyGun.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.Flamethrower.Parent = game.Players.LocalPlayer.Backpack
	wait(0.3)
	game.ReplicatedStorage.Tools.GravityGun.Parent = game.Players.LocalPlayer.Backpack
end)

Label.Name = "Label"
Label.Parent = Main
Label.BackgroundColor3 = Color3.fromRGB(170, 255, 0)
Label.Position = UDim2.new(0.0189035926, 0, 0.808644235, 0)
Label.Size = UDim2.new(0, 200, 0, 11)
Label.Font = Enum.Font.SourceSans
Label.Text = "Made By Pizza Prime on yt"
Label.TextColor3 = Color3.fromRGB(0, 0, 0)
Label.TextSize = 14.000

Label_2.Name = "Label"
Label_2.Parent = Main
Label_2.BackgroundColor3 = Color3.fromRGB(170, 255, 0)
Label_2.Position = UDim2.new(0.0189035926, 0, 0.894938648, 0)
Label_2.Size = UDim2.new(0, 200, 0, 11)
Label_2.Font = Enum.Font.SourceSans
Label_2.Text = "More items coming soon"
Label_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Label_2.TextSize = 14.000

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
TextLabel.BackgroundTransparency = 3.000
TextLabel.Position = UDim2.new(0.12098299, 0, 0.0304568522, 0)
TextLabel.Size = UDim2.new(0, 76, 0, 24)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Vibe NYC"
TextLabel.TextColor3 = Color3.fromRGB(170, 0, 255)
TextLabel.TextSize = 28.000

TextLabel_2.Parent = TextLabel
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0, 0, 1, 0)
TextLabel_2.Size = UDim2.new(0, 113, 0, 20)
TextLabel_2.Font = Enum.Font.SciFi
TextLabel_2.Text = "Fucker"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 21.000

Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
Frame.BackgroundTransparency = 0.950
Frame.BorderColor3 = Color3.fromRGB(170, 85, 255)
Frame.Position = UDim2.new(0.0926276147, 0, 0.0203045681, 0)
Frame.Size = UDim2.new(0, 121, 0, 47)

-- Scripts:

local function CSGLHP_fake_script() -- Main.Search 
	local script = Instance.new('LocalScript', Main)

	local scroll = script.Parent.ScrollingFrame -- CHANGE THIS TO YOUR SCROLLING FRAME
	local textBox = script.Parent.TextBox -- CHANGE THIS TO YOUR TEXT BOX
	
	textBox.Changed:Connect(function() -- when the text is changed
		local text = textBox.Text:lower() -- lowercase search bar text
		if text ~= "" then -- if it has text
			local buttons = scroll:GetDescendants() -- all of the buttons
			for _, button in pairs(buttons) do -- loops through the buttons
				if button:IsA("TextButton") then -- if it's a button
					local buttonText = button.Text:lower() -- lowercase button text
					if string.find(buttonText, text) then -- if search bar text is found in the button's text
						button.Visible = true -- shows button
					else -- otherwise
						button.Visible = false -- hides button
					end
				end
			end
		else -- if it's empty
			local buttons = scroll:GetDescendants() -- all buttons
			for _, button in pairs(buttons) do -- loops through buttons
				if button:IsA("TextButton") then -- if it's a button
					button.Visible = true -- shows button
				end
			end
		end
	end)
end
coroutine.wrap(CSGLHP_fake_script)()
local function ELPCZ_fake_script() -- Main.Dragify 
	local script = Instance.new('LocalScript', Main)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.25), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent)
end
coroutine.wrap(ELPCZ_fake_script)()
