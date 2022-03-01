
xwd = game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId)
Gamename = xwd.Name
local games = {
[game.PlaceId] = {
    Title = "Blox Fruits",
    Icons = "",
    Welcome = function()
            return tostring(
            " "
                ..

                        Gamename.. "!" .. " Magic X]"  .."\n Loadded Succesfully dev script by RO OD #9999 And Beam#2017"
            )
    end
}
}
if games[game.PlaceId] then	
if games[game.PlaceId].Title == "Blox Fruits" then
    local function notify(types, ...)
            if types == "Notify" then
            require(game.ReplicatedStorage.Notification).new(...):Display()
            end
    end
    notify("Notify", games[game.PlaceId].Welcome())
end
end

wait(1.1)

game.StarterGui:SetCore("SendNotification", {
    Icon = "";
    Title = "Magic X HUB", 
    Text = "Check PC :)"
})

wait(2.4)

game.StarterGui:SetCore("SendNotification", {
    Icon = "";
    Title = "Magic X", 
    Text = "Yeah Magic X ON TOP"
})

wait(1)
    if _G.Team == "Pirate" then
        for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.MouseButton1Click)) do
            v.Function()
        end
    elseif _G.Team == "Marine" then
        for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.MouseButton1Click)) do
            v.Function()
        end
    else
        for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.MouseButton1Click)) do
            v.Function()
        end
    end
wait(1)
local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("Magic X")

local serv = win:Server("main","")

local btns = serv:Channel("Auto-Farm")

local placeId = game.PlaceId
if placeId == 2753915549 then
	OldWorld = true
elseif placeId == 4442272183 then
	NewWorld = true
elseif placeId == 7449423635 then
	ThreeWorld = true
end

