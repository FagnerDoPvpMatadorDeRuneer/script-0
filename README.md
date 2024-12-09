--carregando biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Fagnerdopvp " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Menu" }),
}
-- parágrafos 
Tabs.Main:AddParagraph({ Title = "Game scripts", Content = "Scripts" })
-- botões 
Tabs.Main:AddButton({ Title = "Fly", Callback = function()
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
end })

Tabs.Main:AddButton({ Title = "Fling", Callback = function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_5wpM7bBcOPspmX7lQ3m75SrYNWqxZ858ai3tJdEAId6jSI05IOUB224FQ0VSAswH.lua.txt'),true))()
end })

Tabs.Main:AddButton({ Title = "Admin", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
 end })

Tabs.Main:AddButton({ Title = "Dances", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Animation-Hub/main/Animation%20Gui", true))()
end })

Tabs.Main:AddButton({ Title = "Airswin", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/HeyGyt/airswim/main/main"))()
 end })
 
 Tabs.Main:AddButton({ Title = "Brookhaven🏡", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
 end })
 
 Tabs.Main:AddButton({ Title = "MM2🔪🔪", Callback = function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()
 end })
 
 Tabs.Main:AddButton({ Title = "Bedwars🛏⚔", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()	
 end })
 
 local Tabs = {
    Main = Window:AddTab({ Title = "Menu script part 2" }),
}

Tabs.Main:AddButton({ Title = "Life in prison ", Callback = function()
loadstring(game:HttpGet('https://pastebin.com/raw/iZ64yzjE'))()
end })

Tabs.Main:AddButton({ Title = "Muscle Legends 💪", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/ESP-Script/main/ESP.lua"))()
 end })
 
 Tabs.Main:AddButton({ Title = "Evade", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Evade"))()
 end })
 
 Tabs.Main:AddButton({ Title = "Fisch🎣", Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Fisch-Speed-Hub-X-No-Key-Free-21187"))()
 end })
