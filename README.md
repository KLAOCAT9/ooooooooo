#local PlaceId = game.PlaceId
if PlaceId == 2753915549 then
    Sea1 = true
elseif PlaceId == 4442272183 then
    Sea2 = true
elseif PlaceId == 7449423635 then
    Sea3 = true
end
function CheckQuest()
        local Lv = game:GetService("Players").LocalPlayer.Data.Level.Value
            if Sea1 then
            if Lv == 1 or Lv <= 9 then
                Mon = "Bandit [Lv. 5]"
                NameMon = "Bandit"
                LvQuest = 1
                NameQuest = "BanditQuest1"
                CFrameMon = CFrame.new(1038.2711181640625, 24.537282943725586, 1550.2586669921875)
                CFrameQuest = CFrame.new(1059.8109130859375, 16.362747192382812, 1549.0882568359375)
            elseif Lv == 10 or Lv <= 14 then
                Mon = "Monkey [Lv. 14]"
                NameMon = "Monkey"
                LvQuest = 1
                NameQuest = "JungleQuest"
                CFrameMon = CFrame.new(-1443.7662353515625, 61.851966857910156, -47.555946350097656)
                CFrameQuest = CFrame.new(-1599.8194580078125, 36.852149963378906, 153.0706024169922)
            elseif Lv == 15 or Lv <= 29 then
                Mon = "Gorilla [Lv. 20]"
                NameMon = "Gorilla"
                LvQuest = 2
                NameQuest = "JungleQuest"
                CFrameMon = CFrame.new(-1443.7662353515625, 61.851966857910156, -47.555946350097656)
                CFrameQuest = CFrame.new(-1599.8194580078125, 36.852149963378906, 153.0706024169922)