function CheckQuest()
	local MyLevel = game.Players.LocalPlayer.Data.Level.Value
	if OldWorld then
		if MyLevel == 1 or MyLevel <= 9 then 
			Ms = "Bandit [Lv. 5]"
			NaemQuest = "BanditQuest1"
			LevelQuest = 1
			NameMon = "Bandit"
			CFrameQuest = CFrame.new(1061.66699, 16.5166187, 1544.52905)
			PosQuest = Vector3.new(1061.66699, 16.5166187, 1544.52905)
			CFrameMon = CFrame.new(1199.31287, 52.2717781, 1536.91516)
			PosMon = Vector3.new(1199.31287, 52.2717781, 1536.91516)
		elseif MyLevel == 10 or MyLevel <= 14 then 
			Ms = "Monkey [Lv. 14]"
			NaemQuest = "JungleQuest" 
			LevelQuest = 1
			NameMon = "Monkey"
			CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732)
			PosQuest = Vector3.new(-1604.12012, 36.8521118, 154.23732)
			CFrameMon = CFrame.new(-1772.4093017578, 60.860641479492, 54.872589111328)
			PosMon = Vector3.new(-1772.4093017578, 60.860641479492, 54.872589111328)
		elseif MyLevel == 15 or MyLevel <= 29 then 
			Ms = "Gorilla [Lv. 20]"
			NaemQuest = "JungleQuest"
			LevelQuest = 2
			NameMon = "Gorilla"
			CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732)
			PosQuest = Vector3.new(-1604.12012, 36.8521118, 154.23732)
		elseif MyLevel == 30 or MyLevel <= 39 then 
			Ms = "Pirate [Lv. 35]"
			NaemQuest = "BuggyQuest1"
			LevelQuest = 1
			NameMon = "Pirate"
			CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.16211)
			PosQuest = Vector3.new(-1139.59717, 4.75205183, 3825.16211)
			CFrameMon = CFrame.new(-1219.32324, 4.75205183, 3915.63452)
			PosMon = Vector3.new(-1219.32324, 4.75205183, 3915.63452)
		elseif MyLevel == 40 or MyLevel <= 59 then 
			Ms = "Brute [Lv. 45]"
			NaemQuest = "BuggyQuest1"
			LevelQuest = 2
			NameMon = "Brute"
			CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.1621)
			PosQuest = Vector3.new(-1139.59717, 4.75205183, 3825.1621)
			CFrameMon = CFrame.new(-1146.49646, 96.0936813, 4312.1333)
			PosMon = Vector3.new(-1146.49646, 96.0936813, 4312.1333)
		elseif MyLevel == 60 or MyLevel <= 74 then 
			Ms = "Desert Bandit [Lv. 60]"
			NaemQuest = "DesertQuest"
			LevelQuest = 1
			NameMon = "Desert Bandit"
			CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.9716)
			PosQuest = Vector3.new(897.031128, 6.43846416, 4388.9716)
			CFrameMon = CFrame.new(932.788818, 6.4503746, 4488.24609)
			PosMon = Vector3.new(932.788818, 6.4503746, 4488.24609)
		elseif MyLevel == 75 or MyLevel <= 89 then 
			Ms = "Desert Officer [Lv. 70]"
			NaemQuest = "DesertQuest"
			LevelQuest = 2
			NameMon = "Desert Officer"
			CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.9716)
			PosQuest = Vector3.new(897.031128, 6.43846416, 4388.9716)
			CFrameMon = CFrame.new(1580.03198, 4.61375761, 4366.86426)
			PosMon = Vector3.new(1580.03198, 4.61375761, 4366.86426)
		elseif MyLevel == 90 or MyLevel <= 99 then 
			Ms = "Snow Bandit [Lv. 90]"
			NaemQuest = "SnowQuest"
			LevelQuest = 1
			NameMon = "Snow Bandits"
			CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482)
			PosQuest = Vector3.new(1384.14001, 87.272789, -1297.06482)
			CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905)
			PosMon = Vector3.new(1370.24316, 102.403511, -1411.52905)
		elseif MyLevel == 100 or MyLevel <= 119 then 
			Ms = "Snowman [Lv. 100]"
			NaemQuest = "SnowQuest"
			LevelQuest = 2
			NameMon = "Snowman"
			CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482)
			PosQuest = Vector3.new(1384.14001, 87.272789, -1297.06482)
			CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905)
			PosMon = Vector3.new(1370.24316, 102.403511, -1411.52905)
		elseif MyLevel == 120 or MyLevel <= 149 then 
			Ms = "Chief Petty Officer [Lv. 120]"
			NaemQuest = "MarineQuest2"
			LevelQuest = 1
			NameMon = "Chief Petty Officer"
			CFrameQuest = CFrame.new(-5035.0835, 28.6520386, 4325.29443)
			PosQuest = Vector3.new(-5035.0835, 28.6520386, 4325.29443)
			CFrameMon = CFrame.new(-4882.8623, 22.6520386, 4255.53516)
			PosMon = Vector3.new(-4882.8623, 22.6520386, 4255.53516)
		elseif MyLevel == 150 or MyLevel <= 174 then 
			Ms = "Sky Bandit [Lv. 150]"
			NaemQuest = "SkyQuest"
			LevelQuest = 1
			NameMon = "Sky Bandit"
			CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436)
			PosQuest = Vector3.new(-4841.83447, 717.669617, -2623.96436)
			CFrameMon = CFrame.new(-4970.74219, 294.544342, -2890.11353)
			PosMon = Vector3.new(-4970.74219, 294.544342, -2890.11353)
		elseif MyLevel == 175 or MyLevel <= 224 then 
			Ms = "Dark Master [Lv. 175]"
			NaemQuest = "SkyQuest"
			LevelQuest = 2
			NameMon = "Dark Master"
			CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436)
			PosQuest = Vector3.new(-4841.83447, 717.669617, -2623.96436)
			CFrameMon = CFrame.new(-5220.58594, 430.693298, -2278.17456)
			PosMon = Vector3.new(-5220.58594, 430.693298, -2278.17456)
		elseif MyLevel == 225 or MyLevel <= 274 then 
			Ms = "Toga Warrior [Lv. 225]"
			NaemQuest = "ColosseumQuest"
			LevelQuest = 1
			NameMon = "Toga Warrior"
			CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762)
			PosQuest = Vector3.new(-1576.11743, 7.38933945, -2983.30762)
			CFrameMon = CFrame.new(-1779.97583, 44.6077499, -2736.35474)
			PosMon = Vector3.new(-1779.97583, 44.6077499, -2736.35474)
		elseif MyLevel == 275 or MyLevel <= 299 then 
			Ms = "Gladiator [Lv. 275]"
			NaemQuest = "ColosseumQuest"
			LevelQuest = 2
			NameMon = "Gladiato"
			CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762)
			PosQuest = Vector3.new(-1576.11743, 7.38933945, -2983.30762)
			CFrameMon = CFrame.new(-1274.75903, 58.1895943, -3188.16309)
			PosMon = Vector3.new(-1274.75903, 58.1895943, -3188.16309)
		elseif MyLevel == 300 or MyLevel <= 329 then 
			Ms = "Military Soldier [Lv. 300]"
			NaemQuest = "MagmaQuest"
			LevelQuest = 1
			NameMon = "Military Soldier"
			CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998)
			PosQuest = Vector3.new(-5316.55859, 12.2370615, 8517.2998)
			CFrameMon = CFrame.new(-5363.01123, 41.5056877, 8548.47266)
			PosMon = Vector3.new(-5363.01123, 41.5056877, 8548.47266)
		elseif MyLevel == 300 or MyLevel <= 374 then 
			Ms = "Military Spy [Lv. 330]"
			NaemQuest = "MagmaQuest"
			LevelQuest = 2
			NameMon = "Military Spy"
			CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998)
			PosQuest = Vector3.new(-5316.55859, 12.2370615, 8517.2998)
			CFrameMon = CFrame.new(-5787.99023, 120.864456, 8762.25293)
			PosMon = Vector3.new(-5787.99023, 120.864456, 8762.25293)
		elseif MyLevel == 375 or MyLevel <= 399 then 
			Ms = "Fishman Warrior [Lv. 375]"
			NaemQuest = "FishmanQuest"
			LevelQuest = 1
			NameMon = "Fishman Warrior"
			CFrameQuest = CFrame.new(61122.5625, 18.4716396, 1568.16504)
			PosQuest = Vector3.new(61122.5625, 18.4716396, 1568.16504)
			CFrameMon = CFrame.new(61163.8515625, 5.3073043823242, 1819.7841796875)
			PosMon = Vector3.new(61163.8515625, 5.3073043823242, 1819.7841796875)
		elseif MyLevel == 400 or MyLevel <= 449 then 
			Ms = "Fishman Commando [Lv. 400]"
			NaemQuest = "FishmanQuest"
			LevelQuest = 2
			NameMon = "Fishman Commando"
			CFrameQuest = CFrame.new(61122.5625, 18.4716396, 1568.16504)
			PosQuest = Vector3.new(61122.5625, 18.4716396, 1568.16504)
			CFrameMon = CFrame.new(61163.8515625, 5.3073043823242, 1819.7841796875)
			PosMon = Vector3.new(61163.8515625, 5.3073043823242, 1819.7841796875)
		elseif MyLevel == 450 or MyLevel <= 474 then 
			Ms = "God's Guard [Lv. 450]"
			NaemQuest = "SkyExp1Quest"
			LevelQuest = 1
			NameMon = "God's Guards"
			CFrameQuest = CFrame.new(-4721.71436, 845.277161, -1954.20105)
			PosQuest = Vector3.new(-4721.71436, 845.277161, -1954.20105)
			CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.925427)
			PosMon = Vector3.new(-4716.95703, 853.089722, -1933.925427)
		elseif MyLevel == 475 or MyLevel <= 524 then 
			Ms = "Shanda [Lv. 475]"
			NaemQuest = "SkyExp1Quest"
			LevelQuest = 2
			NameMon = "Shandas"
			CFrameQuest = CFrame.new(-7863.63672, 5545.49316, -379.826324)
			PosQuest = Vector3.new(-7863.63672, 5545.49316, -379.826324)
			CFrameMon = CFrame.new(-7685.12354, 5601.05127, -443.171509)
			PosMon = Vector3.new(-7685.12354, 5601.05127, -443.171509)
		elseif MyLevel == 525 or MyLevel <= 549 then 
			Ms = "Royal Squad [Lv. 525]"
			NaemQuest = "SkyExp2Quest"
			LevelQuest = 1
			NameMon = "Royal Squad"
			CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802)
			PosQuest = Vector3.new(-7902.66895, 5635.96387, -1411.71802)
			CFrameMon = CFrame.new(-7685.02051, 5606.87842, -1442.729)
			PosMon = Vector3.new(-7685.02051, 5606.87842, -1442.729)
		elseif MyLevel == 550 or MyLevel <= 624 then 
			Ms = "Royal Soldier [Lv. 550]"
			NaemQuest = "SkyExp2Quest"
			LevelQuest = 2
			NameMon = "Royal Soldier"
			CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802)
			PosQuest = Vector3.new(-7902.66895, 5635.96387, -1411.71802)
			CFrameMon = CFrame.new(-7864.44775, 5661.94092, -1708.22351)
			PosMon = Vector3.new(-7864.44775, 5661.94092, -1708.22351)
		elseif MyLevel == 625 or MyLevel <= 649 then 
			Ms = "Galley Pirate [Lv. 625]" 
			NaemQuest = "FountainQuest"
			LevelQuest = 1
			NameMon = "Galley Pirate"
			CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678)
			PosQuest = Vector3.new(5254.60156, 38.5011406, 4049.69678)
			CFrameMon = CFrame.new(5595.06982, 41.5013695, 3961.47095)
			PosMon = Vector3.new(5595.06982, 41.5013695, 3961.47095)
		elseif MyLevel >= 650 then 
			Ms = "Galley Captain [Lv. 650]"
			NaemQuest = "FountainQuest"
			LevelQuest = 2
			NameMon = "Galley Captain"
			CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678)
			PosQuest = Vector3.new(5254.60156, 38.5011406, 4049.69678)
			CFrameMon = CFrame.new(5658.5752, 38.5361786, 4928.93506)
			PosMon = Vector3.new(5658.5752, 38.5361786, 4928.93506)
		end
	end
	if NewWorld then
		if MyLevel == 700 or MyLevel <= 724 then 
			Ms = "Raider [Lv. 700]"
			NaemQuest = "Area1Quest"
			LevelQuest = 1
			NameMon = "Raider"
			CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589)
			PosQuest = Vector3.new(-424.080078, 73.0055847, 1836.91589)
			CFrameMon = CFrame.new(-737.026123, 39.1748352, 2392.57959)
			PosMon = Vector3.new(-737.026123, 39.1748352, 2392.57959)
		elseif MyLevel == 725 or MyLevel <= 774 then 
			Ms = "Mercenary [Lv. 725]"
			NaemQuest = "Area1Quest"
			LevelQuest = 2
			NameMon = "Mercenary"
			CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589)
			PosQuest = Vector3.new(-424.080078, 73.0055847, 1836.91589)
			CFrameMon = CFrame.new(-973.731995, 95.8733215, 1836.46936)
			PosMon = Vector3.new(-973.731995, 95.8733215, 1836.46936)
		elseif MyLevel == 775 or MyLevel <= 874 then 
			Ms = "Swan Pirate [Lv. 775]"
			NaemQuest = "Area2Quest"
			LevelQuest = 1
			NameMon = "Swan Pirate"
			CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321)
			PosQuest = Vector3.new(632.698608, 73.1055908, 918.666321)
			CFrameMon = CFrame.new(970.369446, 142.653198, 1217.3667)
			PosMon = Vector3.new(970.369446, 142.653198, 1217.3667)
		elseif MyLevel == 875 or MyLevel <= 899 then 
			Ms = "Marine Lieutenant [Lv. 875]"
			NaemQuest = "MarineQuest3"
			LevelQuest = 1
			NameMon = "Marine Lieutenant"
			CFrameQuest = CFrame.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			PosQuest = Vector3.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			CFrameMon = CFrame.new(-3065.75806, 102.075668, -3171.45386, -0.549014449, -3.08626227e-08, -0.835812867, 1.2026228e-08, 1, -4.4824862e-08, 0.835812867, -3.46611735e-08, -0.549014449)
			PosMon = Vector3.new(-3065.75806, 102.075668, -3171.45386, -0.549014449, -3.08626227e-08, -0.835812867, 1.2026228e-08, 1, -4.4824862e-08, 0.835812867, -3.46611735e-08, -0.549014449)
		elseif MyLevel == 900 or MyLevel <= 949 then 
			Ms = "Marine Captain [Lv. 900]"
			NaemQuest = "MarineQuest3"
			LevelQuest = 2
			NameMon = "Marine Captain"
			CFrameQuest = CFrame.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			PosQuest = Vector3.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			CFrameMon = CFrame.new(-1850.47278, 89.8190918, -3206.01025, 0.307623535, 2.29538806e-08, 0.951508164, -7.97129189e-08, 1, 1.64758374e-09, -0.951508164, -7.63543326e-08, 0.307623535)
			PosMon = Vector3.new(-1850.47278, 89.8190918, -3206.01025, 0.307623535, 2.29538806e-08, 0.951508164, -7.97129189e-08, 1, 1.64758374e-09, -0.951508164, -7.63543326e-08, 0.307623535)
		elseif MyLevel == 950 or MyLevel <= 974 then 
			Ms = "Zombie [Lv. 950]"
			NaemQuest = "ZombieQuest"
			LevelQuest = 1
			NameMon = "Zombie"
			CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571)
			PosQuest = Vector3.new(-5492.79395, 48.5151672, -793.710571)
			CFrameMon = CFrame.new(-5634.83838, 126.067039, -697.665039)
			PosMon = Vector3.new(-5634.83838, 126.067039, -697.665039)
		elseif MyLevel == 975 or MyLevel <= 999 then 
			Ms = "Vampire [Lv. 975]"
			NaemQuest = "ZombieQuest"
			LevelQuest = 2
			NameMon = "Vampire"
			CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571)
			PosQuest = Vector3.new(-5492.79395, 48.5151672, -793.710571)
			CFrameMon = CFrame.new(-6030.32031, 6.4377408, -1313.5564)
			PosMon = Vector3.new(-6030.32031, 6.4377408, -1313.5564)
		elseif MyLevel == 1000 or MyLevel <= 1049 then 
			Ms = "Snow Trooper [Lv. 1000]"
			NaemQuest = "SnowMountainQuest"
			LevelQuest = 1
			NameMon = "Snow Trooper"
			CFrameQuest = CFrame.new(604.964966, 401.457062, -5371.69287)
			PosQuest = Vector3.new(604.964966, 401.457062, -5371.69287)
			CFrameMon = CFrame.new(535.893433, 401.457062, -5329.6958)
			PosMon = Vector3.new(535.893433, 401.457062, -5329.6958)
		elseif MyLevel == 1050 or MyLevel <= 1099 then 
			Ms = "Winter Warrior [Lv. 1050]"
			NaemQuest = "SnowMountainQuest"
			LevelQuest = 2
			NameMon = "Winter Warrior"
			CFrameQuest = CFrame.new(604.964966, 401.457062, -5371.69287)
			PosQuest = Vector3.new(604.964966, 401.457062, -5371.69287)
			CFrameMon = CFrame.new(1223.7417, 454.575226, -5170.02148)
			PosMon = Vector3.new(1223.7417, 454.575226, -5170.02148)
		elseif MyLevel == 1100 or MyLevel <= 1124 then 
			Ms = "Lab Subordinate [Lv. 1100]"
			NaemQuest = "IceSideQuest"
			LevelQuest = 1
			NameMon = "Lab Subordinate"
			CFrameQuest = CFrame.new(-6060.10693, 15.9868021, -4904.7876)
			PosQuest = Vector3.new(-6060.10693, 15.9868021, -4904.7876)
			CFrameMon = CFrame.new(-5769.2041, 37.9288292, -4468.38721)
			PosMon = Vector3.new(-5769.2041, 37.9288292, -4468.38721)
		elseif MyLevel == 1125 or MyLevel <= 1174 then 
			Ms = "Horned Warrior [Lv. 1125]"
			NaemQuest = "IceSideQuest"
			LevelQuest = 2
			NameMon = "Horned Warrior"
			CFrameQuest = CFrame.new(-6060.10693, 15.9868021, -4904.7876)
			PosQuest = Vector3.new(-6060.10693, 15.9868021, -4904.7876)
			CFrameMon = CFrame.new(-6400.85889, 24.7645149, -5818.63574)
			PosMon = Vector3.new(-6400.85889, 24.7645149, -5818.63574)
		elseif MyLevel == 1175 or MyLevel <= 1199 then 
			Ms = "Magma Ninja [Lv. 1175]"
			NaemQuest = "FireSideQuest"
			LevelQuest = 1
			NameMon = "Magma Ninja"
			CFrameQuest = CFrame.new(-5431.09473, 15.9868021, -5296.53223)
			PosQuest = Vector3.new(-5431.09473, 15.9868021, -5296.53223)
			CFrameMon = CFrame.new(-5496.65576, 58.6890411, -5929.76855)
			PosMon = Vector3.new(-5496.65576, 58.6890411, -5929.76855)
		elseif MyLevel == 1200 or MyLevel <= 1349 then 
			Ms = "Lava Pirate [Lv. 1200]"
			NaemQuest = "FireSideQuest"
			LevelQuest = 2
			NameMon = "Lava Pirate"
			CFrameQuest = CFrame.new(-5431.09473, 15.9868021, -5296.53223)
			PosQuest = Vector3.new(-5431.09473, 15.9868021, -5296.53223)
			CFrameMon = CFrame.new(-5169.71729, 34.1234779, -4669.73633)
			PosMon = Vector3.new(-5169.71729, 34.1234779, -4669.73633)
		elseif MyLevel == 1350 or MyLevel <= 1374 then 
			Ms = "Arctic Warrior [Lv. 1350]"
			NaemQuest = "FrostQuest"
			LevelQuest = 1
			NameMon = "Arctic Warrior"
			CFrameQuest = CFrame.new(5669.43506, 28.2117786, -6482.60107)
			PosQuest = Vector3.new(5669.43506, 28.2117786, -6482.60107)
			CFrameMon = CFrame.new(5995.07471, 57.3188477, -6183.47314)
			PosMon = Vector3.new(5995.07471, 57.3188477, -6183.47314)
		elseif MyLevel == 1375 or MyLevel <= 1424 then 
			Ms = "Snow Lurker [Lv. 1375]"
			NaemQuest = "FrostQuest"
			LevelQuest = 2
			NameMon = "Snow Lurker"
			CFrameQuest = CFrame.new(5669.43506, 28.2117786, -6482.60107)
			PosQuest = Vector3.new(5669.43506, 28.2117786, -6482.60107)
			CFrameMon = CFrame.new(5518.00684, 60.5559731, -6828.80518)
			PosMon = Vector3.new(5518.00684, 60.5559731, -6828.80518)
		elseif MyLevel == 1425 or MyLevel <= 1449 then 
			Ms = "Sea Soldier [Lv. 1425]"
			NaemQuest = "ForgottenQuest"
			LevelQuest = 1
			NameMon = "Sea Soldier"
			CFrameQuest = CFrame.new(-3052.99097, 236.881363, -10148.1943)
			PosQuest = Vector3.new(-3052.99097, 236.881363, -10148.1943)
			CFrameMon = CFrame.new(-3030.3696289063, 191.13464355469, -9859.7958984375)
			PosMon = Vector3.new(-3030.3696289063, 191.13464355469, -9859.7958984375)
		elseif MyLevel >= 1450 then 
			Ms = "Water Fighter [Lv. 1450]"
			NaemQuest = "ForgottenQuest"
			LevelQuest = 2
			NameMon = "Water Fighter"
			CFrameQuest = CFrame.new(-3052.99097, 236.881363, -10148.1943)
			PosQuest = Vector3.new(-3052.99097, 236.881363, -10148.1943)
			CFrameMon = CFrame.new(-3436.7727050781, 290.52191162109, -10503.438476563)
			PosMon = Vector3.new(-3436.7727050781, 290.52191162109, -10503.438476563)
		end
	end
	if ThreeWorld then
		if MyLevel >= 1500 and MyLevel <= 1524 then
			Ms = "Pirate Millionaire [Lv. 1500]"
			NaemQuest = "PiratePortQuest"
			LevelQuest = 1
			NameMon = "Pirate Millionaire"
			CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984)
			PosQuest = Vector3.new(-290.074677, 42.9034653, 5581.58984)
			CFrameMon = CFrame.new(81.164993286133, 43.755737304688, 5724.7021484375)
			PosMon = Vector3.new(81.164993286133, 43.755737304688, 5724.7021484375)
		elseif MyLevel >= 1525 and MyLevel <= 1574 then
			Ms = "Pistol Billionaire [Lv. 1525]"
			NaemQuest = "PiratePortQuest"
			LevelQuest = 2
			NameMon = "Pistol Billionaire"
			CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984)
			PosQuest = Vector3.new(-290.074677, 42.9034653, 5581.58984)
			CFrameMon = CFrame.new(81.164993286133, 43.755737304688, 5724.7021484375)
			PosMon = Vector3.new(81.164993286133, 43.755737304688, 5724.7021484375)
		elseif MyLevel >= 1575 and MyLevel <= 1599 then
			Ms = "Dragon Crew Warrior [Lv. 1575]"
			NaemQuest = "AmazonQuest"
			LevelQuest = 1
			NameMon = "Dragon Crew Warrior"
			CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563)
			PosQuest = Vector3.new(5832.83594, 51.6806107, -1101.51563)
			CFrameMon = CFrame.new(6241.9951171875, 51.522083282471, -1243.9771728516)
			PosMon = Vector3.new(6241.9951171875, 51.522083282471, -1243.9771728516)
		elseif MyLevel >= 1600 and MyLevel <= 1624 then
			Ms = "Dragon Crew Archer [Lv. 1600]"
			NaemQuest = "AmazonQuest"
			LevelQuest = 2
			NameMon = "Dragon Crew Archer"
			CFrameQuest = CFrame.new(5834.13281, 51.3513527, -1104.94043, -0.224075064, 0, 0.974571884, 0, 1, -0, -0.974571884, 0, -0.224075064)
			PosQuest = Vector3.new(5834.13281, 51.3513527, -1104.94043, -0.224075064, 0, 0.974571884, 0, 1, -0, -0.974571884, 0, -0.224075064)
			CFrameMon = CFrame.new(6788.97461, 462.341248, 164.233673, -0.711975694, 1.98202414e-08, 0.702204108, -1.45830699e-08, 1, -4.30117559e-08, -0.702204108, -4.08636183e-08, -0.711975694)
			PosMon = Vector3.new(6788.97461, 462.341248, 164.233673, -0.711975694, 1.98202414e-08, 0.702204108, -1.45830699e-08, 1, -4.30117559e-08, -0.702204108, -4.08636183e-08, -0.711975694)
		elseif MyLevel >= 1625 and MyLevel <= 1649 then
			Ms = "Female Islander [Lv. 1625]"
			NaemQuest = "AmazonQuest2"
			LevelQuest = 1
			NameMon = "Female Islander"
			CFrameQuest = CFrame.new(5444.26416, 601.603638, 751.6604, 0.116254583, 1.00329423e-07, -0.993219435, 2.09664464e-08, 1, 1.03468444e-07, 0.993219435, -3.2852963e-08, 0.116254583)
			PosQuest = Vector3.new(5444.26416, 601.603638, 751.6604, 0.116254583, 1.00329423e-07, -0.993219435, 2.09664464e-08, 1, 1.03468444e-07, 0.993219435, -3.2852963e-08, 0.116254583)
			CFrameMon = CFrame.new(5763.98682, 848.118103, 1082.43127, 0.986172736, 2.65753979e-08, 0.165720671, -2.36233451e-08, 1, -1.97844852e-08, -0.165720671, 1.55960436e-08, 0.986172736)
			PosMon = Vector3.new(5763.98682, 848.118103, 1082.43127, 0.986172736, 2.65753979e-08, 0.165720671, -2.36233451e-08, 1, -1.97844852e-08, -0.165720671, 1.55960436e-08, 0.986172736)
		elseif MyLevel >= 1650 and MyLevel <= 1699 then
			Ms = "Giant Islander [Lv. 1650]"
			NaemQuest = "AmazonQuest2"
			LevelQuest = 2
			NameMon = "Giant Islander"
			CFrameQuest = CFrame.new(5443.72119, 606.5578, 750.532898, -0.981005013, -0, -0.193982586, -0, 1, -0, 0.193982586, 0, -0.981005)
			PosQuest = Vector3.new(5443.72119, 606.5578, 750.532898, -0.981005013, -0, -0.193982586, -0, 1, -0, 0.193982586, 0, -0.981005)
			CFrameMon = CFrame.new(4784.24561, 708.376465, 466.297485, 0.99801594, 3.11927195e-09, 0.0629619658, -5.34848299e-09, 1, 3.52371394e-08, -0.0629619658, -3.55039766e-08, 0.99801594)
			PosMon = Vector3.new(4784.24561, 708.376465, 466.297485, 0.99801594, 3.11927195e-09, 0.0629619658, -5.34848299e-09, 1, 3.52371394e-08, -0.0629619658, -3.55039766e-08, 0.99801594)
		elseif MyLevel >= 1700 and MyLevel <= 1724 then
			Ms = "Marine Commodore [Lv. 1700]"
			NaemQuest = "MarineTreeIsland"
			LevelQuest = 1
			NameMon = "Marine Commodore"
			CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498)
			PosQuest = Vector3.new(2180.54126, 27.8156815, -6741.5498)
			CFrameMon = CFrame.new(2490.0844726563, 190.4232635498, -7160.0502929688)
			PosMon = Vector3.new(2490.0844726563, 190.4232635498, -7160.0502929688)
		elseif MyLevel >= 1725 and MyLevel <= 1774 then
			Ms = "Marine Rear Admiral [Lv. 1725]"
			NaemQuest = "MarineTreeIsland"
			LevelQuest = 2
			NameMon = "Marine Rear Admiral"
			CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498)
			PosQuest = Vector3.new(2180.54126, 27.8156815, -6741.5498)
			CFrameMon = CFrame.new(3951.3903808594, 229.11549377441, -6912.81640625)
			PosMon = Vector3.new(3951.3903808594, 229.11549377441, -6912.81640625)
		elseif MyLevel >= 1775 and MyLevel <= 1799 then
			Ms = "Fishman Raider [Lv. 1775]"
			NaemQuest = "DeepForestIsland3"
			LevelQuest = 1
			NameMon = "Fishman Raider"
			CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652)
			PosQuest = Vector3.new(-10581.6563, 330.872955, -8761.18652)
			CFrameMon = CFrame.new(-10322.400390625, 390.94473266602, -8580.0908203125)
			PosMon = Vector3.new(-10322.400390625, 390.94473266602, -8580.0908203125)
		elseif MyLevel >= 1800 and MyLevel <= 1824 then
			Ms = "Fishman Captain [Lv. 1800]" 
			NaemQuest = "DeepForestIsland3"
			LevelQuest = 2
			NameMon = "Fishman Captain"
			CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652)
			PosQuest = Vector3.new(-10581.6563, 330.872955, -8761.18652)
			CFrameMon = CFrame.new(-11194.541992188, 442.02795410156, -8608.806640625)
			PosMon = Vector3.new(-11194.541992188, 442.02795410156, -8608.806640625)
		elseif MyLevel >= 1825 and MyLevel <= 1849 then
			Ms = "Forest Pirate [Lv. 1825]"
			NaemQuest = "DeepForestIsland"
			LevelQuest = 1
			NameMon = "Forest Pirate"
			CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137)
			PosQuest = Vector3.new(-13234.04, 331.488495, -7625.40137)
			CFrameMon = CFrame.new(-13225.809570313, 428.19387817383, -7753.1245117188)
			PosMon = Vector3.new(-13225.809570313, 428.19387817383, -7753.1245117188)
		elseif MyLevel >= 1850 and MyLevel <= 1899 then
			Ms = "Mythological Pirate [Lv. 1850]"
			NaemQuest = "DeepForestIsland"
			LevelQuest = 2
			NameMon = "Mythological Pirate"
			CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137)
			PosQuest = Vector3.new(-13234.04, 331.488495, -7625.40137)
			CFrameMon = CFrame.new(-13869.172851563, 564.95251464844, -7084.4135742188)
			PosMon = Vector3.new(-13869.172851563, 564.95251464844, -7084.4135742188)
		elseif MyLevel >= 1900 and MyLevel <= 1924 then
			Ms = "Jungle Pirate [Lv. 1900]"
			NaemQuest = "DeepForestIsland2"
			LevelQuest = 1
			NameMon = "Jungle Pirate"
			CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953)
			PosQuest = Vector3.new(-12680.3818, 389.971039, -9902.01953)
			CFrameMon = CFrame.new(-11982.221679688, 376.32522583008, -10451.415039063)
			PosMon = Vector3.new(-11982.221679688, 376.32522583008, -10451.415039063)
		elseif MyLevel >= 1925 and MyLevel <= 1974 then
			Ms = "Musketeer Pirate [Lv. 1925]"
			NaemQuest = "DeepForestIsland2"
			LevelQuest = 2
			NameMon = "Musketeer Pirate"
			CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953)
			PosQuest = Vector3.new(-12680.3818, 389.971039, -9902.01953)
			CFrameMon = CFrame.new(-13282.3046875, 496.23684692383, -9565.150390625)
			PosMon = Vector3.new(-13282.3046875, 496.23684692383, -9565.150390625)
		elseif MyLevel >= 1975 and MyLevel <= 1999 then
			Ms = "Reborn Skeleton [Lv. 1975]"
			NaemQuest = "HauntedQuest1"
			LevelQuest = 1
			NameMon = "Reborn Skeleton"
			CFrameQuest = CFrame.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			PosQuest = Vector3.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			CFrameMon = CFrame.new(-8817.880859375, 191.16761779785, 6298.6557617188)
			PosMon = Vector3.new(-8817.880859375, 191.16761779785, 6298.6557617188)
		elseif MyLevel >= 2000 and MyLevel <= 2024 then
			Ms = "Living Zombie [Lv. 2000]"
			NaemQuest = "HauntedQuest1"
			LevelQuest = 2
			NameMon = "Living Zombie"
			CFrameQuest = CFrame.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			PosQuest = Vector3.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			CFrameMon = CFrame.new(-10125.234375, 183.94705200195, 6242.013671875)
			PosMon = Vector3.new(-10125.234375, 183.94705200195, 6242.013671875)
		elseif MyLevel >= 2025 and MyLevel <= 2049  then
			Ms = "Demonic Soul [Lv. 2025]" 
			NaemQuest = "HauntedQuest2"
			LevelQuest = 1
			NameMon = "Demonic Soul"
			CFrameQuest = CFrame.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			PosQuest = Vector3.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			CFrameMon = CFrame.new(-9712.03125, 204.69589233398, 6193.322265625)
			PosMon = Vector3.new(-9712.03125, 204.69589233398, 6193.322265625)
		elseif MyLevel >= 2050 and MyLevel <= 2074  then
			Ms = "Posessed Mummy [Lv. 2050]"
			NaemQuest = "HauntedQuest2"
			LevelQuest = 2
			NameMon = "Posessed Mummy"
			CFrameQuest = CFrame.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			PosQuest = Vector3.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			CFrameMon = CFrame.new(-9545.7763671875, 69.619895935059, 6339.5615234375)    
			PosMon = Vector3.new(-9545.7763671875, 69.619895935059, 6339.5615234375)
		elseif MyLevel >= 2075 and MyLevel <= 2099  then
			Ms = "Peanut Scout [Lv. 2075]"
			NaemQuest = "NutsIslandQuest"
			LevelQuest = 1
			NameMon = "Peanut Scout"
			CFrameQuest = CFrame.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			PosQuest = Vector3.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			CFrameMon = CFrame.new(-2265.89014, 89.7506104, -10261.2197, -0.809553444, -9.26727282e-08, 0.587046146, -5.44419549e-08, 1, 8.27857534e-08, -0.587046146, 3.50595535e-08, -0.809553444)
			PosMon = Vector3.new(-2265.89014, 89.7506104, -10261.2197, -0.809553444, -9.26727282e-08, 0.587046146, -5.44419549e-08, 1, 8.27857534e-08, -0.587046146, 3.50595535e-08, -0.809553444)
		elseif MyLevel >= 2100 and MyLevel <= 2124  then
			Ms = "Peanut President [Lv. 2100]"
			NaemQuest = "NutsIslandQuest"
			LevelQuest = 2
			NameMon = "Peanut President"
			CFrameQuest = CFrame.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			PosQuest = Vector3.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			CFrameMon = CFrame.new(-2062.11792, 86.0444489, -10481.1445, 0.834163189, -9.79785408e-09, -0.551517665, -2.60617616e-09, 1, -2.17070646e-08, 0.551517665, 1.95445864e-08, 0.834163189)
			PosMon = Vector3.new(-2062.11792, 86.0444489, -10481.1445, 0.834163189, -9.79785408e-09, -0.551517665, -2.60617616e-09, 1, -2.17070646e-08, 0.551517665, 1.95445864e-08, 0.834163189)
		elseif MyLevel >= 2125 and MyLevel <= 2149  then
			Ms = "Ice Cream Chef [Lv. 2125]"
			NaemQuest = "IceCreamIslandQuest"
			LevelQuest = 1
			NameMon = "Ice Cream Chef"
			CFrameQuest = CFrame.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			PosQuest = Vector3.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			CFrameMon = CFrame.new(-875.441345, 107.871437, -11253.3691, 0.630182087, 5.98710486e-08, 0.776447415, -6.03229751e-08, 1, -2.81494827e-08, -0.776447415, -2.90983202e-08, 0.630182087)
			PosMon = Vector3.new(-875.441345, 107.871437, -11253.3691, 0.630182087, 5.98710486e-08, 0.776447415, -6.03229751e-08, 1, -2.81494827e-08, -0.776447415, -2.90983202e-08, 0.630182087)
		elseif MyLevel > 2150 then
			Ms = "Ice Cream Commander [Lv. 2150]"
			NaemQuest = "IceCreamIslandQuest"
			LevelQuest = 2
			NameMon = "Ice Cream Commander"
			CFrameQuest = CFrame.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			PosQuest = Vector3.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			CFrameMon = CFrame.new(-643.3078, 140.913528, -11334.7109, -0.996822715, -9.07818087e-09, 0.0796525627, -1.43212509e-08, 1, -6.52529906e-08, -0.0796525627, -6.61863808e-08, -0.996822715)
			PosMon = Vector3.new(-643.3078, 140.913528, -11334.7109, -0.996822715, -9.07818087e-09, 0.0796525627, -1.43212509e-08, 1, -6.52529906e-08, -0.0796525627, -6.61863808e-08, -0.996822715)
		end
	end
