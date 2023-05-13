local ScreenGui = Instance.new("ScreenGui")

local UI = Instance.new("Frame")

local Title = Instance.new("TextLabel")

local Frame = Instance.new("Frame")

local Key = Instance.new("TextBox")

local Start = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

UI.Name = "大青蛙"

UI.Parent = ScreenGui

UI.Active = true

UI.BackgroundColor3 = Color3.fromRGB(0, 0, 0)

UI.BackgroundTransparency = 0

UI.BorderSizePixel = 3

UI.Position = UDim2.new(0.5, -150, 0.5, -67)

UI.Size = UDim2.new(0, 260, 0, 250)

UI.Draggable = true

Title.Name = "Title"

Title.Parent = UI

Title.BackgroundColor3 = Color3.fromRGB(68, 68, 68)

Title.BackgroundTransparency = 1

Title.BorderSizePixel = 2

Title.Position = UDim2.new(0, 0, 0.02, 0)

Title.Size = UDim2.new(1, 0, 0, 50)

Title.Font = Enum.Font.SourceSans

Title.Text = "密钥系统V3"

Title.TextColor3 = Color3.fromRGB(0, 0, 255)

Title.TextScaled = true

Title.TextSize = 14

Title.TextWrapped = true

Frame.Parent = Title

Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

Frame.BorderSizePixel = 0

Frame.Position = UDim2.new(0.07, 0, 0.9, 0)

Frame.Size = UDim2.new(0.85, 0, 0, 6)

Key.Name = "Key"

Key.Parent = UI

Key.BackgroundColor3 = Color3.fromRGB(1, 1, 1)

Key.BorderSizePixel = 0

Key.Position = UDim2.new(0.1, 0, 0.31, 0)

Key.Size = UDim2.new(0.8, 0, 0, 50)

Key.Font = Enum.Font.SourceSans

Key.PlaceholderText = "在这里输入"

Key.Text = ""

Key.TextColor3 = Color3.fromRGB(0, 0, 0)

Key.TextScaled = true

Key.TextSize = 14

Key.TextWrapped = true

Start.Name = "Start"

Start.Parent = UI

Start.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

Start.BackgroundTransparency = 0

Start.BorderSizePixel = 2

Start.Position = UDim2.new(0.25, 0, 0.65, 0)

Start.Size = UDim2.new(0.5, 0, 0, 45)

Start.Font = Enum.Font.Gotham

Start.Text = "OK"

Start.TextColor3 = Color3.fromRGB(0, 0, 0)

Start.TextScaled = true

Start.TextSize = 10

Start.TextWrapped = true

