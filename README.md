_G.AutoFarm = true
while _G.AutoFarm do wait()
game:GetService("Players").LocalPlayer.ninjaEvent:FireServer("swingKatana")
wait(.1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(77.34844970703125, 20.94031524658203, -49.25339889526367)
_G.AutoBuy = true
wait(.1)
game:GetService("Players").LocalPlayer.ninjaEvent:FireServer("buyAllSwords","Ground")
wait(.1)
game:GetService("Players").LocalPlayer.ninjaEvent:FireServer("buyAllBelts","Ground")
wait(.1)
game:GetService("Players").LocalPlayer.ninjaEvent:FireServer("buyAllSkills","Ground")
end
