---
'jw-library-linker': patch
---

Fix the automatically inserted quote repeating the reference when the link is wrapped in the configured prefix and suffix (for example `(Matthew 24:14)`): such a line counts as holding nothing but the reference and is replaced by the quote.

After a quote replaces a reference the cursor now lands on a fresh line below it, and a collapsed callout template is inserted open so the quote can be read straight away — it stays foldable by hand.

The "Expanded Callout" preset now uses `> [!quote]+`, which is expanded and foldable, instead of `> [!quote]`, which could not be folded at all.
