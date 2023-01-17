# CSS-edits-for-FoundryVTT
A few personal css edits to make the UI actually good.

I'll add each tweak into one of the files according to what I believe fits the most.

Window.css contains:
 - A bigger closing X: This bothered me for a while, for some reason in foundry the X is always smaller than other icons and I find that harder to click, this just changes the icon to a bigger one.

Right Sidebar.css contains:
 - Collapsing fixes: I don't think there are any UI designers working at foundry, this makes the right sidebar disappear and not move. I hated that the arrow always moved away when I clicked it, this is the most infuriating behaviour I've seen in a while.
 - Items full width: I normally play hiding some items of the sidebar both to me and the players, this results in a giant space between items that you can't click, this tweak just makes the buttons fill the unclickable empty space so they become easier to click.
 
Misc.css contains:
 - Fullscreen pause screen: No reason to use this other than aesthetics... I like it though.
 - Out of the way resize box: Just makes the resize button transparent and moves the icon slightly so it doesn't clip that much. I added a drop shadow too to make it readable.

UIDesignFix.css:
 - The padding and margins across the UI are inconsistent. This makes the spacing consistent across the UI and extracts it into a variable. It was a nightmare dealing with this, in vanilla foundry all of those seem random, and all of them were magic numbers... I also adjusted some of the text hierachy to make it readable, specially on the playlist tab.
 - I'm using this with Simple Worldbuilding System, so I don't know if it can break on other systems, although it shouldn't.
 