Start.MouseButton1Click:Connect(function()

    if Key.Text == "gdhfhfuyfcghg545565686565588" then

        ScreenGui:Destroy()

        local LBLG = Instance.new("ScreenGui", getParent)

local LBL = Instance.new("TextLabel", getParent)

local player = game.Players.LocalPlayer

LBLG.Name = "LBLG"

LBLG.Parent = game.CoreGui

LBLG.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

LBLG.Enabled = true

LBL.Name = "LBL"

LBL.Parent = LBLG

LBL.BackgroundColor3 = Color3.new(1, 1, 1)

LBL.BackgroundTransparency = 1

LBL.BorderColor3 = Color3.new(0, 0, 0)

LBL.Position = UDim2.new(0.75,0,0.010,0)

LBL.Size = UDim2.new(0, 133, 0, 30)

LBL.Font = Enum.Font.GothamSemibold

LBL.Text = "TextLabel"

LBL.TextColor3 = Color3.new(1, 1, 1)

LBL.TextScaled = true

LBL.TextSize = 14

LBL.TextWrapped = true

LBL.Visible = true

local FpsLabel = LBL

local Heartbeat = game:GetService("RunService").Heartbeat

local LastIteration, Start

local FrameUpdateTable = { }

local function HeartbeatUpdate()

	LastIteration = tick()	for Index = #FrameUpdateTable, 1, -1 do

		FrameUpdateTable[Index + 1] = (FrameUpdateTable[Index] >= LastIteration - 1) and FrameUpdateTable[Index] or nil

	end

	FrameUpdateTable[1] = LastIteration

	local CurrentFPS = (tick() - Start >= 1 and #FrameUpdateTable) or (#FrameUpdateTable / (tick() - Start))

	CurrentFPS = CurrentFPS - CurrentFPS % 1

	FpsLabel.Text = ("北京的时间:"..os.date("%H").."时"..os.date("%M").."分"..os.date("%S"))

end

Start = tick()

Heartbeat:Connect(HeartbeatUpdate)

local m = Instance.new("Message", workspace)

m.Text = "欢迎使用大青蛙脚本"

wait(2)

m:Destroy()

local m = Instance.new("Message", workspace)

m.Text = "记得去快手关注我"

wait(2)

m:Destroy()

local m = Instance.new("Message", workspace)

m.Text = "3"

wait(2)

m:Destroy()

local m = Instance.new("Message", workspace)

m.Text = "2"

wait(2)

m:Destroy()

local m = Instance.new("Message", workspace)

m.Text = "1"

wait(2)

m:Destroy()

local m = Instance.new("Message", workspace)

m.Text = "脚本正在加载"

wait(5)

m:Destroy()

local m = Instance.new("Message", workspace)

m.Text = "脚本加载成功"

wait(2)

m:Destroy()

local runDummyScript = function(f,scri)

local oldenv = getfenv(f)

local newenv = setmetatable({}, {

__index = function(_, k)

if k:lower() == 'script' then

return scri

else

return oldenv[k]

end

end

})

setfenv(f, newenv)

ypcall(function() f() end)

end

cors = {}

mas = Instance.new("Model",game:GetService("Lighting")) 

mas.Name = "CompiledModel"

o1 = Instance.new("ScreenGui")

o2 = Instance.new("Frame")

o3 = Instance.new("TextButton")

o4 = Instance.new("TextButton")

o5 = Instance.new("LocalScript")

o6 = Instance.new("LocalScript")

o1.Name = "RateGui"

o1.Parent = mas

o2.Parent = o1

o2.Position = UDim2.new(0.89999997615814,0,0.92500001192093,0)

o2.Size = UDim2.new(0.10000000149012,0,0.075000002980232,0)

o2.Position = UDim2.new(0.89999997615814,0,0.92500001192093,0)

o2.BackgroundColor3 = Color3.new(0, 0, 0)

o2.BackgroundTransparency = 1

o3.Name = "PingLabel"

o3.Parent = o2

o3.Size = UDim2.new(1,0,0.5,0)

o3.Text = "Ping: "

o3.BackgroundColor3 = Color3.new(0, 0, 0)

o3.BackgroundTransparency = 1

o3.BorderSizePixel = 0

o3.ZIndex = 2

o3.Font = Enum.Font.SourceSans

o3.FontSize = Enum.FontSize.Size14

o3.TextColor3 = Color3.new(1, 1, 1)

o4.Name = "FPSLabel"

o4.Parent = o2

o4.Position = UDim2.new(0,0,0.5,0)

o4.Size = UDim2.new(1,0,0.5,0)

o4.Text = "FPS: "

o4.Position = UDim2.new(0,0,0.5,0)

o4.BackgroundColor3 = Color3.new(0, 0, 0)

o4.BackgroundTransparency = 1

o4.BorderSizePixel = 0

o4.ZIndex = 2

o4.Font = Enum.Font.SourceSans

o4.FontSize = Enum.FontSize.Size14

o4.TextColor3 = Color3.new(1, 1, 1)

o5.Name = "PingScript"

o5.Parent = o2

table.insert(cors,coroutine.create(function()

wait()

runDummyScript(function()

local Frame = script.Parent

local PingLabel = Frame:WaitForChild('PingLabel')

while wait(1) do

	local Ping = 300-((1/wait())*10)

	if Ping < 1 then

		Ping = 1

	end

	PingLabel.Text = 'Ping: '..math.floor(Ping)

	wait(9)

end

 

 -- Made by 4ef.

end,o5)

end))

o6.Name = "FPSScript"

o6.Parent = o2

table.insert(cors,coroutine.create(function()

wait()

runDummyScript(function()

local Frame = script.Parent

local FPSLabel = Frame:WaitForChild('FPSLabel')

while wait(1) do

	local FPS = game:GetService("Workspace"):GetRealPhysicsFPS()

	FPSLabel.Text = 'FPS: '..math.floor(FPS)

end

 

 -- Made by 4ef.

end,o6)

end))

mas.Parent = workspace

mas:MakeJoints()

local mas1 = mas:GetChildren()

for i=1,#mas1 do

	mas1[i].Parent = game:GetService("Players").LocalPlayer.PlayerGui 

	ypcall(function() mas1[i]:MakeJoints() end)

end

mas:Destroy()

for i=1,#cors do

coroutine.resume(cors[i])

end

local DarkraiX = loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Kavo-Ui/main/Darkrai%20Ui", true))()

local Library = DarkraiX:Window("🐸青蛙🐸","青蛙V3版本","",Enum.KeyCode.RightControl)

Tab1 = Library:Tab("人物")

Tab1:Button("飞行",function()

    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

end)

Tab1:Slider("速度",1,999,16,function(value)

        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value

    end)

Tab1:Slider("跳跃",1,100,25,function(value)

        game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value

    end)

Tab1:Toggle("夜视",false,function(value)

    _G.autojoinbrawl = value

if Value then

		    game.Lighting.Ambient = Color3.new(1, 1, 1)

		else

		    game.Lighting.Ambient = Color3.new(0, 0, 0)

		end

    end)

Tab1:Toggle("穿墙",false,function(value)

    _G.autojoinbrawl = value

if Value then

		    Noclip = true

		    Stepped = game.RunService.Stepped:Connect(function()

			    if Noclip == true then

				    for a, b in pairs(game.Workspace:GetChildren()) do

                        if b.Name == game.Players.LocalPlayer.Name then

                            for i, v in pairs(game.Workspace[game.Players.LocalPlayer.Name]:GetChildren()) do

                                if v:IsA("BasePart") then

                                    v.CanCollide = false

                                end

                            end

                        end

                    end

			    else

				    Stepped:Disconnect()

			    end

		    end)

	    else

		    Noclip = false

	    end

    end)

Tab1:Button("重置玩家名称", function()

	shuaxinlb(true)

	Players:SetOptions(bai.dropdown)

end)

Tab1:Button("传送到玩家旁边",function()

    local HumRoot = game.Players.LocalPlayer.Character.HumanoidRootPart

    local tp_player = game:GetService("Players")[bai.ftgnwj]

    if tp_player then

        for i = 1,5 do

            wait()

            HumRoot.CFrame = tp_player.Character.HumanoidRootPart.CFrame + Vector3.new(0, 3, 0)

        end

    end

end)

Tab1 = Library:Tab("自然灾害")

Tab1:Button("气球跳跃的高度",function()

    game.Workspace.Gravity = 40

    game.StarterGui:SetCore("SendNotification", {

        Title = "自然灾害",

        Text = "不会扣血掉落的时候"

    })

end)

Tab1:Button("指南针",function()

    game.Players.LocalPlayer.PlayerGui.MainGui.MapVotePage.Visible = true

 

   wait(3)

 

   game.Players.LocalPlayer.PlayerGui.MainGui.MapVotePage.Visible = false

end)

Tab1:Button("传送回去",function()

    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-322.056091, 180.192688, 352.165253, 0.966439426, 6.11293238e-11, 0.256894618, 1.1281677e-10, 1, -6.62372379e-10, -0.256894618, 6.69124811e-10, 0.966439426)

end)

Tab1:Button("传送到岛上",function()

    game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-134,47,7))