end

spawn(function()
    pcall(function()
        while task.wait() do
            if _G.FarmLevel then
                if not game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    local Noclip = Instance.new("BodyVelocity")
                    Noclip.Name = "BodyClip"
                    Noclip.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
                    Noclip.MaxForce = Vector3.new(100000,100000,100000)
                    Noclip.Velocity = Vector3.new(0,0,0)
                end
            else
                if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
                end
            end
        end
    end)
end)

function TP(P)
	Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
	if Distance < 60 then
	    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
		Speed = 1500
	elseif Distance < 215 then
	    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
		Speed = 435
	elseif Distance < 1000 then
		Speed = 380
	elseif Distance >= 1000 then
		Speed = 325
	end
	game:GetService("TweenService"):Create(
		game.Players.LocalPlayer.Character.HumanoidRootPart,
		TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
		{CFrame = P}
	):Play()
end

function EquipWeapon(ToolSe)
    if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
        local tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
        wait(.1)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
    end
end

function UnEquipAll()
    game.Players.LocalPlayer.Character.Humanoid:UnequipTools()
end 

spawn(function()
    while true do game:GetService("RunService").RenderStepped:Wait()
        if syn and  game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
            setfflag("HumanoidParallelRemoveNoPhysics", "False")
            setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
            setfflag("CrashPadUploadToBacktraceToBacktraceBaseUrl", "")
            setfflag("CrashUploadToBacktracePercentage", "0")
            setfflag("CrashUploadToBacktraceBlackholeToken", "")
            setfflag("CrashUploadToBacktraceWindowsPlayerToken", "")
        end
    end
end)

