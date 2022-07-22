     local function liIlIliIl(text)
            local lIllilIll = game:GetService("Players").LocalPlayer
            lIllilIll:Kick(text)
        end
        liIlIliIl("RESET HWID")
        wait(1)
        local ts = game:GetService("TeleportService")
        local p = game:GetService("Players").LocalPlayer
        local pid = game.PlaceId
        ts:Teleport(pid, p)
	end
end
