[tl;dr]

A Zotero plugin that lets you instantly search your library for other works by the author of any selected item — via right-click menu or keyboard shortcut.

[Features]

Context menu — right-click any item in the centre pane:

Single-author item: Search by Author appears directly in the menu and triggers the search immediately.
Multi-author item: Search by Author… opens a submenu listing each creator by name. Click the one you want.


Keyboard shortcut — with an item selected, press Ctrl+Shift+A (Windows / Linux) or Cmd+Shift+A (macOS):

Single-author item: searches immediately.
Multi-author item: a pick-list dialog lists all creators. Choose one and press OK.


In both cases the plugin switches Zotero's built-in quick-search to Title, Creator, Year mode, navigates to the library root (so your whole library is searched, not just the current collection), and fills the search bar with the creator's last name.

[Requirements]

Zotero 7.0 or later (tested on Zotero 9). Compatible through Zotero 10.

[Installation]

Download the latest search-by-author.xpi from the Releases page.

In Zotero, open Tools → Plugins.

Click the ⚙ gear icon → Install Add-on From File…

Select the downloaded .xpi file and confirm.

Restart Zotero if prompted.


[Usage]

Context menu

Right-click any item in Zotero's centre pane. If the item has a single author, you will see Search by Author in the menu. If it has multiple authors, you will see Search by Author… — hover over it to reveal a submenu with each creator listed individually.


Keyboard shortcut

Select a single item in the centre pane and press Ctrl+Shift+A (or Cmd+Shift+A on macOS). For multi-author items a small dialog will appear; select the author you want and click OK.


What the search does

The plugin navigates to My Library, switches the search mode to Title, Creator, Year, and enters the author's last name. The result is identical to typing that name into the search bar yourself — Zotero's normal search results, filters, and sorting all work as usual. You can refine the search further from there.
