# LorenXScript print("My custom script loaded successfully!")

local player = game.Players.LocalPlayer
if player and player.Character then
    player.Character.Humanoid.WalkSpeed = 50
    print("Walkspeed has been increased to 50!")
end
