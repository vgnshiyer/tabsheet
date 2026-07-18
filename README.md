# tabsheet

Minimal guitar tab editor. One HTML file, no build step — open `index.html` in a browser.

## Use

Click a cell (or just start typing) and enter frets as you play:

- `0–9` — fret number; type two digits quickly for frets 10–24
- `h p b r s t x ~ / \` — hammer-on, pull-off, bend, release, slide, tap, mute, vibrato, slide up/down
- `|` — bar line across all strings
- `space` — step right without writing
- `-` — erase and step right
- `arrows` — move cursor (lines auto-extend to the right)
- `backspace` — erase and step left, `delete` — erase in place
- `enter` — jump to next line (creates one at the end)
- `⌘I` / `Ctrl+I` — insert column, `⌘⌫` / `Ctrl+⌫` — delete column
- `⌘Z` / `Ctrl+Z` — undo, `⇧⌘Z` / `Ctrl+Y` — redo

Everything autosaves to localStorage. **copy** / **download** export standard ASCII tab
(`e|---5-7---|` format). Hover a line to reveal **×** to delete it.