spawn(function()
    while wait() do
        pcall(function()
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if _G.FarmLevel and StartMagnet then
                    if v.Name == Ms and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                        if v.Name == "Factory Staff [Lv. 800]" then
                            if (v.HumanoidRootPart.Position - PosMon.Position).Magnitude <= 250 then
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                v.Humanoid.WalkSpeed = 0
                                v.Humanoid.JumpPower = 0
                                v.HumanoidRootPart.CFrame = PosMon
                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                            end
                        elseif v.Name == Ms then
                            if (v.HumanoidRootPart.Position - PosMon.Position).Magnitude <= 280 then
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Anchored = false
                                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                v.Humanoid.WalkSpeed = 0
                                v.Humanoid.JumpPower = 0
                                v.Humanoid:ChangeState(11)
                                v.HumanoidRootPart.CFrame = PosMon
                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                            end
                        end
                    end
                end
            end
        end)
    end
end)

spawn(function()
    while game:GetService("RunService").RenderStepped:wait() do
        if _G.FarmLevel then
            pcall(function()
                for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                    if v.Name == "Humanoid" then
                        v.PlatformStand = true
                    end
                end
            end)
        end
    end
end)

spawn(function()
    while game:GetService("RunService").RenderStepped:wait() do
        if _G.FarmLevel then
            pcall(function()
                for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                    if v.Name == Ms then
                        v.Humanoid:ChangeState(11)
                    end
                end
            end)
        end
    end
end)

spawn(function()
    while wait(.1) do
        pcall(function()
            if _G.FarmLevel then
                PointStats = game:GetService("Players").LocalPlayer.Data.Points.Value
                if game:GetService("Players").LocalPlayer.Data.Stats.Melee.Level.Value >= 2200 then
                    _G.Defense = true
                else
                    _G.Melee = true
                end
            end
            if _G.Melee then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee", PointStats)
            end
            if _G.Defense then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense", PointStats)
            end
        end)
    end
end)

spawn(function()
	while wait(.5) do
		if _G.FarmLevel and game:GetService("Players").LocalPlayer:FindFirstChild("WeaponAssetCache") then
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
				ToolWeapon = "Combat"
			end   
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				UnEquipAll()
				ToolWeapon = "Black Leg"
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				UnEquipAll()
				ToolWeapon = "Electro"
			end
			if ggame:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				ToolWeapon = "Fishman Karate"
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				ToolWeapon = "Dragon Claw"
			end
			
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
			end   
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward", "DragonClaw", "2")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward", "DragonClaw", "2")
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
			end 
		end
	end
end)

spawn(function()
    while wait() do
        if _G.FarmLevel then
            kkii = require(game.ReplicatedStorage.Util.CameraShaker)
            kkii:Stop()
        end
    end
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.FarmLevel then
				function UseCode(Text)
					game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(Text)
				end
				UseCode("fudd10_v2")
				UseCode("3BVISITS")
				UseCode("UPD16")
				UseCode("SUB2GAMERROBOT_EXP1")
				UseCode("StrawHatMaine")
				UseCode("Sub2OfficialNoobie")
				UseCode("FUDD10")
				UseCode("THEGREATACE")
				UseCode("Axiore")
				UseCode("SUB2NOOBMASTER123")
				UseCode("Sub2Daigrock")
				UseCode("TantaiGaming")
				UseCode("UPD15")
				UseCode("XMASEXP")
			end
		end
	end)
end)


spawn(function()
	while wait() do
		if _G.FarmLevel then
			if _G.FarmLevel and game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then
			end
			CheckQuest()
            if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
            end
            if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
            	CheckQuest()
                _G.FastAttack = false
    			StartMagnet = false
    			CheckQuest()
    			TP(CFrameQuest)
    			if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4 then
    				CheckQuest()
    				if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 20 then
    					wait(.5)
    					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NaemQuest, LevelQuest)
    					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
    				else
    					TP(CFrameQuest)
    				end
    			end
			elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
				pcall(function()
					CheckQuest()
					if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v.Name == Ms and v:FindFirstChild("Humanoid") then
								if v.Humanoid.Health > 0  then
									repeat game:GetService("RunService").Heartbeat:wait()
										if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then
											if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
												EquipWeapon(ToolWeapon)
                                                v.Head.CanCollide = false
                                                v.HumanoidRootPart.CanCollide = false
												TP(v.HumanoidRootPart.CFrame * CFrame.new(0,50,0))
												v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
												v.Humanoid.WalkSpeed = 0
												v.Humanoid.JumpPower = 0
												game:GetService("VirtualUser"):CaptureController()
                                                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
												PosMon = v.HumanoidRootPart.CFrame
                                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
												StartMagnet = true
                        					    if not _G.FastAttackOpen then
                                                    _G.FastAttack = false
                                                    RigC.activeController.hitboxMagnitude = 160
                                                else
                                                    _G.FastAttack = true
                        					    end
											else
                                                _G.FastAttack = false
												StartMagnet = false 
												wait(.1)   
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
											end
										else
                    					    _G.FastAttack = false
											StartMagnet = false
											CheckQuest()
										end
									until not v.Parent or v.Humanoid.Health <= 0 or _G.FarmLevel == false or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false or not game:GetService("Workspace").Enemies:FindFirstChild(v.Name)
								end
							end
						end
					else
					    _G.FastAttack = false
						StartMagnet = false
						CheckQuest()
					end
				end)
			end
		end
	end
end)

local placeId = game.PlaceId
if placeId == 2753915549 then
	OldWorld = true
elseif placeId == 4442272183 then
	NewWorld = true
elseif placeId == 7449423635 then
	ThreeWorld = true
end

