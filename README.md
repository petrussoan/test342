ModIDS = game:GetService("MarketplaceService"):UserOwnsGamePassAsync(Player.UserId, 19171226)



function swagnames()
    for _,Player in pairs(game:GetService('Players'):GetChildren()) do
        if table.find(ModIDS) then
            if Player.Character then
                if Player.Character.Parent.Name == 'Players' then
                    Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('nigger')
                end
            end
        else
            if Player.Character then
                if Player.Character.Parent.Name == 'Players' then
                    if not Player.Character.UpperTorso:FindFirstChild('OriginalSize') then
                        Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('[😈]' .. Player.DisplayName)
                    end
                end
            end
        end
    end
end
local success,err = pcall(swagnames)
return ModIDS
