print("THIS SCRIPT MADE BY bobbytri#2272")
while true do
wait(1)
local args = {
   [1] = 1
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
wait(5)
local a1 = game:GetService("Players").bobbytri.Albnn.Value
print("SHA-512: "..a1)

local args = {
   [1] = 2
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
wait(5)
local a2 = game:GetService("Players").bobbytri.Albnn.Value
print("Dagger: "..a2)

local args = {
   [1] = 3
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
wait(5)
local a3 = game:GetService("Players").bobbytri.Albnn.Value
print("Scrypt: "..a3)

local args = {
   [1] = 4
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
wait(5)
local a4 = game:GetService("Players").bobbytri.Albnn.Value
print("Bloxchain: "..a4)

if a1 > a2 and a3 and a4 then
local args = {
   [1] = 1
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
print("Choose SHA-512: "..a1)
end
wait(3)
if a2 > a1 and a3 and a4 then
local args = {
   [1] = 2
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
print("Choose Dagger: "..a2)
end
wait(3)
if a3 > a2 and a1 and a4 then
local args = {
   [1] = 3
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
print("Choose Scrypt: "..a3)
end
wait(3)
if a4 > a2 and a3 and a1 then
local args = {
   [1] = 4
}

game:GetService("ReplicatedStorage").Events.AlgoChang:FireServer(unpack(args))
print("Choose Bloxchain: "..a4)
end
end 