end)

Tab1:Toggle("掉落无伤害",false,function(value)

game.Players.LocalPlayer.Character.FallDamageScript:Destroy()

    end)

Tab1:Button("删除沙尘暴的模糊视线",function()

    game.Players.LocalPlayer.PlayerGui.SandStormGui:destroy()

end)

Tab1 = Library:Tab("造船寻宝")

Tab1:Button("刷钱",function()

       local players = game:GetService("Players")

        local stages = workspace:WaitForChild("BoatStages"):WaitForChild("NormalStages")

        local penguin, gold = workspace:WaitForChild("ChangeCharacter"), workspace:WaitForChild("ClaimRiverResultsGold")

        local client = players.LocalPlayer

        _G.Busy = true

        while _G.Busy do

            local bodyVelocity = Instance.new("BodyVelocity")

            bodyVelocity.Velocity = Vector3.new(0, -4, 0)

            bodyVelocity.Parent = client.Character.HumanoidRootPart

 

            for i = 1, 9 do

                if not client.Character or not client.Character:FindFirstChild("Humanoid") then

                    repeat wait() until client.Character and client.Character:FindFirstChild("Humanoid")

                end

 

                client.Character.HumanoidRootPart.CFrame = stages["CaveStage"..i].DarknessPart.CFrame wait(0.1)

 

                if not _G.Busy then

                    client.Character.Humanoid.Health = 0

                    exit(0)

                end

 

                if i == 1 then

                    wait(4)

                else

                    wait(2)

                end

 

                gold:FireServer()

            end

            penguin:FireServer("ChickenCharacter")

            client.Character:Remove()

            repeat wait() 

            until client.Character and client.Character:FindFirstChild("HumanoidRootPart")

        end

StarterGui:SetCore("SendNotification", {

        Title = "造船寻宝",

        Text = "刷够了钱就退出重进"

    })

end)

