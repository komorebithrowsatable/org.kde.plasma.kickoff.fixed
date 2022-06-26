# KDE application launcher (kickoff) fixed version

In this fork I've separated keyboard navigation with mouse one. Hovering an search result with a mouse no longer selects an item, but uses hover animation instead, just like in any other operating system/DE. 
From the UX perspective this means that you'll never select unexpected application/action by unpremeditated mouse move when you're navingting from keyboard (searching, moving selection with arrow keys, etc). To be honest, I can't imagine a situation when selecting an item with mouse and then pressing enter instead of clicking is useful. 

This also resolves https://bugs.kde.org/show_bug.cgi?id=455674 and similar bugs. 