function CheckQuest()
	local MyLevel = game.Players.LocalPlayer.Data.Level.Value
	if OldWorld then
		if MyLevel == 1 or MyLevel <= 9 then 
			Ms = "Bandit [Lv. 5]"
			NaemQuest = "BanditQuest1"
			LevelQuest = 1
			NameMon = "Bandit"
			CFrameQuest = CFrame.new(1061.66699, 16.5166187, 1544.52905)
			PosQuest = Vector3.new(1061.66699, 16.5166187, 1544.52905)
			CFrameMon = CFrame.new(1199.31287, 52.2717781, 1536.91516)
			PosMon = Vector3.new(1199.31287, 52.2717781, 1536.91516)
		elseif MyLevel == 10 or MyLevel <= 14 then 
			Ms = "Monkey [Lv. 14]"
			NaemQuest = "JungleQuest" 
			LevelQuest = 1
			NameMon = "Monkey"
			CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732)
			PosQuest = Vector3.new(-1604.12012, 36.8521118, 154.23732)
			CFrameMon = CFrame.new(-1772.4093017578, 60.860641479492, 54.872589111328)
			PosMon = Vector3.new(-1772.4093017578, 60.860641479492, 54.872589111328)
		elseif MyLevel == 15 or MyLevel <= 29 then 
			Ms = "Gorilla [Lv. 20]"
			NaemQuest = "JungleQuest"
			LevelQuest = 2
			NameMon = "Gorilla"
			CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732)
			PosQuest = Vector3.new(-1604.12012, 36.8521118, 154.23732)
		elseif MyLevel == 30 or MyLevel <= 39 then 
			Ms = "Pirate [Lv. 35]"
			NaemQuest = "BuggyQuest1"
			LevelQuest = 1
			NameMon = "Pirate"
			CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.16211)
			PosQuest = Vector3.new(-1139.59717, 4.75205183, 3825.16211)
			CFrameMon = CFrame.new(-1219.32324, 4.75205183, 3915.63452)
			PosMon = Vector3.new(-1219.32324, 4.75205183, 3915.63452)
		elseif MyLevel == 40 or MyLevel <= 59 then 
			Ms = "Brute [Lv. 45]"
			NaemQuest = "BuggyQuest1"
			LevelQuest = 2
			NameMon = "Brute"
			CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.1621)
			PosQuest = Vector3.new(-1139.59717, 4.75205183, 3825.1621)
			CFrameMon = CFrame.new(-1146.49646, 96.0936813, 4312.1333)
			PosMon = Vector3.new(-1146.49646, 96.0936813, 4312.1333)
		elseif MyLevel == 60 or MyLevel <= 74 then 
			Ms = "Desert Bandit [Lv. 60]"
			NaemQuest = "DesertQuest"
			LevelQuest = 1
			NameMon = "Desert Bandit"
			CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.9716)
			PosQuest = Vector3.new(897.031128, 6.43846416, 4388.9716)
			CFrameMon = CFrame.new(932.788818, 6.4503746, 4488.24609)
			PosMon = Vector3.new(932.788818, 6.4503746, 4488.24609)
		elseif MyLevel == 75 or MyLevel <= 89 then 
			Ms = "Desert Officer [Lv. 70]"
			NaemQuest = "DesertQuest"
			LevelQuest = 2
			NameMon = "Desert Officer"
			CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.9716)
			PosQuest = Vector3.new(897.031128, 6.43846416, 4388.9716)
			CFrameMon = CFrame.new(1580.03198, 4.61375761, 4366.86426)
			PosMon = Vector3.new(1580.03198, 4.61375761, 4366.86426)
		elseif MyLevel == 90 or MyLevel <= 99 then 
			Ms = "Snow Bandit [Lv. 90]"
			NaemQuest = "SnowQuest"
			LevelQuest = 1
			NameMon = "Snow Bandits"
			CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482)
			PosQuest = Vector3.new(1384.14001, 87.272789, -1297.06482)
			CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905)
			PosMon = Vector3.new(1370.24316, 102.403511, -1411.52905)
		elseif MyLevel == 100 or MyLevel <= 119 then 
			Ms = "Snowman [Lv. 100]"
			NaemQuest = "SnowQuest"
			LevelQuest = 2
			NameMon = "Snowman"
			CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482)
			PosQuest = Vector3.new(1384.14001, 87.272789, -1297.06482)
			CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905)
			PosMon = Vector3.new(1370.24316, 102.403511, -1411.52905)
		elseif MyLevel == 120 or MyLevel <= 149 then 
			Ms = "Chief Petty Officer [Lv. 120]"
			NaemQuest = "MarineQuest2"
			LevelQuest = 1
			NameMon = "Chief Petty Officer"
			CFrameQuest = CFrame.new(-5035.0835, 28.6520386, 4325.29443)
			PosQuest = Vector3.new(-5035.0835, 28.6520386, 4325.29443)
			CFrameMon = CFrame.new(-4882.8623, 22.6520386, 4255.53516)
			PosMon = Vector3.new(-4882.8623, 22.6520386, 4255.53516)
		elseif MyLevel == 150 or MyLevel <= 174 then 
			Ms = "Sky Bandit [Lv. 150]"
			NaemQuest = "SkyQuest"
			LevelQuest = 1
			NameMon = "Sky Bandit"
			CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436)
			PosQuest = Vector3.new(-4841.83447, 717.669617, -2623.96436)
			CFrameMon = CFrame.new(-4970.74219, 294.544342, -2890.11353)
			PosMon = Vector3.new(-4970.74219, 294.544342, -2890.11353)
		elseif MyLevel == 175 or MyLevel <= 224 then 
			Ms = "Dark Master [Lv. 175]"
			NaemQuest = "SkyQuest"
			LevelQuest = 2
			NameMon = "Dark Master"
			CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436)
			PosQuest = Vector3.new(-4841.83447, 717.669617, -2623.96436)
			CFrameMon = CFrame.new(-5220.58594, 430.693298, -2278.17456)
			PosMon = Vector3.new(-5220.58594, 430.693298, -2278.17456)
		elseif MyLevel == 225 or MyLevel <= 274 then 
			Ms = "Toga Warrior [Lv. 225]"
			NaemQuest = "ColosseumQuest"
			LevelQuest = 1
			NameMon = "Toga Warrior"
			CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762)
			PosQuest = Vector3.new(-1576.11743, 7.38933945, -2983.30762)
			CFrameMon = CFrame.new(-1779.97583, 44.6077499, -2736.35474)
			PosMon = Vector3.new(-1779.97583, 44.6077499, -2736.35474)
		elseif MyLevel == 275 or MyLevel <= 299 then 
			Ms = "Gladiator [Lv. 275]"
			NaemQuest = "ColosseumQuest"
			LevelQuest = 2
			NameMon = "Gladiato"
			CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762)
			PosQuest = Vector3.new(-1576.11743, 7.38933945, -2983.30762)
			CFrameMon = CFrame.new(-1274.75903, 58.1895943, -3188.16309)
			PosMon = Vector3.new(-1274.75903, 58.1895943, -3188.16309)
		elseif MyLevel == 300 or MyLevel <= 329 then 
			Ms = "Military Soldier [Lv. 300]"
			NaemQuest = "MagmaQuest"
			LevelQuest = 1
			NameMon = "Military Soldier"
			CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998)
			PosQuest = Vector3.new(-5316.55859, 12.2370615, 8517.2998)
			CFrameMon = CFrame.new(-5363.01123, 41.5056877, 8548.47266)
			PosMon = Vector3.new(-5363.01123, 41.5056877, 8548.47266)
		elseif MyLevel == 300 or MyLevel <= 374 then 
			Ms = "Military Spy [Lv. 330]"
			NaemQuest = "MagmaQuest"
			LevelQuest = 2
			NameMon = "Military Spy"
			CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998)
			PosQuest = Vector3.new(-5316.55859, 12.2370615, 8517.2998)
			CFrameMon = CFrame.new(-5787.99023, 120.864456, 8762.25293)
			PosMon = Vector3.new(-5787.99023, 120.864456, 8762.25293)
		elseif MyLevel == 375 or MyLevel <= 399 then 
			Ms = "Fishman Warrior [Lv. 375]"
			NaemQuest = "FishmanQuest"
			LevelQuest = 1
			NameMon = "Fishman Warrior"
			CFrameQuest = CFrame.new(61122.5625, 18.4716396, 1568.16504)
			PosQuest = Vector3.new(61122.5625, 18.4716396, 1568.16504)
			CFrameMon = CFrame.new(61163.8515625, 5.3073043823242, 1819.7841796875)
			PosMon = Vector3.new(61163.8515625, 5.3073043823242, 1819.7841796875)
		elseif MyLevel == 400 or MyLevel <= 449 then 
			Ms = "Fishman Commando [Lv. 400]"
			NaemQuest = "FishmanQuest"
			LevelQuest = 2
			NameMon = "Fishman Commando"
			CFrameQuest = CFrame.new(61122.5625, 18.4716396, 1568.16504)
			PosQuest = Vector3.new(61122.5625, 18.4716396, 1568.16504)
			CFrameMon = CFrame.new(61163.8515625, 5.3073043823242, 1819.7841796875)
			PosMon = Vector3.new(61163.8515625, 5.3073043823242, 1819.7841796875)
		elseif MyLevel == 450 or MyLevel <= 474 then 
			Ms = "God's Guard [Lv. 450]"
			NaemQuest = "SkyExp1Quest"
			LevelQuest = 1
			NameMon = "God's Guards"
			CFrameQuest = CFrame.new(-4721.71436, 845.277161, -1954.20105)
			PosQuest = Vector3.new(-4721.71436, 845.277161, -1954.20105)
			CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.925427)
			PosMon = Vector3.new(-4716.95703, 853.089722, -1933.925427)
		elseif MyLevel == 475 or MyLevel <= 524 then 
			Ms = "Shanda [Lv. 475]"
			NaemQuest = "SkyExp1Quest"
			LevelQuest = 2
			NameMon = "Shandas"
			CFrameQuest = CFrame.new(-7863.63672, 5545.49316, -379.826324)
			PosQuest = Vector3.new(-7863.63672, 5545.49316, -379.826324)
			CFrameMon = CFrame.new(-7685.12354, 5601.05127, -443.171509)
			PosMon = Vector3.new(-7685.12354, 5601.05127, -443.171509)
		elseif MyLevel == 525 or MyLevel <= 549 then 
			Ms = "Royal Squad [Lv. 525]"
			NaemQuest = "SkyExp2Quest"
			LevelQuest = 1
			NameMon = "Royal Squad"
			CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802)
			PosQuest = Vector3.new(-7902.66895, 5635.96387, -1411.71802)
			CFrameMon = CFrame.new(-7685.02051, 5606.87842, -1442.729)
			PosMon = Vector3.new(-7685.02051, 5606.87842, -1442.729)
		elseif MyLevel == 550 or MyLevel <= 624 then 
			Ms = "Royal Soldier [Lv. 550]"
			NaemQuest = "SkyExp2Quest"
			LevelQuest = 2
			NameMon = "Royal Soldier"
			CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802)
			PosQuest = Vector3.new(-7902.66895, 5635.96387, -1411.71802)
			CFrameMon = CFrame.new(-7864.44775, 5661.94092, -1708.22351)
			PosMon = Vector3.new(-7864.44775, 5661.94092, -1708.22351)
		elseif MyLevel == 625 or MyLevel <= 649 then 
			Ms = "Galley Pirate [Lv. 625]" 
			NaemQuest = "FountainQuest"
			LevelQuest = 1
			NameMon = "Galley Pirate"
			CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678)
			PosQuest = Vector3.new(5254.60156, 38.5011406, 4049.69678)
			CFrameMon = CFrame.new(5595.06982, 41.5013695, 3961.47095)
			PosMon = Vector3.new(5595.06982, 41.5013695, 3961.47095)
		elseif MyLevel >= 650 then 
			Ms = "Galley Captain [Lv. 650]"
			NaemQuest = "FountainQuest"
			LevelQuest = 2
			NameMon = "Galley Captain"
			CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678)
			PosQuest = Vector3.new(5254.60156, 38.5011406, 4049.69678)
			CFrameMon = CFrame.new(5658.5752, 38.5361786, 4928.93506)
			PosMon = Vector3.new(5658.5752, 38.5361786, 4928.93506)
		end
	end
	if NewWorld then
		if MyLevel == 700 or MyLevel <= 724 then 
			Ms = "Raider [Lv. 700]"
			NaemQuest = "Area1Quest"
			LevelQuest = 1
			NameMon = "Raider"
			CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589)
			PosQuest = Vector3.new(-424.080078, 73.0055847, 1836.91589)
			CFrameMon = CFrame.new(-737.026123, 39.1748352, 2392.57959)
			PosMon = Vector3.new(-737.026123, 39.1748352, 2392.57959)
		elseif MyLevel == 725 or MyLevel <= 774 then 
			Ms = "Mercenary [Lv. 725]"
			NaemQuest = "Area1Quest"
			LevelQuest = 2
			NameMon = "Mercenary"
			CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589)
			PosQuest = Vector3.new(-424.080078, 73.0055847, 1836.91589)
			CFrameMon = CFrame.new(-973.731995, 95.8733215, 1836.46936)
			PosMon = Vector3.new(-973.731995, 95.8733215, 1836.46936)
		elseif MyLevel == 775 or MyLevel <= 874 then 
			Ms = "Swan Pirate [Lv. 775]"
			NaemQuest = "Area2Quest"
			LevelQuest = 1
			NameMon = "Swan Pirate"
			CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321)
			PosQuest = Vector3.new(632.698608, 73.1055908, 918.666321)
			CFrameMon = CFrame.new(970.369446, 142.653198, 1217.3667)
			PosMon = Vector3.new(970.369446, 142.653198, 1217.3667)
		elseif MyLevel == 875 or MyLevel <= 899 then 
			Ms = "Marine Lieutenant [Lv. 875]"
			NaemQuest = "MarineQuest3"
			LevelQuest = 1
			NameMon = "Marine Lieutenant"
			CFrameQuest = CFrame.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			PosQuest = Vector3.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			CFrameMon = CFrame.new(-3065.75806, 102.075668, -3171.45386, -0.549014449, -3.08626227e-08, -0.835812867, 1.2026228e-08, 1, -4.4824862e-08, 0.835812867, -3.46611735e-08, -0.549014449)
			PosMon = Vector3.new(-3065.75806, 102.075668, -3171.45386, -0.549014449, -3.08626227e-08, -0.835812867, 1.2026228e-08, 1, -4.4824862e-08, 0.835812867, -3.46611735e-08, -0.549014449)
		elseif MyLevel == 900 or MyLevel <= 949 then 
			Ms = "Marine Captain [Lv. 900]"
			NaemQuest = "MarineQuest3"
			LevelQuest = 2
			NameMon = "Marine Captain"
			CFrameQuest = CFrame.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			PosQuest = Vector3.new(-2442.99805, 73.0160828, -3219.61304, -0.877783895, -7.71497781e-08, -0.479056865, -6.27637746e-08, 1, -4.60420289e-08, 0.479056865, -1.03475353e-08, -0.877783895)
			CFrameMon = CFrame.new(-1850.47278, 89.8190918, -3206.01025, 0.307623535, 2.29538806e-08, 0.951508164, -7.97129189e-08, 1, 1.64758374e-09, -0.951508164, -7.63543326e-08, 0.307623535)
			PosMon = Vector3.new(-1850.47278, 89.8190918, -3206.01025, 0.307623535, 2.29538806e-08, 0.951508164, -7.97129189e-08, 1, 1.64758374e-09, -0.951508164, -7.63543326e-08, 0.307623535)
		elseif MyLevel == 950 or MyLevel <= 974 then 
			Ms = "Zombie [Lv. 950]"
			NaemQuest = "ZombieQuest"
			LevelQuest = 1
			NameMon = "Zombie"
			CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571)
			PosQuest = Vector3.new(-5492.79395, 48.5151672, -793.710571)
			CFrameMon = CFrame.new(-5634.83838, 126.067039, -697.665039)
			PosMon = Vector3.new(-5634.83838, 126.067039, -697.665039)
		elseif MyLevel == 975 or MyLevel <= 999 then 
			Ms = "Vampire [Lv. 975]"
			NaemQuest = "ZombieQuest"
			LevelQuest = 2
			NameMon = "Vampire"
			CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571)
			PosQuest = Vector3.new(-5492.79395, 48.5151672, -793.710571)
			CFrameMon = CFrame.new(-6030.32031, 6.4377408, -1313.5564)
			PosMon = Vector3.new(-6030.32031, 6.4377408, -1313.5564)
		elseif MyLevel == 1000 or MyLevel <= 1049 then 
			Ms = "Snow Trooper [Lv. 1000]"
			NaemQuest = "SnowMountainQuest"
			LevelQuest = 1
			NameMon = "Snow Trooper"
			CFrameQuest = CFrame.new(604.964966, 401.457062, -5371.69287)
			PosQuest = Vector3.new(604.964966, 401.457062, -5371.69287)
			CFrameMon = CFrame.new(535.893433, 401.457062, -5329.6958)
			PosMon = Vector3.new(535.893433, 401.457062, -5329.6958)
		elseif MyLevel == 1050 or MyLevel <= 1099 then 
			Ms = "Winter Warrior [Lv. 1050]"
			NaemQuest = "SnowMountainQuest"
			LevelQuest = 2
			NameMon = "Winter Warrior"
			CFrameQuest = CFrame.new(604.964966, 401.457062, -5371.69287)
			PosQuest = Vector3.new(604.964966, 401.457062, -5371.69287)
			CFrameMon = CFrame.new(1223.7417, 454.575226, -5170.02148)
			PosMon = Vector3.new(1223.7417, 454.575226, -5170.02148)
		elseif MyLevel == 1100 or MyLevel <= 1124 then 
			Ms = "Lab Subordinate [Lv. 1100]"
			NaemQuest = "IceSideQuest"
			LevelQuest = 1
			NameMon = "Lab Subordinate"
			CFrameQuest = CFrame.new(-6060.10693, 15.9868021, -4904.7876)
			PosQuest = Vector3.new(-6060.10693, 15.9868021, -4904.7876)
			CFrameMon = CFrame.new(-5769.2041, 37.9288292, -4468.38721)
			PosMon = Vector3.new(-5769.2041, 37.9288292, -4468.38721)
		elseif MyLevel == 1125 or MyLevel <= 1174 then 
			Ms = "Horned Warrior [Lv. 1125]"
			NaemQuest = "IceSideQuest"
			LevelQuest = 2
			NameMon = "Horned Warrior"
			CFrameQuest = CFrame.new(-6060.10693, 15.9868021, -4904.7876)
			PosQuest = Vector3.new(-6060.10693, 15.9868021, -4904.7876)
			CFrameMon = CFrame.new(-6400.85889, 24.7645149, -5818.63574)
			PosMon = Vector3.new(-6400.85889, 24.7645149, -5818.63574)
		elseif MyLevel == 1175 or MyLevel <= 1199 then 
			Ms = "Magma Ninja [Lv. 1175]"
			NaemQuest = "FireSideQuest"
			LevelQuest = 1
			NameMon = "Magma Ninja"
			CFrameQuest = CFrame.new(-5431.09473, 15.9868021, -5296.53223)
			PosQuest = Vector3.new(-5431.09473, 15.9868021, -5296.53223)
			CFrameMon = CFrame.new(-5496.65576, 58.6890411, -5929.76855)
			PosMon = Vector3.new(-5496.65576, 58.6890411, -5929.76855)
		elseif MyLevel == 1200 or MyLevel <= 1349 then 
			Ms = "Lava Pirate [Lv. 1200]"
			NaemQuest = "FireSideQuest"
			LevelQuest = 2
			NameMon = "Lava Pirate"
			CFrameQuest = CFrame.new(-5431.09473, 15.9868021, -5296.53223)
			PosQuest = Vector3.new(-5431.09473, 15.9868021, -5296.53223)
			CFrameMon = CFrame.new(-5169.71729, 34.1234779, -4669.73633)
			PosMon = Vector3.new(-5169.71729, 34.1234779, -4669.73633)
		elseif MyLevel == 1350 or MyLevel <= 1374 then 
			Ms = "Arctic Warrior [Lv. 1350]"
			NaemQuest = "FrostQuest"
			LevelQuest = 1
			NameMon = "Arctic Warrior"
			CFrameQuest = CFrame.new(5669.43506, 28.2117786, -6482.60107)
			PosQuest = Vector3.new(5669.43506, 28.2117786, -6482.60107)
			CFrameMon = CFrame.new(5995.07471, 57.3188477, -6183.47314)
			PosMon = Vector3.new(5995.07471, 57.3188477, -6183.47314)
		elseif MyLevel == 1375 or MyLevel <= 1424 then 
			Ms = "Snow Lurker [Lv. 1375]"
			NaemQuest = "FrostQuest"
			LevelQuest = 2
			NameMon = "Snow Lurker"
			CFrameQuest = CFrame.new(5669.43506, 28.2117786, -6482.60107)
			PosQuest = Vector3.new(5669.43506, 28.2117786, -6482.60107)
			CFrameMon = CFrame.new(5518.00684, 60.5559731, -6828.80518)
			PosMon = Vector3.new(5518.00684, 60.5559731, -6828.80518)
		elseif MyLevel == 1425 or MyLevel <= 1449 then 
			Ms = "Sea Soldier [Lv. 1425]"
			NaemQuest = "ForgottenQuest"
			LevelQuest = 1
			NameMon = "Sea Soldier"
			CFrameQuest = CFrame.new(-3052.99097, 236.881363, -10148.1943)
			PosQuest = Vector3.new(-3052.99097, 236.881363, -10148.1943)
			CFrameMon = CFrame.new(-3030.3696289063, 191.13464355469, -9859.7958984375)
			PosMon = Vector3.new(-3030.3696289063, 191.13464355469, -9859.7958984375)
		elseif MyLevel >= 1450 then 
			Ms = "Water Fighter [Lv. 1450]"
			NaemQuest = "ForgottenQuest"
			LevelQuest = 2
			NameMon = "Water Fighter"
			CFrameQuest = CFrame.new(-3052.99097, 236.881363, -10148.1943)
			PosQuest = Vector3.new(-3052.99097, 236.881363, -10148.1943)
			CFrameMon = CFrame.new(-3436.7727050781, 290.52191162109, -10503.438476563)
			PosMon = Vector3.new(-3436.7727050781, 290.52191162109, -10503.438476563)
		end
	end
	if ThreeWorld then
		if MyLevel >= 1500 and MyLevel <= 1524 then
			Ms = "Pirate Millionaire [Lv. 1500]"
			NaemQuest = "PiratePortQuest"
			LevelQuest = 1
			NameMon = "Pirate Millionaire"
			CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984)
			PosQuest = Vector3.new(-290.074677, 42.9034653, 5581.58984)
			CFrameMon = CFrame.new(81.164993286133, 43.755737304688, 5724.7021484375)
			PosMon = Vector3.new(81.164993286133, 43.755737304688, 5724.7021484375)
		elseif MyLevel >= 1525 and MyLevel <= 1574 then
			Ms = "Pistol Billionaire [Lv. 1525]"
			NaemQuest = "PiratePortQuest"
			LevelQuest = 2
			NameMon = "Pistol Billionaire"
			CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984)
			PosQuest = Vector3.new(-290.074677, 42.9034653, 5581.58984)
			CFrameMon = CFrame.new(81.164993286133, 43.755737304688, 5724.7021484375)
			PosMon = Vector3.new(81.164993286133, 43.755737304688, 5724.7021484375)
		elseif MyLevel >= 1575 and MyLevel <= 1599 then
			Ms = "Dragon Crew Warrior [Lv. 1575]"
			NaemQuest = "AmazonQuest"
			LevelQuest = 1
			NameMon = "Dragon Crew Warrior"
			CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563)
			PosQuest = Vector3.new(5832.83594, 51.6806107, -1101.51563)
			CFrameMon = CFrame.new(6241.9951171875, 51.522083282471, -1243.9771728516)
			PosMon = Vector3.new(6241.9951171875, 51.522083282471, -1243.9771728516)
		elseif MyLevel >= 1600 and MyLevel <= 1624 then
			Ms = "Dragon Crew Archer [Lv. 1600]"
			NaemQuest = "AmazonQuest"
			LevelQuest = 2
			NameMon = "Dragon Crew Archer"
			CFrameQuest = CFrame.new(5834.13281, 51.3513527, -1104.94043, -0.224075064, 0, 0.974571884, 0, 1, -0, -0.974571884, 0, -0.224075064)
			PosQuest = Vector3.new(5834.13281, 51.3513527, -1104.94043, -0.224075064, 0, 0.974571884, 0, 1, -0, -0.974571884, 0, -0.224075064)
			CFrameMon = CFrame.new(6788.97461, 462.341248, 164.233673, -0.711975694, 1.98202414e-08, 0.702204108, -1.45830699e-08, 1, -4.30117559e-08, -0.702204108, -4.08636183e-08, -0.711975694)
			PosMon = Vector3.new(6788.97461, 462.341248, 164.233673, -0.711975694, 1.98202414e-08, 0.702204108, -1.45830699e-08, 1, -4.30117559e-08, -0.702204108, -4.08636183e-08, -0.711975694)
		elseif MyLevel >= 1625 and MyLevel <= 1649 then
			Ms = "Female Islander [Lv. 1625]"
			NaemQuest = "AmazonQuest2"
			LevelQuest = 1
			NameMon = "Female Islander"
			CFrameQuest = CFrame.new(5444.26416, 601.603638, 751.6604, 0.116254583, 1.00329423e-07, -0.993219435, 2.09664464e-08, 1, 1.03468444e-07, 0.993219435, -3.2852963e-08, 0.116254583)
			PosQuest = Vector3.new(5444.26416, 601.603638, 751.6604, 0.116254583, 1.00329423e-07, -0.993219435, 2.09664464e-08, 1, 1.03468444e-07, 0.993219435, -3.2852963e-08, 0.116254583)
			CFrameMon = CFrame.new(5763.98682, 848.118103, 1082.43127, 0.986172736, 2.65753979e-08, 0.165720671, -2.36233451e-08, 1, -1.97844852e-08, -0.165720671, 1.55960436e-08, 0.986172736)
			PosMon = Vector3.new(5763.98682, 848.118103, 1082.43127, 0.986172736, 2.65753979e-08, 0.165720671, -2.36233451e-08, 1, -1.97844852e-08, -0.165720671, 1.55960436e-08, 0.986172736)
		elseif MyLevel >= 1650 and MyLevel <= 1699 then
			Ms = "Giant Islander [Lv. 1650]"
			NaemQuest = "AmazonQuest2"
			LevelQuest = 2
			NameMon = "Giant Islander"
			CFrameQuest = CFrame.new(5443.72119, 606.5578, 750.532898, -0.981005013, -0, -0.193982586, -0, 1, -0, 0.193982586, 0, -0.981005)
			PosQuest = Vector3.new(5443.72119, 606.5578, 750.532898, -0.981005013, -0, -0.193982586, -0, 1, -0, 0.193982586, 0, -0.981005)
			CFrameMon = CFrame.new(4784.24561, 708.376465, 466.297485, 0.99801594, 3.11927195e-09, 0.0629619658, -5.34848299e-09, 1, 3.52371394e-08, -0.0629619658, -3.55039766e-08, 0.99801594)
			PosMon = Vector3.new(4784.24561, 708.376465, 466.297485, 0.99801594, 3.11927195e-09, 0.0629619658, -5.34848299e-09, 1, 3.52371394e-08, -0.0629619658, -3.55039766e-08, 0.99801594)
		elseif MyLevel >= 1700 and MyLevel <= 1724 then
			Ms = "Marine Commodore [Lv. 1700]"
			NaemQuest = "MarineTreeIsland"
			LevelQuest = 1
			NameMon = "Marine Commodore"
			CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498)
			PosQuest = Vector3.new(2180.54126, 27.8156815, -6741.5498)
			CFrameMon = CFrame.new(2490.0844726563, 190.4232635498, -7160.0502929688)
			PosMon = Vector3.new(2490.0844726563, 190.4232635498, -7160.0502929688)
		elseif MyLevel >= 1725 and MyLevel <= 1774 then
			Ms = "Marine Rear Admiral [Lv. 1725]"
			NaemQuest = "MarineTreeIsland"
			LevelQuest = 2
			NameMon = "Marine Rear Admiral"
			CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498)
			PosQuest = Vector3.new(2180.54126, 27.8156815, -6741.5498)
			CFrameMon = CFrame.new(3951.3903808594, 229.11549377441, -6912.81640625)
			PosMon = Vector3.new(3951.3903808594, 229.11549377441, -6912.81640625)
		elseif MyLevel >= 1775 and MyLevel <= 1799 then
			Ms = "Fishman Raider [Lv. 1775]"
			NaemQuest = "DeepForestIsland3"
			LevelQuest = 1
			NameMon = "Fishman Raider"
			CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652)
			PosQuest = Vector3.new(-10581.6563, 330.872955, -8761.18652)
			CFrameMon = CFrame.new(-10322.400390625, 390.94473266602, -8580.0908203125)
			PosMon = Vector3.new(-10322.400390625, 390.94473266602, -8580.0908203125)
		elseif MyLevel >= 1800 and MyLevel <= 1824 then
			Ms = "Fishman Captain [Lv. 1800]" 
			NaemQuest = "DeepForestIsland3"
			LevelQuest = 2
			NameMon = "Fishman Captain"
			CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652)
			PosQuest = Vector3.new(-10581.6563, 330.872955, -8761.18652)
			CFrameMon = CFrame.new(-11194.541992188, 442.02795410156, -8608.806640625)
			PosMon = Vector3.new(-11194.541992188, 442.02795410156, -8608.806640625)
		elseif MyLevel >= 1825 and MyLevel <= 1849 then
			Ms = "Forest Pirate [Lv. 1825]"
			NaemQuest = "DeepForestIsland"
			LevelQuest = 1
			NameMon = "Forest Pirate"
			CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137)
			PosQuest = Vector3.new(-13234.04, 331.488495, -7625.40137)
			CFrameMon = CFrame.new(-13225.809570313, 428.19387817383, -7753.1245117188)
			PosMon = Vector3.new(-13225.809570313, 428.19387817383, -7753.1245117188)
		elseif MyLevel >= 1850 and MyLevel <= 1899 then
			Ms = "Mythological Pirate [Lv. 1850]"
			NaemQuest = "DeepForestIsland"
			LevelQuest = 2
			NameMon = "Mythological Pirate"
			CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137)
			PosQuest = Vector3.new(-13234.04, 331.488495, -7625.40137)
			CFrameMon = CFrame.new(-13869.172851563, 564.95251464844, -7084.4135742188)
			PosMon = Vector3.new(-13869.172851563, 564.95251464844, -7084.4135742188)
		elseif MyLevel >= 1900 and MyLevel <= 1924 then
			Ms = "Jungle Pirate [Lv. 1900]"
			NaemQuest = "DeepForestIsland2"
			LevelQuest = 1
			NameMon = "Jungle Pirate"
			CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953)
			PosQuest = Vector3.new(-12680.3818, 389.971039, -9902.01953)
			CFrameMon = CFrame.new(-11982.221679688, 376.32522583008, -10451.415039063)
			PosMon = Vector3.new(-11982.221679688, 376.32522583008, -10451.415039063)
		elseif MyLevel >= 1925 and MyLevel <= 1974 then
			Ms = "Musketeer Pirate [Lv. 1925]"
			NaemQuest = "DeepForestIsland2"
			LevelQuest = 2
			NameMon = "Musketeer Pirate"
			CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953)
			PosQuest = Vector3.new(-12680.3818, 389.971039, -9902.01953)
			CFrameMon = CFrame.new(-13282.3046875, 496.23684692383, -9565.150390625)
			PosMon = Vector3.new(-13282.3046875, 496.23684692383, -9565.150390625)
		elseif MyLevel >= 1975 and MyLevel <= 1999 then
			Ms = "Reborn Skeleton [Lv. 1975]"
			NaemQuest = "HauntedQuest1"
			LevelQuest = 1
			NameMon = "Reborn Skeleton"
			CFrameQuest = CFrame.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			PosQuest = Vector3.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			CFrameMon = CFrame.new(-8817.880859375, 191.16761779785, 6298.6557617188)
			PosMon = Vector3.new(-8817.880859375, 191.16761779785, 6298.6557617188)
		elseif MyLevel >= 2000 and MyLevel <= 2024 then
			Ms = "Living Zombie [Lv. 2000]"
			NaemQuest = "HauntedQuest1"
			LevelQuest = 2
			NameMon = "Living Zombie"
			CFrameQuest = CFrame.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			PosQuest = Vector3.new(-9480.8271484375, 142.13066101074, 5566.0712890625)
			CFrameMon = CFrame.new(-10125.234375, 183.94705200195, 6242.013671875)
			PosMon = Vector3.new(-10125.234375, 183.94705200195, 6242.013671875)
		elseif MyLevel >= 2025 and MyLevel <= 2049  then
			Ms = "Demonic Soul [Lv. 2025]" 
			NaemQuest = "HauntedQuest2"
			LevelQuest = 1
			NameMon = "Demonic Soul"
			CFrameQuest = CFrame.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			PosQuest = Vector3.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			CFrameMon = CFrame.new(-9712.03125, 204.69589233398, 6193.322265625)
			PosMon = Vector3.new(-9712.03125, 204.69589233398, 6193.322265625)
		elseif MyLevel >= 2050 and MyLevel <= 2074  then
			Ms = "Posessed Mummy [Lv. 2050]"
			NaemQuest = "HauntedQuest2"
			LevelQuest = 2
			NameMon = "Posessed Mummy"
			CFrameQuest = CFrame.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			PosQuest = Vector3.new(-9516.9931640625, 178.00651550293, 6078.4653320313)
			CFrameMon = CFrame.new(-9545.7763671875, 69.619895935059, 6339.5615234375)    
			PosMon = Vector3.new(-9545.7763671875, 69.619895935059, 6339.5615234375)
		elseif MyLevel >= 2075 and MyLevel <= 2099  then
			Ms = "Peanut Scout [Lv. 2075]"
			NaemQuest = "NutsIslandQuest"
			LevelQuest = 1
			NameMon = "Peanut Scout"
			CFrameQuest = CFrame.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			PosQuest = Vector3.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			CFrameMon = CFrame.new(-2265.89014, 89.7506104, -10261.2197, -0.809553444, -9.26727282e-08, 0.587046146, -5.44419549e-08, 1, 8.27857534e-08, -0.587046146, 3.50595535e-08, -0.809553444)
			PosMon = Vector3.new(-2265.89014, 89.7506104, -10261.2197, -0.809553444, -9.26727282e-08, 0.587046146, -5.44419549e-08, 1, 8.27857534e-08, -0.587046146, 3.50595535e-08, -0.809553444)
		elseif MyLevel >= 2100 and MyLevel <= 2124  then
			Ms = "Peanut President [Lv. 2100]"
			NaemQuest = "NutsIslandQuest"
			LevelQuest = 2
			NameMon = "Peanut President"
			CFrameQuest = CFrame.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			PosQuest = Vector3.new(-2103.04883, 38.1041756, -10193.2646, 0.744396865, -3.04309395e-08, 0.667737424, -2.1975902e-08, 1, 7.00720548e-08, -0.667737424, -6.6835554e-08, 0.744396865)
			CFrameMon = CFrame.new(-2062.11792, 86.0444489, -10481.1445, 0.834163189, -9.79785408e-09, -0.551517665, -2.60617616e-09, 1, -2.17070646e-08, 0.551517665, 1.95445864e-08, 0.834163189)
			PosMon = Vector3.new(-2062.11792, 86.0444489, -10481.1445, 0.834163189, -9.79785408e-09, -0.551517665, -2.60617616e-09, 1, -2.17070646e-08, 0.551517665, 1.95445864e-08, 0.834163189)
		elseif MyLevel >= 2125 and MyLevel <= 2149  then
			Ms = "Ice Cream Chef [Lv. 2125]"
			NaemQuest = "IceCreamIslandQuest"
			LevelQuest = 1
			NameMon = "Ice Cream Chef"
			CFrameQuest = CFrame.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			PosQuest = Vector3.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			CFrameMon = CFrame.new(-875.441345, 107.871437, -11253.3691, 0.630182087, 5.98710486e-08, 0.776447415, -6.03229751e-08, 1, -2.81494827e-08, -0.776447415, -2.90983202e-08, 0.630182087)
			PosMon = Vector3.new(-875.441345, 107.871437, -11253.3691, 0.630182087, 5.98710486e-08, 0.776447415, -6.03229751e-08, 1, -2.81494827e-08, -0.776447415, -2.90983202e-08, 0.630182087)
		elseif MyLevel > 2150 then
			Ms = "Ice Cream Commander [Lv. 2150]"
			NaemQuest = "IceCreamIslandQuest"
			LevelQuest = 2
			NameMon = "Ice Cream Commander"
			CFrameQuest = CFrame.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			PosQuest = Vector3.new(-821.356079, 65.819519, -10963.4785, 0.773735404, -8.29448581e-08, -0.633508921, 9.66429141e-08, 1, -1.28945574e-08, 0.633508921, -5.12471701e-08, 0.773735404)
			CFrameMon = CFrame.new(-643.3078, 140.913528, -11334.7109, -0.996822715, -9.07818087e-09, 0.0796525627, -1.43212509e-08, 1, -6.52529906e-08, -0.0796525627, -6.61863808e-08, -0.996822715)
			PosMon = Vector3.new(-643.3078, 140.913528, -11334.7109, -0.996822715, -9.07818087e-09, 0.0796525627, -1.43212509e-08, 1, -6.52529906e-08, -0.0796525627, -6.61863808e-08, -0.996822715)
		end
	end
