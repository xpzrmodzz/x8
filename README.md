--create by FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 8,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy8.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