elseif Lv == 30 or Lv <= 39 then
Mon = "Pirate [Lv. 35]"
NameMon = "Pirate"
CFrameMon = CFrame.new(-988.5272827148438, 13.752047538757324, 4031.7265625)
CFrameQuest = CFrame.new(-1141.374755859375, 4.752062797546387, 3829.837646484375)
NameQuest = "BuggyQuest1"
LvQuest = 1
elseif Lv == 40 or Lv <= 58 then
Mon = "Brute [Lv. 45]"
NameMon = "Brute"
CFrameMon = CFrame.new(-1178.796142578125, 32.562164306640625, 4164.41357421875)
CFrameQuest = CFrame.new(-1141.374755859375, 4.752062797546387, 3829.837646484375)
NameQuest = "BuggyQuest1"
LvQuest = 2
elseif Lv == 60 or Lv <= 74 then
Mon = "Desert Bandit [Lv. 60]"
NameMon = "Desert Bandit"
CFrameMon = CFrame.new(923.748046875, 6.448704719543457, 4491.7626953125)
CFrameQuest = CFrame.new(895.619873046875, 6.438474178314209, 4391.48828125)
NameQuest = "DesertQuest"
LvQuest = 1
elseif Lv == 75 or Lv <= 89 then
Mon = "Desert Officer [Lv. 70]"
NameMon = "Desert Officer"
CFrameMon = CFrame.new(1607.8001708984375, 7.313505172729492, 4370.998046875)
CFrameQuest = CFrame.new(895.619873046875, 6.438474178314209, 4391.48828125)
NameQuest = "DesertQuest"
LvQuest = 2
elseif Lv == 90 or Lv <= 99 then
Mon = "Snow Bandit [Lv. 90]"
NameMon = "Snow Bandit"
CFrameMon = CFrame.new(1376.412353515625, 97.25218200683594, -1397.505126953125)
CFrameQuest = CFrame.new(1388.5697021484375, 87.2574691772461, -1297.89306640625)
NameQuest = "SnowQuest"
LvQuest = 1
elseif Lv == 100 or Lv <= 119 then
Mon = "Snowman [Lv. 100]"
NameMon = "Snowman"
CFrameMon = CFrame.new(1258.1685791015625, 87.27262115478516, -1688.7796630859375)
CFrameQuest = CFrame.new(1388.5697021484375, 87.2574691772461, -1297.89306640625)
NameQuest = "SnowQuest"
LvQuest = 2
elseif Lv == 120 or Lv <= 149 then
Mon = "Chief Petty Officer [Lv. 120]"
NameMon = "Chief Petty Officer"
CFrameMon = CFrame.new(-4695.87548828125, 20.652050018310547, 4505.2001953125)
CFrameQuest = CFrame.new(-5037.91357421875, 28.652050018310547, 4324.27685546875)
NameQuest = "MarineQuest2"
LvQuest = 1
elseif Lv == 150 or Lv <= 173 then
Mon = "Sky Bandit [Lv. 150]"
NameMon = "Sky Bandit"
CFrameMon = CFrame.new(-5026.087890625, 278.067138671875, -2786.537109375)
CFrameQuest = CFrame.new(-4839.85009765625, 717.6693725585938, -2621.01513671875)
NameQuest = "SkyQuest"
LvQuest = 1
elseif Lv == 175 or Lv <= 189 then
Mon = "Dark Master [Lv. 175]"
NameMon = "Dark Master"
CFrameMon = CFrame.new(-5237.103515625, 388.6519470214844, -2303.81298828125)
CFrameQuest = CFrame.new(-4839.85009765625, 717.6693725585938, -2621.01513671875)
NameQuest = "SkyQuest"
LvQuest = 2
elseif Lv == 190 or Lv <= 209 then
Mon = "Prisoner [Lv. 190]"
NameMon = "Prisoner"
CFrameMon = CFrame.new(5162.3154296875, 3.351527214050293, 420.5860290527344)
CFrameQuest = CFrame.new(5308.69287109375, 1.6552369594573975, 476.1368103027344)
NameQuest = "PrisonerQuest"
LvQuest = 1
elseif Lv == 210 or Lv <= 274 then
Mon = "Dangerous Prisoner [Lv. 210]"
NameMon = "Dangerous Prisoner"
CFrameMon = CFrame.new(5608.6044921875, 1.6335886716842651, 670.66748046875)
CFrameQuest = CFrame.new(5308.69287109375, 1.6552369594573975, 476.1368103027344)
NameQuest = "PrisonerQuest"
LvQuest = 2
elseif Lv == 210 or Lv <= 244 then
Mon = "Toga Warrior [Lv. 250]"
NameMon = "Toga Warrior"
CFrameMon = CFrame.new(-1864.71142578125, 7.442556381225586, -2907.124755859375)
CFrameQuest = CFrame.new(-1579.3824462890625, 7.389348983764648, -2984.995849609375)
NameQuest = "ColosseumQuest"
LvQuest = 1
elseif Lv == 275 or Lv <= 298 then
Mon = "Gladiator [Lv. 275]"
NameMon = "Gladiator"
CFrameMon = CFrame.new(-1401.1207275390625, 7.442556381225586, -3117.96728515625)
CFrameQuest = CFrame.new(-1579.3824462890625, 7.389348983764648, -2984.995849609375)
NameQuest = "ColosseumQuest"
LvQuest = 2
elseif Lv == 300 or Lv <= 323 then
Mon = "Military Soldier [Lv. 300]"
NameMon = "Military Soldier"
CFrameMon = CFrame.new(-5277.33056640625, 26.809797286987305, 8614.669921875)
CFrameQuest = CFrame.new(-5314.8828125, 12.236712455749512, 8515.8876953125)
NameQuest = "MagmaQuest"
LvQuest = 1
elseif Lv == 325 or Lv <= 374 then
Mon = "Military Spy [Lv. 325]"
NameMon = "Military Spy"
CFrameMon = CFrame.new(-5773.30517578125, 82.96986389160156, 8761.5458984375)
CFrameQuest = CFrame.new(-5314.8828125, 12.236712455749512, 8515.8876953125)
NameQuest = "MagmaQuest"
LvQuest = 2
elseif Lv == 375 or Lv <= 399 then
Mon = "Fishman Warrior [Lv. 375]"
NameMon = "Fishman Warrior"
CFrameMon = CFrame.new(60899.3828125, 18.482830047607422, 1594.455078125)
CFrameQuest = CFrame.new(61122.31640625, 18.47164535522461, 1565.877685546875)
NameQuest = "FishmanQuest"
LvQuest = 1
elseif Lv == 400 or Lv <= 449 then
Mon = "Fishman Commando [Lv. 400]"
NameMon = "Fishman Commando"
CFrameMon = CFrame.new(60899.3828125, 18.482830047607422, 1594.455078125)
CFrameQuest = CFrame.new(61122.31640625, 18.47164535522461, 1565.877685546875)
NameQuest = "FishmanQuest"
LvQuest = 2
elseif Lv == 450 or Lv <= 473 then
Mon = "God's Guard [Lv. 450]"
NameMon = "God's Guard"
CFrameMon = CFrame.new(-4819.96533203125, 844.3027954101562, -1935.9559326171875)
CFrameQuest = CFrame.new(-4722.841796875, 845.3027954101562, -1953.981689453125)
NameQuest = "SkyExp1Quest"
LvQuest = 1
elseif Lv == 475 or Lv <= 524 then
Mon = "Shanda [Lv. 475]"
NameMon = "Shanda"
CFrameMon = CFrame.new(-7684.23291015625, 5565.015625, -439.2098083496094)
CFrameQuest = CFrame.new(-7860.45556640625, 5545.517578125, -380.8363037109375)
NameQuest = "SkyExp1Quest"
LvQuest = 2
elseif Lv == 525 or Lv <= 549 then
Mon = "Royal Squad [Lv. 525]"
NameMon = "Royal Squad"
CFrameMon = CFrame.new(-7773.08154296875, 5621.552734375, -1358.8348388671875)
CFrameQuest = CFrame.new(-7903.35400390625, 5635.98828125, -1411.6661376953125)
NameQuest = "SkyExp2Quest"
LvQuest = 1
elseif Lv == 550 or Lv <= 624 then
Mon = "Royal Soldier [Lv. 550]"
NameMon = "Royal Soldier"
CFrameMon = CFrame.new(-7835.4453125, 5622.30615234375, -1786.0172119140625)
CFrameQuest = CFrame.new(-7903.35400390625, 5635.98828125, -1411.6661376953125)
NameQuest = "SkyExp2Quest"
LvQuest = 2
elseif Lv == 625 or Lv <= 649 then
Mon = "Galley Pirate [Lv. 625]"
NameMon = "Galley Pirate"
CFrameMon = CFrame.new(5550.44970703125, 85.51802062988281, 4123.072265625)
CFrameQuest = CFrame.new(5258.3759765625, 38.52693176269531, 4048.90380859375)
NameQuest = "FountainQuest"
LvQuest = 1
elseif Lv == 650 or Lv <= 699 then
Mon = "Galley Captain [Lv. 650]"
NameMon = "Galley Captain"
CFrameMon = CFrame.new(5270.01708984375, 0.12784358859062195, 4938.8681640625)
CFrameQuest = CFrame.new(5258.3759765625, 38.52693176269531, 4048.90380859375)
NameQuest = "FountainQuest"
LvQuest = 2
        end 
    end
