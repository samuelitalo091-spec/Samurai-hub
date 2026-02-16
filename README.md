# Samurai-hub
Config = {
    Team = "Pirates",
    Configuration = {
        HopWhenIdle = true,
        AutoHop = true,
        AutoHopDelay = 60 * 60,
        FpsBoost = false,
        blackscreen = false
    },
    Items = {

        -- Melees 
        AutoFullyMelees = true,

        -- Swords 
        Saber = true,
        CursedDualKatana = true,
        TrueTripleKatana = true,
        SharkAnchor = true
        
        -- Guns 
        SoulGuitar = true,
        DragonStorm = true
        
        -- Upgrades 

        RaceV2 = true
        RaceV3 = true
    },
    Settings = {
        StayInSea2UntilHaveDarkFragments = false
    }
}


loadstring(game:HttpGet("https://raw.githubusercontent.com/hhl29042008-ops/script/refs/heads/main/cac"))()
