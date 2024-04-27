local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BackgroundTransparency = 0.200
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.319999993, 0, 0.0599999987, 0)
Frame.Size = UDim2.new(0.359261692, 0, 0.816377103, 0)

UICorner.CornerRadius = UDim.new(0, 10)
UICorner.Parent = Frame

ScrollingFrame.Parent = Frame
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
ScrollingFrame.BackgroundTransparency = 0.600
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.0293579102, 0, 0.56382978, 0)
ScrollingFrame.Size = UDim2.new(0.937614441, 0, 0.420972675, 0)

TextLabel.Parent = ScrollingFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0684931651, 0, -0.00161754177, 0)
TextLabel.Size = UDim2.new(0.502935529, 0, 0.0830455199, 0)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "ของที่จะทำ"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 58.000
TextLabel.TextWrapped = true
TextLabel.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_2.Parent = ScrollingFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.2465754, 0, 0.0703844428, 0)
TextLabel_2.Size = UDim2.new(0.502935529, 0, 0.0830455199, 0)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "ไม่บอก"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 255, 115)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 58.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.45688051, 0, 0.0683890879, 0)
TextLabel_3.Size = UDim2.new(0.460550725, 0, 0.144376919, 0)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Attack Hub"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 71.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.379816502, 0, 0.191489473, 0)
TextLabel_4.Size = UDim2.new(0.409174323, 0, 0.107902765, 0)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Kaitun"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 71.000
TextLabel_4.TextWrapped = true

TextLabel_5.Parent = Frame
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.614678919, 0, 0.182370886, 0)
TextLabel_5.Size = UDim2.new(0.48256886, 0, 0.126139849, 0)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "PC"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 71.000
TextLabel_5.TextWrapped = true

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.0462815575, 0, 0.110670708, 0)
ImageLabel.Size = UDim2.new(0.288529366, 0, 0.188721448, 0)
ImageLabel.Image = "http://www.roblox.com/asset/?id=16663324629"
local function RMQMU_fake_script()
	local script = Instance.new('LocalScript', Frame)

	local TweenService = game:GetService("TweenService")
	
	local function MakeDraggable(object)
		local mouseDown = false
		local dragStart = nil
		local startPos = nil
	
		object.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				mouseDown = true
				dragStart = input.Position
				startPos = object.Position
			end
		end)
	
		object.InputEnded:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				mouseDown = false
			end
		end)
	
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement then
				if mouseDown then
					local delta = input.Position - dragStart
					local newPos = UDim2.new(
						startPos.X.Scale,
						startPos.X.Offset + delta.X,
						startPos.Y.Scale,
						startPos.Y.Offset + delta.Y
					)
					local tweenInfo = TweenInfo.new(0.1)
					local tween = TweenService:Create(object, tweenInfo, {Position = newPos})
					tween:Play()
				end
			end
		end)
	end
	
	MakeDraggable(script.Parent)
end
coroutine.wrap(RMQMU_fake_script)()
