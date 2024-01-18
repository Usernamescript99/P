--Loads
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

--Main
local Window = OrionLib:MakeWindow({Name = "KING SCRIPTS (BETA 1.0)", HidePremium = false, SaveConfig = true, ConfigFolder = "kk",IntroText = "KING SCRIPTS"})

--Tab
local Tab = Window:MakeTab({
	Name = "Tab Blox fruits",
	Icon = "rbxassetid://14400409576",
	PremiumOnly = false
})
 
local Section = Tab:AddSection({
	Name = "Blox fruite scripts Free"
})

Tab:AddButton({
	Name = "Lore Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/GoblinKun009/Script/main/loreloader"))()
	  
  	end    
})

 Tab:AddButton({
	Name = "Maris Hub",
	Callback = function()
	  loadstring(game:HttpGet('https://raw.githubusercontent.com/marisdeptrai/Script-Free/main/Maris-Hub'))()
	  
  	end    
})

 Tab:AddButton({
	Name = "Min Hub",
	Callback = function()
	  loadstring(game:HttpGet"https://raw.githubusercontent.com/Basicallyy/Basicallyy/main/Min_XT_V2_.lua")()
	  
  	end    
})

 Tab:AddButton({
	Name = " APPLE HUB",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/ImTienNguyenZ/ImTienNguyenZ/main/obf_lc8NZP74x7Y0j6TZs4B8c2EF93mtOpRQZkarI3R8GiBRedSlkA2293QygddzqIWU.lua"))()
	  
  	end    
})

 Tab:AddButton({
	Name = "Mitien Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/ImTienNguyenZ/MTienHub/main/Loader.lua"))()
	  
  	end    
})

 Tab:AddButton({
	Name = "Makori Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/NewHubX.txt"))()
	  
  	end    
})

Tab:AddButton({
	Name = " Chest Farm Hub",
	Callback = function()
	  _G.Chest_Farm = true
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Zekrom-Hub-X/main/Zekrom-Hub-X-exe", true))()
	  
  	end    
})

Tab:AddButton({
	Name = "Xero Hub",
	Callback = function()
	  getgenv().Team = "Pirates"
loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/main/main.lua"))()
	  
  	end    
})

Tab:AddButton({
	Name = "Annie Hub",
	Callback = function()
	  loadstring(game:HttpGet('https://raw.githubusercontent.com/1st-Mars/Annie/main/1st.lua'))()
	  
  	end    
})

Tab:AddButton({
	Name = "W-AZURE V2 Hub",
	Callback = function()
	  getgenv().Team = "Pirates"
getgenv().FixCrash = false
getgenv().FixCrash2 = false
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
	  
  	end    
})

Tab:AddButton({
	Name = "Zen Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/ZenHubTheBest/Main/main/Loader", true))()
	  
  	end    
})



Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
	  
  	end    
})

Tab:AddButton({
	Name = " Raito Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))()
	  
  	end    
})

Tab:AddButton({
	Name = "MTritet Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
	  
  	end    
})

 Tab:AddButton({
	Name = "Perd Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/PerdHub/Blosfruitscript/main/PerdLoader"))()
	  
  	end    
})

Tab:AddButton({
	Name = "Fai Fao Hub",
	Callback = function()
	  loadstring(game:HttpGet"https://raw.githubusercontent.com/PNguyen0199/Script/main/Fai-Fao-Ver2.lua")()
	  
  	end    
})

Tab:AddButton({
	Name = "Vector Hub",
	Callback = function()
	  _G.Mode = "English"
loadstring(game:HttpGet("https://raw.githubusercontent.com/Tuxoz/VectorHub/main/MBPC"))()
	  
  	end    
})

 Tab:AddButton({
	Name = "ZEKROM Hub",
	Callback = function()
	   loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Zekrom-Hub-X/main/Zekrom-Hub-X-exe", true))()
	  
  	end    
})

 Tab:AddButton({
	Name = "Full Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Fiend1sh/FiendMain/main/Fullloader"))()
	  
  	end    
})

Tab:AddButton({
	Name = "OMYG Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Omgshit/Scripts/main/MainLoader.lua"))()
	  
  	end    
})

Tab:AddButton({
	Name = " Uranium Hub",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Augustzyzx/UraniumMobile/main/UraniumKak.lua"))()
	  
  	end    
})



local Section = Tab:AddSection({
	Name = "Galera Depois vai ter mais script"
})

local Tab = Window:MakeTab({
	Name = "Tab scriptSpeed",
	Icon = "rbxassetid://14400409576",
	PremiumOnly = false
})

 Tab:AddButton({
	Name = "Speed Test (No key)",
	Callback = function()
	  loadstring(game:HttpGet("https://raw.githubusercontent.com/Usernamescript99/SPEED.TRUE/main/Speedfreescripts%2520"))()
	  
  	end    
})
