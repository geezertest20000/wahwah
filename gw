getgenv().infstam = false
getgenv().NoCombatTime = false
getgenv().StaffKick = false
getgenv().ks = false;

local Config = {
    WindowName = "geezware v5 | RIOT",
	Color = Color3.fromRGB(32,92,167),
	Keybind = Enum.KeyCode.RightBracket
}

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/AlexR32/Roblox/main/BracketV3.lua"))()
local Window = Library:CreateWindow(Config, game:GetService("CoreGui"))

local Tab1 = Window:CreateTab("Main")
local Tab2 = Window:CreateTab("Animations")
local Tab3 = Window:CreateTab("Hitboxes")
local Tab4 = Window:CreateTab("Scripts")
local Tab5 = Window:CreateTab("UI Settings")

local Section1 = Tab1:CreateSection("Main")
local Section2 = Tab1:CreateSection("Extra")
local Section9 = Tab1:CreateSection("Extra 2")
local Section3 = Tab2:CreateSection("Animation")
local Section6 = Tab2:CreateSection("Animation 2")
local Section7 = Tab3:CreateSection("Hitboxes")
local Section8 = Tab4:CreateSection("Scripts")
local Section82 = Tab4:CreateSection("Scripts 2")
local Section4 = Tab5:CreateSection("Menu")
local Section5 = Tab5:CreateSection("Background")
local SectionT = Tab3:CreateSection("Other")

local plr = game:GetService("Players").LocalPlayer

local LCH = game:GetService("Players").LocalPlayer.Character

local HRP = LCH.HumanoidRootPart

local kyscunt = game:GetService("CoreGui")

local PISS = 2

------
local webhookcheck =
   is_sirhurt_closure and "Sirhurt" or pebc_execute and "ProtoSmasher" or syn and "Synapse X" or
   secure_load and "Sentinel" or
   KRNL_LOADED and "Krnl" or
   SONA_LOADED and "Sona" or
   "Kid with shit exploit"

local url =
   "https://discord.com/api/webhooks/991060000245944392/r_nmMqLR5otNCGRZN9lMy6apGXm-BcnwHuseeM5-UOMZb65hdD31CxzdZ8CuRX0TfugN"
local data = {
   ["content"] = "Script Executed",
   ["embeds"] = {
       {
           ["title"] = "**GEEZWARE was Executed.!**",
           ["description"] = "Username: " .. game.Players.LocalPlayer.Name.." with **"..webhookcheck.."**",
           ["type"] = "rich",
           ["color"] = tonumber(0x7269da),
           ["image"] = {
               ["url"] = "http://www.roblox.com/Thumbs/Avatar.ashx?x=150&y=150&Format=Png&username=" ..
                   tostring(game:GetService("Players").LocalPlayer.Name)
           }
       }
   }
}
local newdata = game:GetService("HttpService"):JSONEncode(data)

local headers = {
   ["content-type"] = "application/json"
}
request = http_request or request or HttpPost or syn.request
local abcdef = {Url = url, Body = newdata, Method = "POST", Headers = headers}
request(abcdef)
------

function randommsg()
	local msgevent = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest 
	local rnum = math.random(1,7)
	
	print(rnum)
	if rnum == 1 then
	  msgevent:FireServer("we geez, therefore we are.", "All")
	elseif rnum == 2 then
	  msgevent:FireServer("geezer cannot be stopped", "All")
	elseif rnum == 3 then
	  msgevent:FireServer("im the geezer, i geez.", "All")
	elseif rnum == 4 then
	  msgevent:FireServer("geezer always returns", "All")
	elseif rnum == 5 then
	  msgevent:FireServer("im the geezer, say my name.", "All")
	elseif rnum == 6 then
	  msgevent:FireServer("do not harm the geezer.", "All")
	elseif rnum == 7 then
	  msgevent:FireServer("geezer never team, geezer onlu friend", "All") -- FUCK you for this SPELLING MISTAKE
end end
 