end

spawn(function()
    pcall(function()
        while task.wait() do
            if _G.FarmLevel then
                if not game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    local Noclip = Instance.new("BodyVelocity")
                    Noclip.Name = "BodyClip"
                    Noclip.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
                    Noclip.MaxForce = Vector3.new(100000,100000,100000)
                    Noclip.Velocity = Vector3.new(0,0,0)
                end
            else
                if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
                end
            end
        end
    end)
end)



function EquipWeapon(ToolSe)
    if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
        local tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
        wait(.1)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
    end
end

function UnEquipAll()
    game.Players.LocalPlayer.Character.Humanoid:UnequipTools()
end 

spawn(function()
    while true do game:GetService("RunService").RenderStepped:Wait()
        if syn and  game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
            setfflag("HumanoidParallelRemoveNoPhysics", "False")
            setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
            setfflag("CrashPadUploadToBacktraceToBacktraceBaseUrl", "")
            setfflag("CrashUploadToBacktracePercentage", "0")
            setfflag("CrashUploadToBacktraceBlackholeToken", "")
            setfflag("CrashUploadToBacktraceWindowsPlayerToken", "")
        end
    end
end)

spawn(function()
    while wait() do
        pcall(function()
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if _G.FarmLevel and StartMagnet then
                    if v.Name == Ms and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
                        if v.Name == "Factory Staff [Lv. 800]" then
                            if (v.HumanoidRootPart.Position - PosMon.Position).Magnitude <= 250 then
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                v.Humanoid.WalkSpeed = 0
                                v.Humanoid.JumpPower = 0
                                v.HumanoidRootPart.CFrame = PosMon
                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                            end
                        elseif v.Name == Ms then
                            if (v.HumanoidRootPart.Position - PosMon.Position).Magnitude <= 280 then
                                v.Head.CanCollide = false
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Anchored = false
                                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                v.Humanoid.WalkSpeed = 0
                                v.Humanoid.JumpPower = 0
                                v.Humanoid:ChangeState(11)
                                v.HumanoidRootPart.CFrame = PosMon
                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                            end
                        end
                    end
                end
            end
        end)
    end
end)

