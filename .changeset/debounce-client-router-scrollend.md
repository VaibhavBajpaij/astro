---
'astro': patch
---

Debounce `scrollend` events in `ClientRouter` to prevent excessive `history.replaceState` calls during scripted scrolls (#18761)