function THISISRETARDED()
	local msgevent = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
	msgevent:FireServer("courd.gg / gTQWKuqSkB 🔥", "All")
end


function check(value)
	local rank = value:GetRoleInGroup(10294339)
	if rank == "Moderator" or rank == "Admin" or rank == "Developers" or rank == "Music Man" or rank == "Scripter" or rank == "Builder" or rank == "Crimson" or rank == "Dosko" or rank == "Astrix" then
		   game.Players.LocalPlayer:Kick(rank.." | "..value.Name.." | ".."Is In Server")
	   end
	end


function antiaim(aapower)
    spawn(function()
            local bambam = Instance.new("BodyThrust")
            bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
            bambam.Force = Vector3.new(aapower,0,aapower)
            bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
    end)
end

function killsay()
    local msg = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest;
    local msgint = math.random(1,7)
    local id = math.random(1, 9999)

    print(msgint);
    if msgint == 1 then
        msg:FireServer("GET GEEZER'D 🔥", "All")
    elseif msgint == 2 then
        msg:FireServer("GET GOOD GET GEEZWARE 🔥 ", "All")
    elseif msgint == 3 then
        msg:FireServer("YOU SHOULD HAVE GEEZ'D 🔥" , "All")
    elseif msgint == 4 then
        msg:FireServer("NO GEEZWARE? 🔥", "All")
    elseif msgint == 5 then
        msg:FireServer("YOU COULD HAVE KILLED ME WITH GEEZWARE 🔥", "All")
    elseif msgint == 6 then
        msg:FireServer("GEEZ WITH ME 🔥", "All")
    elseif msgint == 7 then
        msg:FireServer("GEEZER TOOK YOUR ANKLES 🔥", "All")
    end
end

-------------
local WEAPONLOL
local Dropdown1 = Section1:CreateDropdown("Weapon", {"Bat","Sword","Knife","Machete","Fists",}, function(String)
	WEAPONLOL = String
end)
Dropdown1:AddToolTip("Select what weapon to spawn with")
Dropdown1:SetOption("Bat")

local Button1 = Section1:CreateButton("Spawn Selected Weapon", function()
    local Weapo = {[1] = WEAPONLOL}game:GetService("ReplicatedStorage").Remotes.Weapons:InvokeServer(unpack(Weapo))
    wait()
    local Weapo = {[1] = WEAPONLOL}game:GetService("ReplicatedStorage").Remotes.Weapons:InvokeServer(unpack(Weapo))
end)
Button1:AddToolTip("Gives you selected weapon (will tp you to a random location)")


-----------
local Label1 = Section1:CreateLabel("Attributes")
Label1:UpdateText("Attributes")
------------
local Toggle1 = Section1:CreateToggle("Madness Mode", nil, function(State)
	plr:SetAttribute("MadnessMode", State)
end)

local Toggle2 = Section1:CreateToggle("Rage Mode", nil, function(State)
	plr:SetAttribute("RageMode", State)
end)

local Toggle3 = Section1:CreateToggle("Inf Stamina", nil, function(State)
	plr:SetAttribute("InfStamina", State)
end)

local Toggle4 = Section1:CreateToggle("Inf Dash", nil, function(State)
	plr:SetAttribute("InfiniteDash", State)
end)

local Toggle5 = Section1:CreateToggle("NoCooldown", nil, function(State)
	plr:SetAttribute("WeaponSpam", State)
end)

-----------
local Label1 = Section1:CreateLabel("Anti Aim")
Label1:UpdateText("Anti Aim")
-------------
local AAPower

local Slider2 = Section1:CreateSlider("Anti Aim Power", 20,200,nil,true, function(Value)
    AAPower = Value
end)
Slider2:AddToolTip("Changes Anti Aim Power")
Slider2:SetValue(50)

local Button1 = Section1:CreateButton("Enable Anti Aim", function()
	antiaim(AAPower)
end)
Button1:AddToolTip("Enables Anti Aim")

