getgenv().SpamSkill = false

getgenv().AutoUseRaceV3 = true

getgenv().AutoUseRacev4 = true

getgenv().SpamSkillOnRaceV4 = true

getgenv().Invisible = false

getgenv().InCombatNoReset = false

getgenv().Team = "Pirates" -- Marines

getgenv().TweenSpeed = 350 -- 350 max or Get Tp Back

 getgenv().Setting = { -- Select Weapon, Self Explain

        ["Melee"] = {["Enable"] = true,["Delay"] = 1,

          ["Skills"] = {

            ["Z"] = {["Enable"] = true,["HoldTime"] = 2.5,["TimeToNextSkill"] = 0,},

            [ "X"] = {["Enable"] = true,["HoldTime"] = 0, ["TimeToNextSkill"] = 1,},

            ["C"] = {["Enable"] = true,["HoldTime"] = 0, ["TimeToNextSkill"] = 0.5,},

            },

        },

        ["Blox Fruit"] = {["false"] = true, ["Delay"] = 4,

            ["Skills"] = {

                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},

                ["X"] = { ["Enable"] = true, ["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},

                ["C"] = { ["Enable"] = true, ["HoldTime"] = 0,["TimeToNextSkill"] = 0, },

                ["V"] = { ["Enable"] = true, ["HoldTime"] = 0,["TimeToNextSkill"] = 0,},

                ["F"] = {["Enable"] = false,["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},

            },

        },

        ["Sword"] = { ["false"] = true, ["Delay"] = 2,

            ["Skills"] = {

                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.5,["TimeToNextSkill"] = 0,},

                ["X"] = {["Enable"] = true, ["HoldTime"] = 0.5, ["TimeToNextSkill"] = 0,},

            },

        },

        ["Gun"] = {["Enable"] = true, ["Delay"] = 1,

            ["Skills"] = {

                ["Z"] = {["Enable"] = true,["HoldTime"] = 0,["TimeToNextSkill"] = 0,},

                ["X"] = {["Enable"] = true,["HoldTime"] = 0,["TimeToNextSkill"] = 0,

                },

            },

        }

    }

 loadstring(game:HttpGet('https://raw.githubusercontent.com/vinhuchi/temp-repos/main/FreeAutoBounty.lua'))()

