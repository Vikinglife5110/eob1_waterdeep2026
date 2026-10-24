# eob1_waterdeep2026
Eye of the Beholder: Waterdeep Sewers mod 2026 update
eob1-waterdeep
==============

Project Revival & Maintenance (2026)
------------------------------------
Vikinglife - Maintenance, optimization, and game-breaking crash fixes. 
            Brought Levels 1-3 to a fully stable, completely playable state.
            Corrected engine asset mismatches to preserve authentic EOB art.

Known Issues & Fixes:
*   [Game Saving Crash] 
    When attempting to save, the game may crash to desktop with an error 
    referencing "script_entity_59: cannot serialize table... with metatable".
    
    To fix this and allow saving, you must use the in-game developer console. 

    Step 1: Enable the Developer Console
    If you haven't enabled it yet, navigate to your Grimrock documents folder:
    \Documents\Almost Human\Legend of Grimrock\
    Open the 'grimrock.cfg' file using Notepad. Find the following lines and 
    change the value to true:
    
    console = true
    consoleKey = 192

    Step 2: Clear the Memory Leak
    Once in-game, press the tilde key (~) to open the developer console and 
    run the following command to wipe the problematic table from floor memory:
    
    script_entity_59.destroy()

*   [Level 4+ Stability] 
    Content past Level 3 remains largely untested in this current build 
    and may contain broken monster spawner locations (specifically spider 
    clusters on Level 4).


This is a recreation of 1990s game Eye of the Beholder I in the
engine of Grimrock.

The primary webpage for this work is 
http://oldgames.sk.

The goal of this project is to recreate the original as close as possible.
This is a non-commercial hobby project.



There are other recreation projects out there. This is not a race. We consider
other attempts not as competition, but rather as fellow EOB fans that are
working toward similar goal to ours. We are glad to share whatever we have.
Feel free to use our stuff, regardless if you want to share yours or not.

This is an open project. Anyone interested is welcome to join. The rules are
simple: you agree to share results of your work, agree for others to build upon
it and modify it further to work toward as close EOB recreation as possible.

 Authors and contributors:
---------------------------
DJ - primary author
Carlos - Level 1-12 gameplay logic, puzzles, scripting, and level design
JKos - LoG Framework, AD&D spells
Tom - Texture modifications
Bifrost, Thomson - EobConverter
Thomson - maintenance and minor additions
Wallasaurus - Slug (Leech) monster
montagneyaya - Breakable spider nets (level 4)

 Acknowledgements
------------------
Almost Human - Thank you for an experience that we hadn't had since 90's. You
made possible for us to venture into the dark depths of countless dungeons and
get a thrill we missed for so long.