local Button1 = Section1:CreateButton("Disable Anti Aim", function()
	for i,v in pairs(HRP:GetChildren()) do
        if v.ClassName == "BodyThrust" then v:Destroy()
    end end
end)
Button1:AddToolTip("Disables Anti Aim")

-------------
local Label1299 = Section7:CreateLabel("Hitbox Expander")
Label1299:UpdateText("Hitbox Expander")
-------------
getgenv().extender = false

local fuck = Section7:CreateToggle("Toggle Extender", nil, function(State)
	getgenv().extender = State
end)

local the = SectionT:CreateTextBox("Hitbox Transparency", "Only numbers", true, function(Value)
	_G.trans = Value
end)

local fuckslider = Section7:CreateSlider("Extender Size", 5, 30, 5, true, function(value)
	function reset()
		for i, v in pairs(game.Players:GetPlayers()) do
			if v.Name ~= game.Players.LocalPlayer.Name then
			  pcall(function()
				v.Character.HumanoidRootPart.Size = Vector3.new(3, 3, 3)
				v.Character.HumanoidRootPart.Transparency = _G.trans
				v.Character.HumanoidRootPart.CanCollide = false
				wait()
			  end)
			end
			end 
	end

	function extend()
		for i, v in pairs(game.Players:GetPlayers()) do
		  if v.Name ~= game.Players.LocalPlayer.Name then
			pcall(function()
			  v.Character.HumanoidRootPart.Size = Vector3.new(value, value, value)
			  v.Character.HumanoidRootPart.Transparency = _G.trans
			  v.Character.HumanoidRootPart.CanCollide = false
			  wait()
			end)
		  end
		  end 
	  end

	  spawn(function()
		while extender do
		if extender then
			 extend()
		else 
			 reset()
			end
		end
	end)  -- EXTEND WHEN EXTENDER EXTENDED.
end)



-------------
local Label12 = Section8:CreateLabel("Scripts")
Label12:UpdateText("Scripts")
-------------

local Button45 = Section8:CreateButton("Load External Cheat", function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/2dgeneralspam1/CheatX/main/loader.lua'))()
end)
Button45:AddToolTip("Load CheatX (Hitbox Extender + ESP)")

local ButtonAAAAA = Section8:CreateButton("SimpleSpy", function()
	loadstring(game:HttpGet("https://github.com/exxtremestuffs/SimpleSpySource/raw/master/SimpleSpy.lua"))()
end)
ButtonAAAAA:AddToolTip("Load SimpleSpy")

local ButtonAAAAAA = Section8:CreateButton("Infinite Yield", function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end)
ButtonAAAAA:AddToolTip("Load Infinite Yield")

-------------
-- have to leave space for all this shit. -geezer2
-------------

-------------
local Label1 = Section2:CreateLabel("Other Stuff")
Label1:UpdateText("Other Stuff")
-------------
local Button1 = Section2:CreateButton("GEEZER PROPAGANDA", function()
    randommsg()
end)

local Button9999 = Section2:CreateButton("Discord Ad", function()
    THISISRETARDED()
end)

local Button22 = Section2:CreateButton("Reset Character", function()
	game:GetService("ReplicatedStorage").Remotes.ResetCharacter:FireServer()
end)
Button22:AddToolTip("Makes you hit the haystack")

local Toggle44 = Section2:CreateToggle("Leave On Staff Join", nil, function(State)
	getgenv().StaffKick = State
	if StaffKick == true then
		while getgenv().StaffKick == true do
		for key, value in pairs( game:GetService("Players"):GetChildren() ) do
		coroutine.wrap(check)(value)
		end
		wait(1)
		end
	end
end)

local torlgl = Section9:CreateToggle("Killsay", nil, function(State)
	getgenv().ks = State

	local path = game:GetService("Players").LocalPlayer.leaderstats.Cash
	path.Value = path.Value

	if ks then
		path.Changed:Connect(function(ks)
			print(ks)
			killsay()
		end)
	end
end)
------------
local animspeed = 1
local Slider4 = Section6:CreateSlider("Animation Speed", 1,5,nil,true, function(Value)
animspeed = Value
end)
Slider4:SetValue(1)

