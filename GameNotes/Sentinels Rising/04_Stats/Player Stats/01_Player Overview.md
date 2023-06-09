This should have everything that is attached to the player character. 
Including;
All the variables that are on the player (Health, stamina, defense, attack, etc.)
Anything the player can **store**
Anything the player can **use**
How is progression of the player tracked? Experience added? Currency earned/spent?
Link any features that the players will use

---
Critical %, Parry Chance, Swing Speed, Attack Multiplier (Melee; Musculature, Kinematics. Ranged; Kinematics, Potential)
Accuracy, Critical Damage, Damage, Recoil, Stability, Fire Rate, Magazine Size, Reload Speed, Penetration, Movement Speed

---
# Player Stats
The player has a set of stats that correlate to a number of different systems in the game. The player can modify their base stats through ability ranking, gear, and weapons. 
![[SR_AST_Abilities_FlowChart.png]]

Stats will be 0-11 or 12 'notches' on the player UI. These will be modifiers to base stats (Ranged or Melee) to within combat. The average starting player will be 3 on this scale. They will have 22 pts.  to create their character from. 
%%If we give the player 22 extra points, on top of 3 in each category, they will be able to max out 3 other categories in from the Character Creation Menu%%
The average character starts with 3 points in each attribute, and has an additional 7 points to allocate at character creation, that means the character can have up to 10 points in any given attribute, since 3 + 7 = 10.
![[SR_Stats_BasePlayer_AbilityPointAllocation.png|450]]
This gives the player some flexibility in creating their character, allowing them to specialize in one or two attributes while still having a decent amount of competency in the others. It's also worth noting that characters who focus heavily on one attribute may be more vulnerable in other areas, so there's a trade-off to consider.
%%See my above comment, we're allowing the player to have too much power without much progression from the beginning. Decrease the number of points we allow the player to allocate during the Character Creation Phase%%

### Musculature
This stat represents the player's raw physical power and ability to deal devastating melee attacks. A high musculature stat means that the player can hit harder and break through enemy defenses more easily.
This attribute is on a scale of 0-11, where 0 represents a character with very little physical strength and 11 represents a character who can lift massive weights and deal devastating blows.

### Kinematics
This stat encompasses the player's agility, speed, and jumping ability. A high kinematics stat means the player can quickly maneuver around the battlefield, dodge enemy attacks, and jump to higher platforms with ease. It also represents the player's ability to store and release power for devastating attacks.
This attribute is on a scale of 0-11, where 0 represents a character who is slow, clumsy, and not very agile, and 11 represents a character who is incredibly fast, agile, and capable of impressive acrobatics.

### Reconstruction
This stat represents how quickly the player can recover from damage. A high reconstruction stat means the player's health and shield regenerate quickly, allowing them to stay in the fight longer. Weapon ammunition is also governed by this stat as the suit will regenerate the new magazine for a 'reload' time/effect. 
This attribute is on a scale of 0-11 as well, where 0 represents a character who takes a long time to recover from injuries and 11 represents a character who regenerates health and shields very quickly.

### Tenacity
This stat determines how much damage the player can withstand before taking serious harm. A high tenacity stat means the player can absorb more damage and continue fighting, while a low tenacity stat means they must be more careful and strategic in their approach.
This attribute is on a scale of 0-11, where 0 represents a character who can't take much damage and 11 represents a character who is very difficult to take down.

### Potential
This stat represents the effectiveness of the player's skills and abilities in dealing damage to enemies. A high potential stat means that the player's abilities are very powerful and can take down enemies quickly, while a low potential stat means that the player will need to rely more on basic attacks to deal damage.
This attribute is on a scale of 0-11 as well, where 0 represents a character whose abilities are not very effective and 11 represents a character whose abilities are incredibly powerful.
