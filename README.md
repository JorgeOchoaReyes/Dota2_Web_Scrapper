# Dota2_Web_Scrapper
This Web Scrapper gets the following data for each Dota 2 Hero: 


hero = 
{

    "Hero_Name": {
    
        "name": "hero_name", 
        
        "attribute": "ex: Strength", 
        
        "Attack Type": "ex: Melee", 
        
        "Lore": "Lore", #DONE
        
        "abilities": [{"First": "abil1"}, {"Second": "abil2"}, {"Third": "abil3"}, {"Fourth": "abil4"}],
        
        "lvl": [{"1": ["opt1", "opt2"]}, {"10": ["opt1", "opt2"]}, {"20": ["opt1", "opt2"]}], 
        
        "stats": {
            "strenght": "123",
            "agility": "123",
            "intellegince": "123", 
            "health": "123", 
            "mana": "123", 
            "damage": "123", 
            "range": "123", 
            "armor": "123",
            "movement": "123"
        },

    }
};

It also obtains the images of the hero Icon, along with Each Ability icon. 
