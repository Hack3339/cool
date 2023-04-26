local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "CON HUB😳😳", HidePremium = false, IntroText = "CON HUB😳😳",  SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({

    Name = "TP👽🗿",

    Icon = "rbxassetid://4483345998",

    PremiumOnly = false

})

OrionLib:MakeNotification({

    Name = "LOL",

    Content = "มีแค่TP",

    Image = "rbxassetid://4483345998",

    Time = 5

})

Tab:AddButton({

    Name = "เกาะแรก",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(17.21052360534668, 13.341556549072266, -35.65540313720703)

      end    

})

Tab:AddButton({

    Name = "เกาะทราย",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-671.7678833007812, 7.915792942047119, 1137.715576171875)

      end    

})

Tab:AddButton({

    Name = "เกาะหิมะ",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1629.9794921875, 4.422079086303711, 3132.015625)

      end    

})

Tab:AddButton({

    Name = "เกาะมิฮอค",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3754.80810546875, 10.37023639678955, 3087.788818359375)

      end    

})

Tab:AddButton({

    Name = "เกาะโมอาย",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3800.990478515625, 42.100284576416016, -780.10400390625)

      end    

})

Tab:AddButton({

    Name = "เกาะทรายV2",

    Callback = function()

           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6494.5029296875, 7.915792942047119, 1859.818359375)   

      end    

})

Tab:AddButton({

    Name = "เกาะ2ดาบ",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1130.2940673828125, 21.978538513183594, -3154.31689453125)

      end    

})

Tab:AddButton({

    Name = "มารีนฟอร์ด",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4980.10595703125, 60.268104553222656, -1257.6693115234375)

      end    

})

Tab:AddButton({

    Name = "เกาะเดมอน",

    Callback = function()

              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4015.685791015625, 30.512937545776367, -7066.4306640625)

      end    

})

OrionLib:Init()