end
if Sea2 then
local Lv = game.Players.LocalPlayer.Data.Level.Value
if Lv == 700 or Lv <= 724 then
Mon = "Raider [Lv. 700]"
NameMon = "Raider"
LvQuest = 1
NameQuest = "Area1Quest"
CFrameMon = CFrame.new(-379.59521484375, 75.89311218261719, 2676.202880859375)
CFrameQuest = CFrame.new(-428.1158447265625, 72.99632263183594, 1836.0904541015625)
    elseif Lv == 725 or Lv <= 774 then
Mon = "Mercenary [Lv. 725]"
NameMon = "Mercenary"
CFrameMon = CFrame.new(-849.7936401367188, 122.47102355957031, 1481.407470703125)
CFrameQuest = CFrame.new(-428.1158447265625, 72.99632263183594, 1836.0904541015625)
NameQuest = "Area1Quest"
LvQuest = 2
    elseif Lv == 775 or Lv <= 799 then
Mon = "Swan Pirate [Lv. 775]"
NameMon = "Swan Pirate"
CFrameMon = CFrame.new(685.5987548828125, 72.9854965209961, 1284.5538330078125)
CFrameQuest = CFrame.new(636.1425170898438, 73.09632873535156, 917.8521118164062)
NameQuest = "Area2Quest"
LvQuest = 1
    elseif Lv == 800 or Lv <= 874 then
Mon = "Factory Staff [Lv. 800]"
NameMon = "Factory Staff"
CFrameMon = CFrame.new(679.2174072265625, 137.8992156982422, 350.7538146972656)
CFrameQuest = CFrame.new(636.1425170898438, 73.09632873535156, 917.8521118164062)
NameQuest = "Area2Quest"
LvQuest = 2
    elseif Lv == 875 or Lv <= 899 then
Mon = "Marine Lieutenant [Lv. 875]"
NameMon = "Marine Lieutenant"
CFrameMon = CFrame.new(-2752.685791015625, 115.79624938964844, -3354.85888671875)
CFrameQuest = CFrame.new(-2442.25927734375, 73.04188537597656, -3217.06982421875)
NameQuest = "MarineQuest3"
LvQuest = 1
   elseif Lv == 900 or Lv <= 949 then
Mon = "Marine Captain [Lv. 900]"
NameMon = "Marine Captain"
CFrameMon = CFrame.new(-2752.685791015625, 115.79624938964844, -3354.85888671875)
CFrameQuest = CFrame.new(-2442.25927734375, 73.04188537597656, -3217.06982421875)
NameQuest = "MarineQuest3"
LvQuest = 2
   elseif Lv == 950 or Lv <= 974 then
Mon = "Zombie [Lv. 950]"
NameMon = "Zombie"
CFrameMon = CFrame.new(-5595.892578125, 49.967472076416016, -1010.1049194335938)
CFrameQuest = CFrame.new(-5491.50341796875, 48.50592041015625, -794.6982421875)
NameQuest = "ZombieQuest"
LvQuest = 1
   elseif Lv == 975 or Lv <= 999 then
Mon = "Vampire [Lv. 975]"
NameMon = "Vampire"
CFrameMon = CFrame.new(-5788.99755859375, 6.428503036499023, -1200.2452392578125)
CFrameQuest = CFrame.new(-5491.50341796875, 48.50592041015625, -794.6982421875)
NameQuest = "ZombieQuest"
LvQuest = 2
   elseif Lv == 1000 or Lv <= 1049 then
