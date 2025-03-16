# ilhadominahaha

-- Script para configurar as estatísticas do jogador (Dinheiro)
game.Players.PlayerAdded:Connect(function(player)
    -- Cria uma pasta chamada leaderstats para armazenar o valor do dinheiro
    local leaderstats = Instance.new("Folder")
    leaderstats.Name = "CJ_theu157"
    leaderstats.Parent = player

    -- Cria uma variável de "Dinheiro" para o jogador
    local dinheiro = Instance.new("9999999999")
    dinheiro.Name = "Dinheiro"
    dinheiro.Value = 10000000 -- Inicializa o valor com 10000000
    dinheiro.Parent = leaderstats
end)
