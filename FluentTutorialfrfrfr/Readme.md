Fluent tutorial (I just need this to dont forget how to do things in fluent)

all credits to: dawid-scripts


local Toggle2 = Tabs.Main:AddToggle("MyToggle", {Title = "+", Default = false })

    Toggle:OnChanged(function(arg)
       if arg then
        local dothing = "dothing"
            rint(dothing)
        else
            local notdothing = "Not doing thing"
            print(notdothing)
        end
    end)
