Fluent tutorial (I just need this to dont forget how to do things in fluent)

all credits to: dawid-scripts


Better Toggle (FRFFRFRFRFFRFfrfrffr)

local Toggle2 = Tabs.Main:AddToggle("MyToggle", {Title = "+", Default = false })

    Toggle:OnChanged(function(arg)
       if arg then
        local dothing = "dothing"
            print(dothing)
        else
            local notdothing = "Not doing thing"
            print(notdothing)
        end
    end)
well or

Main:AddToggle("IdkName", {
        Title = "Name",
        Description = "Makes Something",
        Default = false,
        Callback = function(Value)
            --do something fr
        end
    })
