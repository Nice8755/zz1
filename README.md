_G.auto = true
while _G.auto do wait()
for i,v in pairs(game:GetService("Workspace").Monster.Boss:GetChildren()) do
    if v.ClassName == "Model" then
        v.Humanoid.Health = die
wait(0.1)
end
end
end