Tab1 = Library:Tab("力量传奇")

Tab1:Button("重置人物",function()

    game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Tab1:Button("重进",function()

    local TeleportService = game:GetService("TeleportService")

    local Players = game:GetService("Players")

    local LocalPlayer = Players.LocalPlayer

    local Rejoin = coroutine.create(function()

        local Success, ErrorMessage = pcall(function()

            TeleportService:Teleport(game.PlaceId, LocalPlayer)

        end)

        if ErrorMessage and not Success then

            warn(ErrorMessage)

        end

    end)

    coroutine.resume(Rejoin)

end)

Tab1:Dropdown("选择传送地点",{"新手岛","出生点","冰冻健身房","神秘健身房","地狱健身房","传奇健身房","肌肉之王健身房"},function(value)

    _G.selectxyz = value

end)

Tab1:Button("传送",function()

    if _G.selectxyz == "新手岛" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-37.3832397, 3.93394399, 1885.64355, -0.999980569, -3.40501849e-08, -0.0062325038, -3.39714035e-08, 1, -1.27464252e-08, 0.0062325038, -1.25344508e-08, -0.999980569)

    elseif _G.selectxyz == "出生点" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(15.2333269, 3.78062296, 163.758591, 0.999851763, 1.96320187e-08, -0.0172187611, -2.03378434e-08, 1, -4.08164773e-08, 0.0172187611, 4.11606216e-08, 0.999851763)

    elseif _G.selectxyz == "冰冻健身房" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2711.82764, 3.78062248, -409.042572, 0.00548080029, 1.18744083e-07, 0.99998498, 1.52677249e-08, 1, -1.18829547e-07, -0.99998498, 1.59187774e-08, 0.00548080029)

    elseif _G.selectxyz == "神秘健身房" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2331.67773, 3.78062248, 1076.02795, -0.0029885713, -6.25791401e-08, -0.99999553, 4.83115015e-09, 1, -6.25938554e-08, 0.99999553, -5.01819475e-09, -0.0029885713)

    elseif _G.selectxyz == "地狱健身房" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6865.82324, 3.7806356, -1284.92664, 0.0056865178, 1.3501813e-08, 0.999983847, 1.86734428e-09, 1, -1.35126497e-08, -0.999983847, 1.94415395e-09, 0.0056865178)

    elseif _G.selectxyz == "传奇健身房" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4480.11035, 987.933594, -3858.88501, 0.0159854759, 4.91444183e-08, 0.999872208, -1.6045675e-08, 1, -4.88941687e-08, -0.999872208, -1.52620281e-08, 0.0159854759)

    elseif _G.selectxyz == "肌肉之王健身房" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8688.46289, 13.6306515, -5792.2002, 0.701782882, -5.41762866e-08, 0.7123909, 2.72639049e-08, 1, 4.91906142e-08, -0.7123909, -1.50985731e-08, 0.701782882)

          end

end)

Tab1:Dropdown("选择石头",{"小号石头","拳击岩石","大号岩石","金色石头","冰冻岩石","神话岩石","地狱火岩石","传说之岩","肌肉之王岩"},function(value)

    _G.SelectRock = value

end)

