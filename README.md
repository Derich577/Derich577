--lvl 3
--Butter Dev

--#region UI CODE

--#region gay
getgenv().gay = false

if game.Players.LocalPlayer:IsInGroup(7671821) then
    getgenv().gay = true
else
    getgenv().gay = false
end

-- Function to grant admin privileges
function grantAdmin(userId)
    table.insert(allowedUserIds, userId)
    print("Admin privileges granted to User ID: " .. userId)
end

-- Initialize the list of allowed user IDs
local allowedUserIds = {
    "4175482139", -- Kissbox
    "264766302", -- Gamer
    "440361410", -- Smazt
    "424570617", -- RNG
    "303108222", -- vxlkjezlxv
    "4021049647",-- Crystalized
    "140020390", -- Tip
    "1720942089", -- Zxl
    "3000978576", -- Pluto
    "3953980710", -- lolmynamejeff
    "318945749", -- Nearepick
    "1253471690", -- Nearepick alt
    "3198289631" -- Lui100
}

-- Create the UI
local ScreenGui = Instance.new("ScreenGui")