Mon = "Snow Trooper [Lv. 1000]"
NameMon = "Snow Trooper"
CFrameMon = CFrame.new(-2752.685791015625, 115.79624938964844, -3354.85888671875)
CFrameQuest = CFrame.new(-2442.25927734375, 73.04188537597656, -3217.06982421875)
NameQuest = "SnowMountainQuest"
LvQuest = 1
   elseif Lv == 1050 or Lv <= 1099 then
Mon = "Winter Warrior [Lv. 1050]"
NameMon = "Winter Warrior"
CFrameMon = CFrame.new(-2752.685791015625, 115.79624938964844, -3354.85888671875)
CFrameQuest = CFrame.new(-2442.25927734375, 73.04188537597656, -3217.06982421875)
NameQuest = "SnowMountainQuest"
LvQuest = 2
elseif Lv == 1100 or Lv <= 1124 then
Mon = "Lab Subordinate [Lv. 1100]"
NameMon = "Lab Subordinate"
CFrameMon = CFrame.new(-6150.83740234375, 15.97768497467041, -4388.92626953125)
CFrameQuest = CFrame.new(-6062.6689453125, 15.97756290435791, -4903.7060546875)
NameQuest = "IceSideQuest"
LvQuest = 1
elseif Lv == 1125 or Lv <= 1174 then
Mon = "Horned Warrior [Lv. 1125]"
NameMon = "Horned Warrior"
CFrameMon = CFrame.new(-6383.04833984375, 31.631372451782227, -5928.79541015625)
CFrameQuest = CFrame.new(-6062.6689453125, 15.97756290435791, -4903.7060546875)
NameQuest = "IceSideQuest"
LvQuest = 2
elseif Lv == 1175 or Lv <= 1199 then
Mon = "Magma Ninja [Lv. 1175]"
NameMon = "Magma Ninja"
CFrameMon = CFrame.new(-5317.50341796875, 23.80988121032715, -5446.87353515625)
CFrameQuest = CFrame.new(-5430.1708984375, 15.97756290435791, -5293.5537109375)
NameQuest = "FireSideQuest"
LvQuest = 1
elseif Lv == 1200 or Lv <= 1249 then
Mon = "Lava Pirate [Lv. 1200"
NameMon = "Lava Pirate"
CFrameMon = CFrame.new(-5198.43603515625, 21.75054359436035, -5146.00927734375)
CFrameQuest = CFrame.new(-5430.1708984375, 15.97756290435791, -5293.5537109375)
NameQuest = "FireSideQuest"
LvQuest = 2
elseif Lv == 1250 or Lv <= 1299 then
Mon = "Ship Deckhand [Lv. 1250]"
NameMon = "Ship Deckhand"
CFrameMon = CFrame.new(1056.54541015625, 125.0829086303711, 32845.06640625)
CFrameQuest = CFrame.new(1037.679931640625, 125.0829086303711, 32911.9609375)
NameQuest = "ShipQuest1"
LvQuest = 1
elseif Lv == 1300 or Lv <= 1324 then
Mon = "Ship Officer [Lv. 1325]"
NameMon = "Ship Officer"
CFrameMon = CFrame.new(949.9971923828125, 136.58181762695312, 33337.74609375)
CFrameQuest = CFrame.new(968.3858032226562, 125.0829086303711, 33243.62890625)
NameQuest = "ShipQuest2"
LvQuest = 1
elseif Lv == 1325 or Lv <= 1349 then
Mon = "Ship Officer [Lv. 1325]"
NameMon = "Ship Officer"
CFrameMon = CFrame.new(1225.73779296875, 181.17491149902344, 33292.98828125)
CFrameQuest = CFrame.new(968.3858032226562, 125.0829086303711, 33243.62890625)
NameQuest = "ShipQuest2"
LvQuest = 2
elseif Lv == 1350 or Lv <= 1374 then
Mon = "Arctic Warrior [Lv. 1350]"
NameMon = "Arctic Warrior"
CFrameMon = CFrame.new(6133.435546875, 28.39253044128418, -6239.7431640625)
CFrameQuest = CFrame.new(5671.80859375, 28.20246124267578, -6482.96826171875)
NameQuest = "FrostQuest"
LvQuest = 1
elseif Lv == 1375 or Lv <= 1424 then
Mon = "Snow Lurker [Lv. 1375]"
NameMon = "Snow Lurker"
CFrameMon = CFrame.new(5443.203125, 84.44671630859375, -6718.73388671875)
CFrameQuest = CFrame.new(5671.80859375, 28.20246124267578, -6482.96826171875)
NameQuest = "FrostQuest"
LvQuest = 2
elseif Lv == 1425 or Lv <= 1449 then
Mon = "Sea Soldier [Lv. 1425]"
NameMon = "Sea Soldier"
CFrameMon = CFrame.new(-3026.2275390625, 131.7957763671875, -9814.0546875)
CFrameQuest = CFrame.new(-3051.339599609375, 236.87208557128906, -10148.1044921875)
NameQuest = "ForgottenQuest"
LvQuest = 1
elseif Lv == 1450 or Lv <= 1499 then
Mon = "Water Fighter [Lv. 1450]"
NameMon = "Water Fighter"
CFrameMon = CFrame.new(-3188.722412109375, 298.6902770996094, -10592.8134765625)
CFrameQuest = CFrame.new(-3051.339599609375, 236.87208557128906, -10148.1044921875)
NameQuest = "ForgottenQuest"
LvQuest = 2
        end
    end