spawn(function()
    while game:GetService("RunService").RenderStepped:wait() do
        if _G.FarmLevel then
            pcall(function()
                for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                    if v.Name == "Humanoid" then
                        v.PlatformStand = true
                    end
                end
            end)
        end
    end
end)

spawn(function()
    while game:GetService("RunService").RenderStepped:wait() do
        if _G.FarmLevel then
            pcall(function()
                for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                    if v.Name == Ms then
                        v.Humanoid:ChangeState(11)
                    end
                end
            end)
        end
    end
end)

spawn(function()
    while wait(.1) do
        pcall(function()
            if _G.FarmLevel then
                PointStats = game:GetService("Players").LocalPlayer.Data.Points.Value
                if game:GetService("Players").LocalPlayer.Data.Stats.Melee.Level.Value >= 2200 then
                    _G.Defense = true
                else
                    _G.Melee = true
                end
            end
            if _G.Melee then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee", PointStats)
            end
            if _G.Defense then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense", PointStats)
            end
        end)
    end
end)

spawn(function()
	while wait(.5) do
		if _G.FarmLevel and game:GetService("Players").LocalPlayer:FindFirstChild("WeaponAssetCache") then
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
				ToolWeapon = "Combat"
			end   
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				UnEquipAll()
				ToolWeapon = "Black Leg"
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				UnEquipAll()
				ToolWeapon = "Electro"
			end
			if ggame:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				ToolWeapon = "Fishman Karate"
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 299 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				ToolWeapon = "Dragon Claw"
			end
			
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
			end   
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward", "DragonClaw", "2")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward", "DragonClaw", "2")
			end
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
			end
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300 and game.Players.LocalPlayer.Character.Humanoid.Health > 0 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
			end 
		end
	end
end)

spawn(function()
    while wait() do
        if _G.FarmLevel then
            kkii = require(game.ReplicatedStorage.Util.CameraShaker)
            kkii:Stop()
        end
    end
end)

spawn(function()
	pcall(function()
		while wait() do
			if _G.FarmLevel then
				function UseCode(Text)
					game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(Text)
				end
				UseCode("fudd10_v2")
				UseCode("3BVISITS")
				UseCode("UPD16")
				UseCode("SUB2GAMERROBOT_EXP1")
				UseCode("StrawHatMaine")
				UseCode("Sub2OfficialNoobie")
				UseCode("FUDD10")
				UseCode("THEGREATACE")
				UseCode("Axiore")
				UseCode("SUB2NOOBMASTER123")
				UseCode("Sub2Daigrock")
				UseCode("TantaiGaming")
				UseCode("UPD15")
				UseCode("XMASEXP")
			end
		end
	end)
end)






btns:Toggle("Auto Fram",false, function(v)
    
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
    _G.FarmLevel = v
    _G.FastAttackOpen = v
    if v == false then
		wait(.1)
		TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
	end
end)

