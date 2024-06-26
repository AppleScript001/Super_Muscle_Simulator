local Library = loadstring(game:HttpGet("https://pastebin.com/raw/KNBp0LRy"), "Coastified UI")()
repeat wait() until game:IsLoaded()
game:GetService("Players").LocalPlayer.Idled:connect(function()
game:GetService("VirtualUser"):ClickButton2(Vector2.new())
end)
local Window = Library:NewWindow("Super Muscle Simulator")

local Section = Window:NewSection("AutoFarm")

local Toggle = Section:CreateToggle("Auto INF [Muscle]", function(Value)
_G.Muscle = Value
while _G.Muscle do
wait()  -- Wait for 1 second before checking for enemies
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Lift Weight"):FireServer("Mountain")
    end
end)
local Toggle = Section:CreateToggle("Auto [Rebirth]", function(Value)
_G.reb = Value
while _G.reb do
wait(0.1)  -- Wait for 1 second before checking for enemies
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Rebirth"):FireServer()
    end
end)
local Section = Window:NewSection("Extra")
local Toggle = Section:CreateToggle("Auto [Get_Gift_All]", function(Value)
_G.gift = Value
while _G.gift do
wait(1)  -- Wait for 1 second before checking for enemies
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(1)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(2)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(3)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(4)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(5)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(6)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(7)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(8)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(9)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(10)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(11)
wait(0.1)
game:GetService("ReplicatedStorage"):WaitForChild("Packages"):WaitForChild("Network"):WaitForChild("RemoteEventStorage"):WaitForChild("Claim Gift"):FireServer(12)
end
end)