if Sea3 then
local Lv = game.Players.LocalPlayer.Data.Level.Value
if Lv == 1500 or Lv <= 1524 then
Mon = "Pirate Millionaire [Lv. 1500]"
NameMon = "Pirate Millionaire"
LvQuest = 1
NameQuest = "PiratePortQuest"
CFrameMon = CFrame.new(-459.04425048828125, 43.7557373046875, 5547.62646484375)
CFrameQuest = CFrame.new(-289.9590759277344, 43.81901168823242, 5579.88623046875)
elseif Lv == 1525 or Lv <= 1574 then
Mon = "Pistol Billionaire [Lv. 1525]"
NameMon = "Pistol Billionaire"
CFrameMon = CFrame.new(-475.5018615722656, 73.75572204589844, 5839.98046875)
CFrameQuest = CFrame.new(-289.9590759277344, 43.81901168823242, 5579.88623046875)
NameQuest = "PiratePortQuest"
LvQuest = 2
elseif Lv == 1575 or Lv <= 1599 then
Mon = "Dragon Crew Warrior [Lv. 1575]"
NameMon = "Dragon Crew Warrior"
CFrameMon = CFrame.new(5832.55078125, 51.37715530395508, -1105.109619140625)
CFrameQuest = CFrame.new(5832.55078125, 51.37715530395508, -1105.109619140625)
NameQuest = "AmazonQuest"
LvQuest = 1
elseif Lv == 1600 or Lv <= 1524 then
Mon = "Dragon Crew Archer [Lv. 1600]"
NameMon = "Dragon Crew Archer"
CFrameMon = CFrame.new(6492.38720703125, 338.295654296875, -116.89198303222656)
CFrameQuest = CFrame.new(5832.55078125, 51.37715530395508, -1105.109619140625)
NameQuest = "AmazonQuest"
LvQuest = 2
elseif Lv == 1625 or Lv <= 1649 then
Mon = "Female Islander [Lv. 1625]"
NameMon = "Female Islander"
CFrameMon = CFrame.new(4787.7841796875, 700.1817626953125, 977.4163818359375)
CFrameQuest = CFrame.new(5444.22021484375, 601.6294555664062, 752.4744262695312)
NameQuest = "AmazonQuest"
LvQuest = 1
elseif Lv == 1650 or Lv <= 1699 then
Mon = "Giant Islander [Lv. 1650]"
NameMon = "Giant Islander"
CFrameMon = CFrame.new(5543.08203125, 601.594970703125, -350.8583679199219)
CFrameQuest = CFrame.new(5444.22021484375, 601.6294555664062, 752.4744262695312)
NameQuest = "AmazonQuest"
LvQuest = 2
elseif Lv == 1700 or Lv <= 1724 then
Mon = "Giant Islander [Lv. 1650]"
NameMon = "Giant Islander"
CFrameMon = CFrame.new(2511.83984375, 87.39913177490234, -7236.78369140625)
CFrameQuest = CFrame.new(2178.9951171875, 28.731239318847656, -6739.1884765625)
NameQuest = "MarineTreeIsland"
LvQuest = 1
elseif Lv == 1725 or Lv <= 1774 then
Mon = "Giant Islander [Lv. 1650]"
NameMon = "Giant Islander"
CFrameMon = CFrame.new(3621.549072265625, 160.5498504638672, -6968.73779296875)
CFrameQuest = CFrame.new(2178.9951171875, 28.731239318847656, -6739.1884765625)
NameQuest = "MarineTreeIsland"
LvQuest = 2
elseif Lv == 1775 or Lv <= 1799 then
Mon = "Fishman Raider [Lv. 1775]"
NameMon = "Fishman Raider"
CFrameMon = CFrame.new(-10701.87890625, 331.7884216308594, -8274.6484375)
CFrameQuest = CFrame.new(-10583.04296875, 331.78839111328125, -8754.779296875)
NameQuest = "DeepForestIsland3"
LvQuest = 1
elseif Lv == 1800 or Lv <= 1899 then
Mon = "Fishman Captain [Lv. 1800]"
NameMon = "Fishman Captain"
CFrameMon = CFrame.new(-11283.9619140625, 331.7489929199219, -9004.1513671875)
CFrameQuest = CFrame.new(-10583.04296875, 331.78839111328125, -8754.779296875)
NameQuest = "DeepForestIsland3"
LvQuest = 2
elseif Lv == 1900 or Lv <= 1924 then
Mon = "Jungle Pirate [Lv. 1900]"
NameMon = "Jungle Pirate"
CFrameMon = CFrame.new(-12270.6025390625, 465.96783447265625, -10254.17578125)
CFrameQuest = CFrame.new(-12686.134765625, 390.886474609375, -9901.1728515625)
NameQuest = "DeepForestIsland2"
LvQuest = 1
elseif Lv == 1925 or Lv <= 1974 then
Mon = "Musketeer Pirate [Lv. 1925]"
NameMon = "Musketeer Pirate"
CFrameMon = CFrame.new(-13458.630859375, 391.5714416503906, -9859.1064453125)
CFrameQuest = CFrame.new(-12686.134765625, 390.886474609375, -9901.1728515625)
NameQuest = "DeepForestIsland2"
LvQuest = 2
elseif Lv == 1975 or Lv <= 1999 then
Mon = "Reborn Skeleton [Lv. 1975]"
NameMon = "Reborn Skeleton"
CFrameMon = CFrame.new(-8766.974609375, 190.4741973876953, 6272.3095703125)
CFrameQuest = CFrame.new(-9484.8427734375, 142.130615234375, 5567.34814453125)
NameQuest = "HauntedQuest1"
LvQuest = 1
elseif Lv == 2000 or Lv <= 2024 then
Mon = "Living Zombie [Lv. 2000]"
NameMon = "Living Zomb"
CFrameMon = CFrame.new(-10232.4052734375, 144.9747314453125, 6100.9384765625)
CFrameQuest = CFrame.new(-9484.8427734375, 142.130615234375, 5567.34814453125)
NameQuest = "HauntedQuest1"
LvQuest = 2
elseif Lv == 2025 or Lv <= 2049 then
Mon = "Demonic Soul [Lv. 2025]"
NameMon = "Demonic Soul"
CFrameMon = CFrame.new(-9272.5546875, 191.3197784423828, 6035.5361328125)
CFrameQuest = CFrame.new(-9513.802734375, 172.130615234375, 6075.21630859375)
NameQuest = "HauntedQuest2"
LvQuest = 1
elseif Lv == 2050 or Lv <= 2074 then
Mon = "Posessed Mummy [Lv. 2050]"
NameMon = "Posessed Mummy"
CFrameMon = CFrame.new(-9584.15625, 6.185522079467773, 6205.2607421875)
CFrameQuest = CFrame.new(-9513.802734375, 172.130615234375, 6075.21630859375)
NameQuest = "HauntedQuest2"
LvQuest = 2
elseif Lv == 2075 or Lv <= 2099 then
Mon = "Peanut Scout [Lv. 2075]"
NameMon = "Peanut Scout"
CFrameMon = CFrame.new(-1959.8287353515625, 88.63423156738281, -10249.7041015625)
CFrameQuest = CFrame.new(-2102.507568359375, 38.1290397644043, -10190.091796875)
NameQuest = "NutsIslandQuest"
LvQuest = 1
elseif Lv == 2100 or Lv <= 2124 then
Mon = "Peanut President [Lv. 2100]"
NameMon = "Peanut President"
CFrameMon = CFrame.new(-2323.180419921875, 88.31880950927734, -10536.3583984375)
CFrameQuest = CFrame.new(-2102.507568359375, 38.1290397644043, -10190.091796875)
NameQuest = "NutsIslandQuest"
LvQuest = 2
elseif Lv == 2125 or Lv <= 2149 then
Mon = "Ice Cream Chef [Lv. 2125]"
NameMon = "Ice Cream Chef"
CFrameMon = CFrame.new(-823.4948120117188, 65.84532928466797, -10962.1982421875)
CFrameQuest = CFrame.new(-823.4948120117188, 65.84532928466797, -10962.1982421875)
NameQuest = "IceCreamIslandQuest"
LvQuest = 1
elseif Lv == 2150 or Lv <= 2199 then
Mon = "Ice Cream Chef [Lv. 2125]"
NameMon = "Ice Cream Chef"
CFrameMon = CFrame.new(-823.4948120117188, 65.84532928466797, -10962.1982421875)
CFrameQuest = CFrame.new(-823.4948120117188, 65.84532928466797, -10962.1982421875)
NameQuest = "IceCreamIslandQuest"
LvQuest = 2
elseif Lv == 2200 or Lv <= 2224 then
Mon = "Cookie Crafter [Lv. 2200]"
NameMon = "Cookie Crafter"
CFrameMon = CFrame.new(-2022.667724609375, 37.82401657104492, -12026.154296875)
CFrameQuest = CFrame.new(-2022.667724609375, 37.82401657104492, -12026.154296875)
NameQuest = "CakeQuest1"
LvQuest = 1
elseif Lv == 2225 or Lv <= 2249 then
Mon = "Cake Guard [Lv. 2225]"
NameMon = "Cake Guard"
CFrameMon = CFrame.new(-1591.5015869140625, 44.802120208740234, -12251.9833984375)
CFrameQuest = CFrame.new(-2022.667724609375, 37.82401657104492, -12026.154296875)
NameQuest = "CakeQuest1"
LvQuest = 2
elseif Lv == 2250 or Lv <= 2274 then
Mon = "Head Baker [Lv. 2275]"
NameMon = "Head Baker"
CFrameMon = CFrame.new(-1924.470458984375, 37.82392501831055, -12842.0546875)
CFrameQuest = CFrame.new(-1924.470458984375, 37.82392501831055, -12842.0546875)
NameQuest = "CakeQuest2"
LvQuest = 1
elseif Lv == 2275 or Lv <= 2299 then
Mon = "Head Baker [Lv. 2275]"
NameMon = "Head Baker"
CFrameMon = CFrame.new(-2239.84912109375, 61.64055633544922, -12943.017578125)
CFrameQuest = CFrame.new(-1924.470458984375, 37.82392501831055, -12842.0546875)
NameQuest = "CakeQuest2"
LvQuest = 2
        end
