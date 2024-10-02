local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()
local window = DrRayLibrary:Load("Games", "Default")

local tab = DrRayLibrary.newTab("Blox fruit", "ImageIdHere")

tab.newButton("REDZ HUB", "Click to use", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/REDzHUB/main/REDzHUB"))()
end)

tab.newButton("HOHO HUB V4", "Click to use", function()
    
end)

tab.newButton("COOKA HUB", "Click to use", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/UserDevEthical/Loadstring/main/CokkaHub.lua")()
end)


tab.newButton("VECTOR HUB", "Click to use", function()
    _G.Mode = "Eng"
loadstring(game:HttpGet("https://raw.githubusercontent.com/AAwful/VectorHub/main/Loader.lua"))()
end)


tab.newButton("OMG HUB", "Click to use", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Omgshit/Scripts/main/MainLoader.lua"))()
end)

tab.newButton("HUTAO V2", "Click to use", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/HutaoHubs/Hutaohubs2.0/refs/heads/main/Bloxfruit2.lua'))()
end)

tab.newButton("PANDA FRUIT", "Click to use", function()
    SpeedTween = 300
getgenv().RandomFruit = true
getgenv().EspFruit = true
getgenv().Team = "Marines"
getgenv().WebhookUrl = ''
loadstring(game:HttpGet('https://raw.githubusercontent.com/VNT-UNIVERSAL/Panda-Hub/main/Release/fruitfarm.lua'))()
end)

tab.newButton("MIN BLUE 2", "Click to use", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LuaCrack/Min/refs/heads/main/MinAPEng"))()
end)

tab.newButton("TSUO HUB BETA", "Click to use", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Tsuo7/TsuoHub/main/Tsuoscripts"))()
end)

tab.newButton("HIRU HUB", "Click to use", function()
    getgenv().Team = "Pirates"
getgenv().AntiCrash = false
getgenv().BoostFps = false
loadstring(game:HttpGet("https://raw.githubusercontent.com/NGUYENVUDUY1/Super/main/HiruDone.lua"))()
end)

tab.newButton("ZEN HUB NEXT GEN", "Click to use", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Zenhubtop/zen_hub_pr/main/zennewwwwui.lua", true))()
end)
