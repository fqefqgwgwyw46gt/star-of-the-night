print("star of the night is Injected!")
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "star of the night",
    Text = "injected star of the night",
    Icon = "rbxassetid://18931391752",
    Duration = 8
})
wait(8)
print("http://dsc.gg/star-of-the-night")
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "http://dsc.gg/star-of-the-night",
    Text = "http://dsc.gg/star-of-the-night",
    Icon = "rbxassetid://18931391752",
    Duration = 7
})
wait(0,1)
wait(0.1)
  function printidentity() return print("Current identity is 4") end






local function customHttpGet(url)
    return HttpGet(url)
end


local function executeScript(url)
    local scriptContent = customHttpGet(url)
    loadstring(scriptContent)()
end


local function gameHttpGet(url)
    return customHttpGet(url)
end
