[h1]Artifact Manager[/h1]

This is a combination of some artifact-related mods I’ve been playing with.
The mod list is getting a little too long, so I decided to combine some of
them in one mod.

Some features were inspired by other existing mods, and some are just the
mod embedded (if they’re small enough).   

So far, here are the mods I’ve combined:

[oList]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2748508571]Clear Artifact Levels[/url]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2776119489]Court Artifacts in Inventory[/url]
[*] [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2752573001]Distribute Artifacts (note: only on default list view)[/url]
[*] [url=https://steamcommunity.com/workshop/filedetails/?id=2747305366]Auction Off Artifact[/url] 
[/oList]

Extra credits and thanks to the following:

[list]
[*] [url=https://steamcommunity.com/profiles/76561198127983144]JmBl[/url] - for the custom artwork.
[*] [url=https://steamcommunity.com/id/Krumps]Krumps[/url] - Spanish localization. 
[*] [url=https://steamcommunity.com/profiles/76561198385823171]Dillo[/url] - German localization

[/list]

[h1]To The Original Authors[/h1]
All of the content are their authors’ property, and I was just trying to
reduce the clutter in my mod list, and my UI.  Ping me if this isn’t 
something you’d like available, and I’ll take it down.

Note:  All the extra features are disabled in the game rules by default.

[h1]FEATURES:[/h1]

[b]Note:  All the extra features are disabled in the game rules by default.[/b]

[list]
[*] Added game rules for stuff.
[*] Integrated edit artifact description mod.
[*] Mass distribute artifacts with minimal clicks.
[*] Repair ALL with one click.
[*] Sell ALL unused with one click.
[*] Combine and Upgrade artifacts game rules. 
[*] Upgrading artifacts in-place.
[/list]

Upgrade mechanics is straightforward, and simplistic.  You can control this with the Upgrade game rule, which you can disable.
All it does is max out all the existing modifiers, and make the artifact illustrious.  You cannot upgrade relics, or anything
else with already maxed out modifiers.  The upgrade cost depends on what rarity is the starting point, which are the following:
[list]
[*] Illustrious = 1000g
[*] Famed = 2200g
[*] Masterwork = 3300g
[*] Common = 5000g
[/list]

[h2]Combining Artifacts[/h2]

Combining artifacts is now a thing.  There’s an extra tab, and two extra buttons.  In order to use it, you need to do the following:
[list]
[*] Select a primary artifact.
[*] Select a secondary artifact that’s not also the primary.  
[*] Go to the advanced actions, and you should have another button.
[*] Click and lose lots of gold!
[/list]

Now for the cost, which would need feedback.  The cost scales on the quality
of both artifacts individually.  The resulting artifact will be the the next
quality up OF THE PRIMARY artifact!  This might be an important detail since
the cost are different depending.  Here’re the current values:

[table]
[tr]
[th]Quality[/th]
[th]Cost for primary[/th]
[th]Cost for secondary[/th]
[/tr]
[tr]
[td]Illustrious[/td]
[td]6500[/td]
[td]4000[/td]
[/tr]
[tr]
[td]Famed[/td]
[td]5000[/td]
[td]3000[/td]
[/tr]
[tr]
[td]Masterwork[/td]
[td]4500[/td]
[td]2000[/td]
[/tr]
[tr]
[td]Common[/td]
[td]2000[/td]
[td]1000[/td]
[/tr]
[/table]

And yes, these two values are added together!  Watch out!  Furthermore, you can
only do this once every 5 years.  Might make that a game rule as well.  Open
to suggestions.

FILTERS for bulk operations are available.  You can filter whom to give it to, and what quality to give.
(IGNORE the Dynasty option — didn’t work and was replaced with Close Family option instead)


[h2]Changes Since (reverse chronological)[h2]

[list]
[*] Custom backgrounds for artifact panels.
[*] Working version of combine artifacts.
[*] Filters for repair and selling artifacts.
[*] Gifting court artifacts now only pick landed targets, except courtiers.
[*] Added icons for the other artifact types.
[*] Added artifact owner face at top left.
[*] Updated for 1.11
[*] Removed all of Rhox’ stuff, replacement code under way. !!THIS WILL PROBABLY BREAK YOUR EXISTING SAVE GAME!!.
[*] Updated for 1.9.*
[*] Added more localization entries (Thanks to Alba Vituli for checking these).
[*] More Spanish localization courtesy of [url=https://steamcommunity.com/id/Krumps]Krumps[/url]
[*] Added game rules
[*] Bulk operations added
[*] Updated to 1.8*
[*] German localization, courtesy of [url=https://steamcommunity.com/profiles/76561198385823171]Dillo[/url]
[*] Used the default “Gift Artifact” localization tag
[*] There is now a checkbox to keep the inventory open while giving away your artifacts.
[*] Integrated [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2752573001]Distribute Artifacts[/url]
[*] Thumbnail added
[/list]