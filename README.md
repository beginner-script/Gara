-- ScreenGui와 TextLabel
local screenGui = Instance.new("ScreenGui", game.Players.LocalPlayer:WaitForChild("PlayerGui"))
local textLabel = Instance.new("TextLabel", screenGui)

textLabel.Size = UDim2.new(0.3, 0, 0.1, 0)
textLabel.Position = UDim2.new(0.35, 0, 0.45, 0)
textLabel.Text = "구란데"
textLabel.TextScaled = true
textLabel.BackgroundColor3 = Color3.new(1, 1, 1)
textLabel.TextColor3 = Color3.new(0, 0, 0)