function Code(Text)
	game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(Text)
end

btns:Button("Destroy Animation", function()
	pcall(function()
		game:GetService("ReplicatedStorage").Assets.GUI:Destroy()
		game:GetService("ReplicatedStorage").Assets.SlashHit:Destroy()
		game:GetService("ReplicatedStorage").Effect.Container:Destroy()
	end)
end)

btns:Button("FPS Boost", function()
	local decalsyeeted = true
	local g = game
	local w = g.Workspace
	local l = g.Lighting
	local t = w.Terrain
	t.WaterWaveSize = 0
	t.WaterWaveSpeed = 0
	t.WaterReflectance = 0
	t.WaterTransparency = 0
	l.GlobalShadows = false
	l.FogEnd = 9e9
	l.Brightness = 0
	settings().Rendering.QualityLevel = "Level01"
	for i, v in pairs(g:GetDescendants()) do
		if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
			v.Material = "Plastic"
			v.Reflectance = 0
		elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
			v.Transparency = 1
		elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
			v.Lifetime = NumberRange.new(0)
		elseif v:IsA("Explosion") then
			v.BlastPressure = 1
			v.BlastRadius = 1
		elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
			v.Enabled = false
		elseif v:IsA("MeshPart") then
			v.Material = "Plastic"
			v.Reflectance = 0
			v.TextureID = 10385902758728957
		end
	end
	for i, e in pairs(l:GetChildren()) do
		if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
			e.Enabled = false
		end
	end
end)


btns:Button("Rejoin", function()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").LocalPlayer)
end)


btns:Toggle("Bring Fruits | No Work",false, function(v)
    _G.BringFruits = v
end)



   local RigC = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework) 
   local VirtualUser = game:GetService('VirtualUser')
   local kkii = require(game.ReplicatedStorage.Util.CameraShaker)
   spawn(function()
       while game:GetService("RunService").RenderStepped:wait() do
           if _G.FastAttack and _G.FarmLevel then
               pcall(function()
                RigC.activeController.timeToNextAttack = 0
                RigC.activeController.attacking = false
                RigC.activeController.blocking = false
                RigC.activeController.timeToNextAttack = 0
                RigC.activeController.timeToNextBlock = 0
                RigC.activeController.increment = 3
                RigC.activeController.hitboxMagnitude = 100
                game.Players.LocalPlayer.Character.Stun.Value = 0
                game.Players.LocalPlayer.Character.Humanoid.Sit = false
                kkii:Stop()
               end)
           end
       end
   end)

spawn(function()   
     game:GetService('RunService').Stepped:Connect(function()
        if _G.DeleteEffect then
            for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
                if v.Name == "CurvedRing" or v.Name == "SlashHit" or v.Name == "SwordSlash" or v.Name == "Sounds" then
                    v:Destroy() 
                end
            end
        end
    end)
end)

btns:Toggle("Delete Effect",false, function(v)
    _G.DeleteEffect = v
end)

btns:Seperator()




btns:Button("Super Fastattack", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Stepzaza123/Fast-Attack/main/sadasd"))();
end)

local serv = win:Server("TP","")
local btns = serv:Channel("")

btns:Button("Starter island", function()
	function topos(Para1)
		Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
		if Distance <= 300 then
			Speed = 99999
		elseif Distance >= 400 then
			Speed = 270
		end
		game:GetService("TweenService"):Create(
			game.Players.LocalPlayer.Character.HumanoidRootPart,
			TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
			{CFrame = Para1}
		):Play()
	end
	topos(CFrame.new(975.259216, 16.5166225, 1430.25183, 0.0946362317, -4.51618369e-08, 0.995511949, 7.76327838e-08, 1, 3.79854441e-08, -0.995511949, 7.36895629e-08, 0.0946362317))
	end)
	btns:Button("Jundle island", function()
		function topos(Para1)
			Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
			if Distance <= 300 then
				Speed = 99999
			elseif Distance >= 400 then
				Speed = 270
			end
			game:GetService("TweenService"):Create(
				game.Players.LocalPlayer.Character.HumanoidRootPart,
				TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
				{CFrame = Para1}
			):Play()
		end
		topos(CFrame.new(-1325.01001, 11.9785004, 500.661987, 1, 0, 0, 0, 1, 0, 0, 0, 1))
		end)
		btns:Button("Middel Town", function()
			function topos(Para1)
				Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
				if Distance <= 300 then
					Speed = 99999
				elseif Distance >= 400 then
					Speed = 270
				end
				game:GetService("TweenService"):Create(
					game.Players.LocalPlayer.Character.HumanoidRootPart,
					TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
					{CFrame = Para1}
				):Play()
			end
			topos(CFrame.new(-1210.8717, 7.65221119, 1702.86597, -0.938877583, -0, -0.344251096, -0, 1, -0, 0.344251066, 0, -0.938877702))
			end)btns:Button("Pirate Island", function()
				function topos(Para1)
					Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
					if Distance <= 300 then
						Speed = 99999
					elseif Distance >= 400 then
						Speed = 270
					end
					game:GetService("TweenService"):Create(
						game.Players.LocalPlayer.Character.HumanoidRootPart,
						TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
						{CFrame = Para1}
					):Play()
				end
				topos(CFrame.new(-1178.1947, 4.75206375, 3848.43433, -0.921633065, 0, 0.388062507, 0, 1.00000012, -0, -0.388062447, 0, -0.921633184))
				end)
				btns:Button("Desert", function()
					function topos(Para1)
						Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
						if Distance <= 300 then
							Speed = 99999
						elseif Distance >= 400 then
							Speed = 270
						end
						game:GetService("TweenService"):Create(
							game.Players.LocalPlayer.Character.HumanoidRootPart,
							TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
							{CFrame = Para1}
						):Play()
					end
					topos(CFrame.new(924.859741, 8.69319725, 4129.99219, 0.126468331, 0, 0.991970658, -0, 1, -0, -0.991970658, 0, 0.126468331))
					end)
					btns:Button("Snow island", function()
						function topos(Para1)
							Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
							if Distance <= 300 then
								Speed = 99999
							elseif Distance >= 400 then
								Speed = 270
							end
							game:GetService("TweenService"):Create(
								game.Players.LocalPlayer.Character.HumanoidRootPart,
								TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
								{CFrame = Para1}
							):Play()
						end
						topos(CFrame.new(1024.35596, 110.575089, -1419.44958, -0.105104171, 0, 0.994461238, 0, 1, -0, -0.994461238, 0, -0.105104171))
						end)
						btns:Button("Marine Ford", function()
							function topos(Para1)
								Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								if Distance <= 300 then
									Speed = 99999
								elseif Distance >= 400 then
									Speed = 270
								end
								game:GetService("TweenService"):Create(
									game.Players.LocalPlayer.Character.HumanoidRootPart,
									TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
									{CFrame = Para1}
								):Play()
							end
							topos(CFrame.new(-5003.92871, 20.6520424, 4283.73242, -0.608482778, 0, 0.793567061, 0, 1, -0, -0.793567061, 0, -0.608482778))
							end)
							btns:Button("Sky Piea1", function()
								function topos(Para1)
									Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
									if Distance <= 300 then
										Speed = 99999
									elseif Distance >= 400 then
										Speed = 270
									end
									game:GetService("TweenService"):Create(
										game.Players.LocalPlayer.Character.HumanoidRootPart,
										TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
										{CFrame = Para1}
									):Play()
								end
								topos(CFrame.new(-4983.44434, 717.821594, -2597.7627, 0.419786662, 4.0075161e-08, -0.907622814, 4.08414361e-12, 1, 4.41558718e-08, 0.907622814, -1.85397528e-08, 0.419786662))
								end)
								btns:Button("Sky Piea2", function()
									function topos(Para1)
										Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
										if Distance <= 300 then
											Speed = 99999
										elseif Distance >= 400 then
											Speed = 270
										end
										game:GetService("TweenService"):Create(
											game.Players.LocalPlayer.Character.HumanoidRootPart,
											TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
											{CFrame = Para1}
										):Play()
									end
									topos(CFrame.new(-4657.50977, 872.542603, -1768.026, 0.897209466, 1.80802555e-08, 0.44160524, -2.38629276e-08, 1, 7.54019158e-09, -0.44160524, -1.7303126e-08, 0.897209466))
									end)
									btns:Button("Sky Piea3", function()
										function topos(Para1)
											Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
											if Distance <= 300 then
												Speed = 99999
											elseif Distance >= 400 then
												Speed = 270
											end
											game:GetService("TweenService"):Create(
												game.Players.LocalPlayer.Character.HumanoidRootPart,
												TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
												{CFrame = Para1}
											):Play()
										end
										topos(CFrame.new(-7901.50781, 5545.4917, -400.504211, -0.272922754, -0, -0.962035954, -0, 1, -0, 0.962035954, 0, -0.272922754))
										end)
										btns:Button("Colosseum", function()
											function topos(Para1)
												Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
												if Distance <= 300 then
													Speed = 99999
												elseif Distance >= 400 then
													Speed = 270
												end
												game:GetService("TweenService"):Create(
													game.Players.LocalPlayer.Character.HumanoidRootPart,
													TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
													{CFrame = Para1}
												):Play()
											end
											topos(CFrame.new(-1496.87976, 7.38922977, -2930.30078, 0.982194006, 0, -0.18786934, -0, 1, -0, 0.18786931, 0, 0.982194126))
											end)
											btns:Button("Magma Island", function()
												function topos(Para1)
													Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
													if Distance <= 300 then
														Speed = 2000
													elseif Distance >= 400 then
														Speed = 270
													end
													game:GetService("TweenService"):Create(
														game.Players.LocalPlayer.Character.HumanoidRootPart,
														TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
														{CFrame = Para1}
													):Play()
												end
												topos(CFrame.new(-5227.00732, 8.71570873, 8440.12207, -0.396634072, -3.4869533e-08, 0.917976797, -5.26531085e-09, 1, 3.57101939e-08, -0.917976797, 9.33044664e-09, -0.396634072))
												end)
												btns:Button("Mob Island", function()
													function topos(Para1)
														Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
														if Distance <= 300 then
															Speed = 2000
														elseif Distance >= 400 then
															Speed = 270
														end
														game:GetService("TweenService"):Create(
															game.Players.LocalPlayer.Character.HumanoidRootPart,
															TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
															{CFrame = Para1}
														):Play()
													end
													topos(CFrame.new(-2851.60278, 7.39225721, 5356.18018, -0.983235121, 0, 0.182342738, 0, 1, -0, -0.182342753, 0, -0.983235002))
													end)
													btns:Button("Water island", function()
														function topos(Para1)
															Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
															if Distance <= 300 then
																Speed = 2000
															elseif Distance >= 400 then
																Speed = 270
															end
															game:GetService("TweenService"):Create(
																game.Players.LocalPlayer.Character.HumanoidRootPart,
																TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
																{CFrame = Para1}
															):Play()
														end
														topos(CFrame.new(5172.84473, 31.863636, 4130.29443, 0.164557353, 0, -0.986367524, -0, 1, -0, 0.986367524, 0, 0.164557353))
														end)
														btns:Button("Prison island", function()
															function topos(Para1)
																Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
																if Distance <= 300 then
																	Speed = 2000
																elseif Distance >= 400 then
																	Speed = 270
																end
																game:GetService("TweenService"):Create(
																	game.Players.LocalPlayer.Character.HumanoidRootPart,
																	TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
																	{CFrame = Para1}
																):Play()
															end
															topos(CFrame.new(4853.2124, 5.77740622, 733.322388, -0.0105576077, -7.77419107e-09, -0.99994427, -1.08353271e-09, 1, -7.76318476e-09, 0.99994427, 1.00151165e-09, -0.0105576077))
															end)
															btns:Button("underWater island", function()
																function topos(Para1)
																	Distance = (Para1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
																	if Distance <= 300 then
																		Speed = 2000
																	elseif Distance >= 400 then
																		Speed = 270
																	end
																	game:GetService("TweenService"):Create(
																		game.Players.LocalPlayer.Character.HumanoidRootPart,
																		TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
																		{CFrame = Para1}
																	):Play()
																end
																topos(CFrame.new(61163.8516, 11.6796875, 1819.78418, 1, 0, 0, 0, 1, 0, 0, 0, 1))
																end)

																local tgls = serv:Channel("dungeon")

                                                  tgls:Toggle("Kill Aura",false, function(bool)
													for i,v in pairs(game:GetService("Workspace").Enemies:GetDescendants()) do
														if v.Name == "HumanoidRootPart" then
															v.Parent.Humanoid.Health = 0
															v.Parent.HumanoidRootPart.Size = Vector3.new(20,20,20)
															v.Parent.HumanoidRootPart.CanCollide = false
															v.Parent.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * Cframe.new(0,20,0)
															
															sethiddenprooperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
														end
													end
                                                 end)