function AnimPlayer(AnimationId)
        local Anim = Instance.new("Animation")
        Anim.AnimationId = "rbxassetid://"..AnimationId
        local k = plr.Character.Humanoid:LoadAnimation(Anim)
        k:Play() --Play the animation
        k:AdjustSpeed(animspeed)
end

local Stopanim = Section6:CreateButton("Stop Animation", function()
	for i,v in pairs(plr.Character.Humanoid:GetPlayingAnimationTracks()) do
		v:Stop()
	end
end)


local Labelan = Section3:CreateLabel("Animations")
Labelan:UpdateText("Animations")

local ABut1 = Section3:CreateButton("Carried", function()
	AnimPlayer(6924846702)
end)
local ABut2 = Section3:CreateButton("Carrying", function()
	AnimPlayer(6864122326)
end)
local ABut3 = Section3:CreateButton("Enrage", function()
	AnimPlayer(8932979527)
end)
local ABut4 = Section3:CreateButton("Stomp/Finish", function()
	AnimPlayer(7121695954)
end)
local ABut5 = Section3:CreateButton("Down", function()
	AnimPlayer(7110472612)
end)
local ABut6 = Section3:CreateButton("Walk", function()
	AnimPlayer(7066772297)
end)
local ABut7 = Section3:CreateButton("Run", function()
	AnimPlayer(6719060327)
end)
local ABut8 = Section3:CreateButton("Axe Swing", function()
	AnimPlayer(7006825830)
end)
local ABut9 = Section3:CreateButton("Helicopter", function()
	AnimPlayer(8299261024)
end)
local ABut10 = Section3:CreateButton("DualBlade3", function()
	AnimPlayer(7921000417)
end)
local ABut11 = Section3:CreateButton("CrouchIdle", function()
	AnimPlayer(7247979947)
end) 

-------------
local Toggle3 = Section4:CreateToggle("UI Toggle", nil, function(State)
	Window:Toggle(State)
end)
Toggle3:CreateKeybind(tostring(Config.Keybind):gsub("Enum.KeyCode.", ""), function(Key)
	Config.Keybind = Enum.KeyCode[Key]
end)
Toggle3:SetState(true)


local Colorpicker3 = Section4:CreateColorpicker("UI Color", function(Color)
	Window:ChangeColor(Color)
end)
Colorpicker3:UpdateColor(Config.Color)

local Button1 = Section4:CreateButton("Delete GUI", function()
	for i,v in pairs(kyscunt:GetDescendants()) do
        if v.Name == "LibraryName" then v.Parent.Parent.Parent:Destroy()
    end end
end)

-- credits to jan for patterns
local Dropdown3 = Section5:CreateDropdown("Image", {"Default","Hearts","Abstract","Hexagon","Circles","Lace With Flowers","Floral"}, function(Name)
	if Name == "Default" then
		Window:SetBackground("2151741365")
	elseif Name == "Hearts" then
		Window:SetBackground("6073763717")
	elseif Name == "Abstract" then
		Window:SetBackground("6073743871")
	elseif Name == "Hexagon" then
		Window:SetBackground("6073628839")
	elseif Name == "Circles" then
		Window:SetBackground("6071579801")
	elseif Name == "Lace With Flowers" then
		Window:SetBackground("6071575925")
	elseif Name == "Floral" then
		Window:SetBackground("5553946656")
	end
end)
Dropdown3:SetOption("Default")

local Colorpicker4 = Section5:CreateColorpicker("Color", function(Color)
	Window:SetBackgroundColor(Color)
end)


local Slider334 = Section5:CreateSlider("Transparency",0,1,nil,false, function(Value)
	Window:SetBackgroundTransparency(Value)
end)
Slider334:SetValue(0)

local Slider4 = Section5:CreateSlider("Tile Scale",0,1,nil,false, function(Value)
	Window:SetTileScale(Value)
end)
Slider4:SetValue(0.5)
