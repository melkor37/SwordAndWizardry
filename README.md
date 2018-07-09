# SwordAndWizardry
Roll20 API scripts for Swords and Wizardry.  Working on this for the following functions:
> Parse statblocks (shortened and long) into attributesd
> Create token actions for attacks / saves / etc. (inspired by Creature Gen by Ken L.
> Create PC self-spawn with creation walk-through (right now I have them in seperated scripts.. will merge once I'm happy with each functions)
> auto - generate stats during token drop (roll HD for hitpoints, etc)
> Make NPCs as compatible with current C.S. as possible

**7/9/2018**
>  - Posting alpha script
>  - If you're looking at this script and you're not me, I'M SORRY!! It's ugly as hell

**TODO:**
>  - Find a way to make token-action abilities to appear without having to refresh them in the ability list
>  - transfer some variables to npc_variable to avoid character sheet auto calc removing them
>  - Used d20swsrd.com to create initial results-- used 4 spaces to distinguish statblocks from flavor text, set up alternate method
>    i.e. Search('HD:') or something similar
>  - Create menu macro --same problem as abilities.
>  - Use c.s. css to format attack abilities.
  
>  - CLEAN UP attack section.. attempt to seperate pulling the stats and breaking down attacks, hd, etc into own function
>  - pulling combat related notes from bio-- or put link to bio (already in as attribute) in attack macro.
