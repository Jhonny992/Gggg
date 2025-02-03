while true do
local args = {
    [1] = "Egg_1_1",
    [2] = 6
}

game:GetService("ReplicatedStorage").Packages._Index:FindFirstChild("sleitnick_knit@1.5.1").knit.Services.EggHatchService.RE.Hatch:FireServer(unpack(args))
Wait()
end
