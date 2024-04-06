local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "IDK HUB (beta)", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <IDK HUB> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <https://www.google.co.th/search?client=ms-opera-mobile&sca_esv=8ca988cea1190486&sca_upv=1&channel=new&espv=1&q=idk&uds=AMwkrPs3luxm7TPdKExM6orO6npGi8zbOQc7aP59swoPvHQ6JmN2uYPGquZzrK0-g5QbpLrShdxufmHWmBrKgRsD-qtNXZxlRI6MIdlL4i6cUOt-BWOEEOlbLRa6mg-J0qhBZPW-hd0ZHVixXWqClAZpo42RBHOx3_In1aW-xw52sU4mw0wkfs3ptlSYb7S-6s-TR6J8004kophO3nMPkxa2nL-hO-7pFXrNtIsGhiWqkXUP9vc5Ta2HQEkrm5m36IZ1W88kpiifNkBHVmt7VayaWHx3C_kSD44yskA2kEf2WWaKqnmra91cVeK5Zofbo2dfGWSfN-yl05dBWnPK5ZBNn7fT0XJZ2Yy1OaFymfO8sevG378kgvyb9BvJ3dolRS5i5MiSO58X&udm=2&prmd=ivsnbmtz&sa=X&ved=2ahUKEwjeko7ZuK2FAxV54DgGHcP1CjsQtKgLegQIEBAB#vhid=Ht9IGdSnlcAWoM&vssid=mosaic> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]
local Tab = Window:MakeTab({
    Name = "NPC farm",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]
local Section = Tab:AddSection({
    Name = "แนะนำให้กดสองครั้งครับ อย่าใช้ถี่ระวังโดนเตะ"
})

--[[
Name = <string> - The name of the section.
]]
Tab:AddButton({
    Name = "GET YA รีตัวแล้วรอเกิดใหม่จะมีวงสีฟ้าให้กดใช้เลย!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-661.004211, 1509.49292, -1494.53589, 1, 0, 0, 0, 1, 0, 0, 0, 1)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "SELL YA มีบัควาปกลับที่เดิมอย่ากดรัว!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1062.04126, 1509.40002, -1447.75647, -1.1920929e-07, -0, -1.00000012, 0, 1, 0, 1.00000012, 0, -1.2920929e-07)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
local Tab = Window:MakeTab({
    Name = "NPC อาวุธ",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]
local Section = Tab:AddSection({
    Name = "ก่อนใช้ให้รีตัวมีวงสีฟ้าก่อน เพราะถ้าไม่มีมันจะวาปกลับ"
})

--[[
Name = <string> - The name of the section.
]]
Tab:AddButton({
    Name = "Ebo1!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-986.533997, 1509.40002, -1399.70544, 1, 0, 0, 0, 1, 0, 0, 0, 1)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "ปืนปากกา!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-588.900024, 1509.40002, -1539.99988, 0, 0, -1, 0, 1, 0, 1, 0, 0)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "บาเร็ตต้า!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-365.306519, 1509.40002, -1524.92407, 0, 0, 1, 0, 1, -0, -1, 0, 0)
      end
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "Katana!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-739.200012, 1509.40002, -1562.30005, 0, 0, -1, 0, 1, 0, 1, 0, 0)
      end
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "สปาต้า!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1140.00916, 1509.58533, -1884.70874, 0, 0, 1, 0, 1, -0, -1, 0, 0)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "มีดหัวตัด!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-980.862244, 1509.58533, -1894.09045, 1, 0, 0, 0, 1, 0, 0, 0, 1)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "ง้าว!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-636.827332, 1509.58533, -2037.40125, -1, 0, 0, 0, 1, 0, 0, 0, -1)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "มีดผ่าแตง!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-386.605438, 1509.40002, -2013.69995, 1, 0, 0, 0, 1, 0, 0, 0, 1)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "มีดปังตอ!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-596.236328, 1510.04211, -2062.3125, 0, 0, 1, 0, 1, -0, -1, 0, 0)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
    Name = "แหนบยาว!",
    Callback = function()
              game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-544.325256, 1509.58533, -1680.72021, 0, 0, -1, 0, 1, 0, 1, 0, 0)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
