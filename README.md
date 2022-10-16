_G.auto = true
while _G.auto do wait()
for i,v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do
    if v.ClassName == "Model" then
        v.Humanoid.Health = die
wait(.5)
end
end
end