end




    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
    local CenterHubNo1 = library:CreateWindow("Ice x Hub | BLOX FRUIT",Enum.KeyCode.RightControl)
    local Tab = CenterHubNo1:CreateTab("Main")
    local AutoFarm = Tab:CreateSector("AutoFarm","Left")
    AutoFarm:AddLabel("AutoFarm Lv")
    Weapon = {}
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA"Tool" then
            table.insert(Weapon,v.Name)
    end
end
    local WE = AutoFarm:AddDropdown("Select Weapon",Weapon,"Select Weapon",false,function(t)
        _G.SelectWeapon = t
    end)
function Equip(ToolX)
    if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX) then
        getgenv().Tol = game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tol)
    end
end
function click()
   game:GetService'VirtualUser':CaptureController()
   game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
end
 function TP(P)
   local Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
   local Speed = 300 -- ความเร็วของมึง
   tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
   tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = P})
   tween:Play()
 end
         AutoFarm:AddButton("ReSet Weapon",function()
        table.clear(Weapon)
        for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA"Tool" then
        WE:Add(v.Name)
        end
    end
end)

 AutoFarm:AddToggle("AutoFarm",false,function(t)
        _G.AutoFarm = t
    end)
    AutoFarm:AddToggle("BringMob",false,function(t)
        _G.BringMob = t
    end)
      function TP(P)
    Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 250 then
       game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
       Speed = 1000
    elseif Distance >= 1000 then
       Speed = 300
    end
    game:GetService("TweenService"):Create(
    game.Players.LocalPlayer.Character.HumanoidRootPart,
    TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
    {CFrame = P}
    ):Play()
 end

