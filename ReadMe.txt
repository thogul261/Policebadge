coding is from https://github.com/DOSE-420/qb-policebadge and https://github.com/Zerofour04/esx_PoliceBadge
the scripts that was outdated that i put togheter to make it work agein hope u like it :D

Add to qbcore item.lua 
	["specialbadge"] 				 = {["name"] = "specialbadge", 			  		["label"] = "Police Badge", 			["weight"] = 1000, 		["type"] = "item", 		["image"] = "specialbadge.png", 	["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,	   ["combinable"] = nil,   ["description"] = "Special Badge of Law Enforcements"},


add the image to qb-inventory or the inventory u using in to image

when u done that u add the item to ur Police armory in config like this.

        [1] = {
            name = "specialbadge",
            price = 0,
            amount = 50,
            info = {},
            type = "item",
            slot = 1,
            authorizedJobGrades = {0, 1, 2, 3, 4}
        },

remeber to add it to the slot u want to use from 1 to whaver u wanna use and u could see a picture of a badge when u put it in ur hotbar it could start a animation and show ur badge with ur face on it. and other player will see it too.