Tab1:Toggle("自动打石头",false,function(value)

_G.tprock = value

    while _G.tprock == true do

        if _G.SelectRock == "小号石头" then

        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(24.4961128, 3.72196555, 2099.53735, -0.69158572, 0.0250273459, 0.721860647, 0, 0.999399543, -0.0346497893, -0.72229439, -0.0239633061, -0.691170454)

        wait(0.01)

        elseif _G.SelectRock == "拳击岩石" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-158.857407, 3.86024189, 411.886353, -0.799369395, 1.31105882e-08, -0.600839853, 1.08799547e-08, 1, 7.34552641e-09, 0.600839853, -6.65321076e-10, -0.799369395)

        wait(0.01)

        elseif _G.SelectRock == "大号岩石" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(179.097717, 3.45000076, -152.624084, -0.0424842201, 0.0701754093, 0.996629715, 2.32830671e-10, 0.997530341, -0.0702388734, -0.999097228, -0.00298404275, -0.0423792973)

            wait(0.01)

        elseif _G.SelectRock == "金色石头" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(297.331146, 3.24769545, -567.852173, 0.908808589, 0.0155105852, -0.416924864, -8.03942246e-09, 0.999308705, 0.0371766165, 0.417213291, -0.0337864235, 0.908180356)

            wait(0.01)

        elseif _G.SelectRock == "冰冻岩石" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2588.32031, 3.98274565, -242.878662, 0.0922317132, 0.0102147022, -0.99568516, -8.3768219e-09, 0.999947369, 0.0102584278, 0.995737553, -0.000946143991, 0.0922268555)

            wait(0.01)

        elseif _G.SelectRock == "神话岩石" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2219.19751, 4.19589376, 1236.1698, -0.172804534, 0.0587716848, 0.983201146, -7.05719438e-09, 0.998218179, -0.0596693419, -0.984956145, -0.0103111397, -0.172496632)

            wait(0.01)

        elseif _G.SelectRock == "地狱火岩石" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7228.74805, 3.4117527, -1242.7666, 0.316847205, -0.0498497151, 0.947165668, 6.51175958e-09, 0.998617887, 0.0525576659, -0.948476613, -0.0166527443, 0.31640929)

            wait(0.01)

        elseif _G.SelectRock == "传说之岩" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4186.89209, 987.893555, -4121.46436, -0.718660772, -1.6120806e-08, 0.695360839, 3.29589867e-09, 1, 2.65897047e-08, -0.695360839, 2.14008171e-08, -0.718660772)

            wait(0.01)

        elseif _G.SelectRock == "肌肉之王岩" then

            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-9033.37793, 5.60062313, -6071.25, -0.302900642, -7.34220365e-08, -0.953022122, 7.08072605e-08, 1, -9.95460638e-08, 0.953022122, -9.76334533e-08, -0.302900642)

        wait(0.01)

        end

        end

    end)

Tab1:Toggle("刷人头",false,function(value)

    _G.autokill = value

    autokill()

    end)

Tab1:Toggle("自动锻炼",false,function(value)

    _G.autolift = value

    autolift()

    end)

Tab1 = Library:Tab("DOORS")

Tab1:Button("神圣手雷",function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/MrNeRD0/Doors-Hack/main/HolyGrenadeByNerd.lua"))()

end)

Tab1 = Library:Tab("其他")

Tab1:Seperator("欢迎用户"..game.Players.LocalPlayer.Name)

Tab1:Seperator("当前游戏ID为:" .. game.GameId .. ".")

Tab1:Seperator("您的注入器是: "..identifyexecutor())

Tab1:Button("复制作者的QQ",function()

    setclipboard("2285033810")

end)

Tab1:Button("复制作者的快手号",function()

    setclipboard("2306024610")

end)

Tab1:Button("重进服务器",function()

    local TeleportService = game:GetService("TeleportService")

    local Players = game:GetService("Players")

    local LocalPlayer = Players.LocalPlayer

    local Rejoin = coroutine.create(function()

        local Success, ErrorMessage = pcall(function()

            TeleportService:Teleport(game.PlaceId, LocalPlayer)

        end)

        if ErrorMessage and not Success then

            warn(ErrorMessage)

        end

    end)

    coroutine.resume(Rejoin)

end)

game.StarterGui:SetCore("SendNotification", {

        Title = "欢迎",

        Text = "欢迎用户"..game.Players.LocalPlayer.Name

    })

    

game.StarterGui:SetCore("SendNotification", {

        Title = "🐸大青蛙🐸",

        Text = "帧率在下面让你们方便看🐸"

    })

    

    local ScreenGui = Instance.new("ScreenGui")

local TextButton = Instance.new("TextButton")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextButton.Parent = ScreenGui

TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

TextButton.Position = UDim2.new(0.855521917, 0, 0.516025662, 0)

TextButton.Size = UDim2.new(0, 135, 0, 50)

TextButton.Font = Enum.Font.SourceSans

TextButton.Text = "隐藏/打开"

TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)

TextButton.TextScaled = true

TextButton.TextSize = 14.000

TextButton.TextWrapped = true

TextButton.Draggable = true

caonima = false

TextButton.MouseButton1Click:Connect(function()

	if caonima == false then

		caonima = true

		game.CoreGui.Darkrai.Main.Visible = false

	else

		caonima = false

		game.CoreGui.Darkrai.Main.Visible = true

	end

end)

    else

        game.StarterGui:SetCore("SendNotification", {

        Title = "🐸大青蛙🐸",

        Text = "密码错误"

    })

    

    end

end)