Boss = {}
for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
    if string.find(v.Name,"Boss") then
table.insert(Boss,v.Name)
    end
end
 local WE = AutoFarm:AddDropdown("Select Boss",Boss,"Select Boss",false,function(v)
        SelectBoss = v
    end)
    AutoFarm:AddToggle("Boss",false,function(v)
        _G.Boss = v
    end)
spawn(function()
    while wait() do
        if _G.Boss then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if v.Name == SelectBoos and v:FindFirstChild("HumanoidRootPart") then
            repeat wait()
                TP(v.HumanoidRootPart.CFrame * CFrame.new(0,10,3))
                v.HumanoidRootPart.Size = Vector3.new(30,30,30)
                v.Humanoid.WalkSpeed = 0
                v.Humanoid.JumpPower = 0
            until not _G.Boss or v.Humanoid.Health <= 0
                else
                    if game:GetService("ReplicatedStorage"):FindFirstChild(SelectBoos) then
                        TP(game:GetService("ReplicatedStorage"):FindFirstChild(SelectBoos).HumanoidRootPart.CFrame)
                    end
                end
            end
        end
    end
end)
spawn(function()
        game:GetService("RunService").Heartbeat:Connect(function()
        if _G.Boss then
        if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
            setfflag("HumanoidParallelRemoveNoPhysics", "False")
            setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
            game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end
    end)
end)
   
    
local Stats = Tab:CreateSector("Stats","Reft")
Stats:AddLabel("Stats")
Stats:AddToggle(" Melee",false,function(t)
_G.Melee = t
while _G.Melee do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",Point)
end)
end
end)
Stats:AddToggle(" Defense",false,function(t)
_G.Defense = t
while _G.Defense do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",Point)
end)
end
end)
Stats:AddToggle(" Sword",false,function(t)
_G.Sword = t
while _G.Sword do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Sword",Point)
end)
end
end)
Stats:AddToggle(" Gun",false,function(t)
_G.Gun = t
while _G.Gun do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Gun",Point)
end)
end
end)
Stats:AddToggle(" Blox Fruit",false,function(t)
_G.Fruit = t
while _G.Fruit do wait(.1)
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Demon Fruit",Point)
end)
end
end)
Stats:AddSlider("Point",1,1,100,1,function(x)
Point = x
end)

    spawn(function()
    while wait() do
        if _G.BringMob then
            pcall(function()
            CheckQuest()
       for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
for x,y in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
if v.Name == Mon then
    if y.Name == Mon then
   v.HumanoidRootPart.CFrame = y.HumanoidRootPart.CFrame
   v.HumanoidRootPart.Size = Vector3.new(120,120,120)
   y.HumanoidRootPart.Size = Vector3.new(120,120,120)
   v.HumanoidRootPart.Transparency = 100
   v.HumanoidRootPart.CanCollide = false
   y.HumanoidRootPart.CanCollide = false
   v.Humanoid.WalkSpeed = 150
   y.Humanoid.WalkSpeed = 150
   v.Humanoid.JumpPower = 150
   y.Humanoid.JumpPower = 150
   if sethiddenproperty then
     sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
end
end
end
end
end
end)
end
end
end)










