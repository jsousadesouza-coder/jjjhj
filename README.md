--// Services
local StarterGui = game:GetService("StarterGui")

--// Show notification
StarterGui:SetCore("SendNotification", {
    Title = "Credits",
    Text = "de loostNT",
    Duration = 5, -- how long it stays on screen (in seconds)
    Button1 = "OK"
})
