local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/NiceBBMBThai12/NBTScript/main/UI-Library-Robloxx"))()
local window = library:Win()
local tap1 = window:addtap("Tab1")
local tap2 = window:addtap("Tab2")
local page1 = tap1:addpage()
local page2 = tap1:addpage()
local page3 = tap1:addpage()
local page4 = tap1:addpage()
page1:Ti("GODMICK")

page1:Button1("Fishing rod", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-113.459351, 254.699951, 813.771179, 0.735317647, 1.04872619e-07, -0.677722633, -6.76540992e-08, 1, 8.13391239e-08, 0.677722633, -1.39593777e-08, 0.735317647)
end)
page1:Button1("Stage", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-160.295258, 255.715225, 644.689636, -1.1920929e-07, 0, -1.00000012, 0, 1, 0, 1.00000012, 0, -1.1920929e-07)
end)
page1:Button1("Ship", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-174.743225, 244.580948, 855.642334, -0.984812617, 0, 0.173621148, 0, 1, 0, -0.173621148, 0, -0.984812617)
end)
page1:Button1("Bed in the house 1", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(108.305069, 253.520065, 755.564819, 0.86313206, 0, -0.50497824, 0, 1, 0, 0.50497824, 0, 0.86313206)
end)
page1:Button1("Bed in the house 2", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(9.98181438, 263.329987, 797.558044, 0.999983788, 0, -0.00569722941, 0, 1, 0, 0.00569722941, 0, 0.999983788)
end)    
page1:Button1("Bed outside", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(96.6850128, 251.740005, 736.951111, -0.342042685, 0, -0.939684391, 0, 1, 0, 0.939684391, 0, -0.342042685)
end)
page1:Button1("Sit and play", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-140.792374, 253.346268, 764.486877, -0.667493224, -0.000114017515, -0.74461633, -4.36232804e-05, 1, -0.000114017515, 0.74461633, -4.36232804e-05, -0.667493224)
end)
page1:Button1("lie down and play", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-161.921722, 253.729294, 754.191345, 0.90629667, 0, 0.422642082, 0, 1, 0, -0.422642082, 0, 0.90629667)
end)
local getdrop = page2:DropDown("Player Name","Name",{"???????????????????????????????????????","??????????????????????????????????????????????????????"}, function(value)
    print(value)
end)
page2:Button("TELEPORT PLAYER", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[PlayerTP].Character.HumanoidRootPart.CFrame
end)
page2:Toggle("WalkSpeed",nil, function(value)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)
page2:Toggle("Jumpower",nil, function(value)
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/miczzaa1156/Jum/main/README.md'),true))()
end)
page2:Button("Noclip", function(value)
    loadstring(game:HttpGet("https://raw.githubusercontent.com/miczzaa1156/page2-Toggle-Jumpower-nil-function-value-/main/README.md"))();
end)        
    
page3:Ti("V2")
page3:Button1("Stage", function(value)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-215.702072, 311.071106, 1005.67432, 0.575435758, 0.0215789005, -0.817562401, -2.43159011e-05, 0.999652326, 0.0263679121, 0.817847073, -0.015153164, 0.575236201)
end)



    
    
