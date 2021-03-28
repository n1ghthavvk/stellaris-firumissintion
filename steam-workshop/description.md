Did your first ruler vanish inexplicably after they lost their first election?
 - No more!

[b]Your initial ruler will now become a governor when they lose an election.[/b]

Check the Leader screen, the election details and your factions screen to confirm the fix is working and your ruler has not vanished into thin air.

[i]Should be save game compatible, for as long as the initial ruler is still in office. 
Ironman compatibility status questionable due to changes for a vanilla event chain (please leave a comment if you notice otherwise).[/i]

[h1]Details[/h1]
This mod uses [i]on_actions[/i] and is thus 100% compatible to every other mod out there. 
It works by intercepting the game from getting rid of your original ruler by listening to the following action:
[code]on_ruler_removed[/code]
Then it calls a custom event using three scripted_effects that execute the magic to keep your ruler alive.
They clone the ruler before the original one is deleted by the game.
But don't worry, the ruler will have all of its original memories implanted and retained!

[h1]Notes[/h1]
When converting to a governor, the leader will keep all of its previous traits that are not vanilla.
So if you use a mod that adds ruler traits - the leader will keep them as a governor.
This is a "feature" of the vanilla game which I can only add exceptions to - such as all the vanilla traits, which are correctly "kept" as ruler traits (by removing them from the old leader and assigning them to the new leader correctly).
Any level-up traits that may apply to the governor as well (such as Stubborn, etc.) will be applied.
The same will be done for special traits like Brain Slugs, Erudite, Psychic, Cyborg, etc.

[i]Thankfully game version 2.6 brought us a small update to the clone_leader effect, so we can now specify a class. Otherwise this mod wouldn't be possible like this.[/i]

[h1]Obligatory Footnote[/h1]
[url=https://github.com/n1ghthavvk/stellaris-firumissintion][img]https://i.imgur.com/0nVeF3I.png[/img][/url]
Looking for my other creations?
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=1998204784][img]https://i.imgur.com/wJgHgx8.jpg[/img][/url]
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=1868834704][img]https://i.imgur.com/sbtUpRC.jpg[/img][/url]
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=2080968400][img]https://i.imgur.com/IBj3WfX.jpg[/img][/url]
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=2036087802][img]https://i.imgur.com/JCGnvng.jpg[/img][/url]

Thanks for reading the description, downloading & playing with my mods!

[strike][i]Don't forget to leave a comment, smash that like button, subscribe and hit the bell icon!!![/i][/strike]

[img]https://i.imgur.com/p7Fv1Z6.gif[/img]