spawn(function()
   game:GetService("RunService").RenderStepped:Connect(function()
    pcall(function()
        local Combat = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
        local Cemara = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
        Cemara.CameraShakeInstance.CameraShakeState = {FadingIn = 3, FadingOut = 2, Sustained = 0, Inactive = 1}
    end)
end) 
end)

spawn(function()
    while wait() do
        if _G.AutoFarm then
            pcall(function()
            CheckQuest()
    if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
    TP(CFrameQuest)
    if (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 then
    wait(.1)
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NameQuest,LvQuest)
    end
    elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
        if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if v.Name == Mon and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid")   then
                    if v.Humanoid.Health > 0 then
                    repeat wait()
                        click()
                        Equip(_G.SelectWeapon)
                        HealthMin = v.Humanoid.MaxHealth * 1000 / 1000
                        Magma = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                        if Magma <= 230 then
                            if v.Humanoid.Health > HealthMin then
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
                                else
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
                            end
                        end
                            if v.Humanoid.Health > HealthMin then
                        Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                        Speed = 300 
                        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,20,0)})
                        tween:Play() 
                        else
                        Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                        Speed = 300 
                        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,20,0)})
                        tween:Play()
                            end
                        v.HumanoidRootPart.Size = Vector3.new(70,70,70)
                        v.HumanoidRootPart.CanCaillde = false
                    until _G.AutoFarm == false or v.Humanoid.Health <= 0
                    else
                        TP(CFrameMon)
                    end
                    if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                    end
                    if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 then
                        _G.AutoFarm = false
                        wait(3)
                        _G.AutoFarm = true
                        end
                end
                end
        end
        end
       end)
end
end
end)










spawn(function()
    game:GetService("RunService").Heartbeat:Connect(function()
        if _G.AutoFarm then
        if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
            setfflag("HumanoidParallelRemoveNoPhysics", "False")
            setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
            game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
            end
        end
    end)
end)

























local Tab = CenterHubNo1:CreateTab("Store")
local Store = Tab:CreateSector("Store","Left")
Store:AddToggle(" DARK STEP",false,function(v)
    _G.DARKSTEP = v
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-984.609375, 14.3359022, 3990.02368, -0.408447713, -0, -0.912781715, -0, 1, -0, 0.912781715, 0, -0.408447713)}):Play()
end)
Store:AddToggle(" ELECTRIC",false,function(v)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-5384.02881, 14.5887861, -2149.18042, -0.0822776556, -0, -0.996609449, -0, 1, -0, 0.996609449, 0, -0.0822776556)}):Play()
end)
Store:AddToggle(" WATER KUNG FU",false,function(v)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(61592.3125, 18.8970432, 984.843445, 0.0836518556, 0, -0.996495008, -0, 1, -0, 0.996495128, 0, 0.0836518481)}):Play()
end)
Store:AddToggle(" DRAGON BREAT",false,function(v)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(61592.3125, 18.8970432, 984.843445, 0.0836518556, 0, -0.996495008, -0, 1, -0, 0.996495128, 0, 0.0836518481)}):Play()
end)





local Store = Tab:CreateSector("Haki-key","Left")
Store:AddToggle(" key",false,function(v)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(4850.71582, 6.35411787, 718.245178, 0.29571557, 0, -0.955276012, -0, 1, -0, 0.955276132, 0, 0.295715541)}):Play()
end)
Store:AddToggle("key2",false, function(v)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(1350.41174, 37.7902641, -1327.59827, 0.558075845, 0, 0.829789937, -0, 1, -0, -0.829789937, 0, 0.558075845)}):Play()
end)

Store:AddToggle("Haki",false, function(v)
local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(1490.64807, 38.0448494, -1413.59949, -0.378409445, 0, 0.925638318, 0, 1, -0, -0.925638318, 0, -0.378409445)}):Play()
end)






local StatsAFK = Tab:CreateSector("AFK","Reft")
StatsAFK:AddLabel("AFK")
StatsAFK:AddToggle(" AFK",false,function(t)
    Magnet = t  
	end)
	local t = game:GetService("VirtualUser")
	game:GetService("Players").LocalPlayer.Idled:connect(function()
		vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		wait(1)
		vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
	end)
StatsAFK:AddToggle(" AFK",false,function(t)
    game:GetService("Players").LocalPlayer.Idled:connect(function()
			vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
			wait(1)
			vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		end)
	end)















