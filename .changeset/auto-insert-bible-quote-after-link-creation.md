---
'jw-library-linker': minor
---

Add an opt-in "Insert quote automatically" setting that inserts the Bible quote right after a link is created from the suggestions (silent mode, `/b` and "create link and open"). The text is fetched in the background so typing is never blocked, and a failed lookup shows a notice instead of writing anything to the note.

Quotes now cover multi-range and multi-chapter references: the reference is looked up part by part and the parts are stitched into a single quote. This also applies to the existing quote commands and the context menu.
