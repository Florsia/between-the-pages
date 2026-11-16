# Between the Pages — Faceless Modest Editorial design system

The approved gift photograph is the visual benchmark. Every screen must feel like the same premium reading sanctuary.

## Visual identity
- Palette: ivory #F5EFE6, latte #D8C3AC, caramel #A67B5B, espresso #50372D, olive #89917C, antique gold #B18A4C. Five selectable themes retain the typography, spacing, shapes and photographic identity.
- Editorial Georgia serif for headings; system sans for practical controls. Consistent warm outline icons, rounded cards (20px), controls (13px), generous breathing room, visible focus, 44px minimum controls where practical.
- Original, locally stored photographs only for decorative imagery. No remote stock-photo IDs. No visible faces, no conspicuous foreign words, no invented religious script, no Christmas decorations. Real library covers and user photos remain authentic.
- Warm natural light, linen, modest fabrics, books, blank notebooks, olive leaves, ceramic, soft gold, coffee and tea. Restrained rather than stereotypical faith cues. Ramadan artwork has no beverages or people.

## Image map
- Gift and home: original approved gift composition and complementary reading nook, 1440px wide.
- editorial-00–11: Jan–Dec, distinct original seasonal compositions.
- editorial-12: Ramadan (blank pages, crescent, lantern, olive fabric).
- editorial-13: Eid al-Fitr (gift, flowers, lantern).
- editorial-14: Eid al-Adha (books, olive fabric, architecture, flowers).
- editorial-15: Creative Corner / Quote Studio (pressed flowers, blank journal).
- Library categories, author pages, goals, timer, memories, settings, insights and other forms use relevant artwork from the same collection, with smaller masthead images on functional pages. No decorative photograph competes with a real book cover.
- Month grid always retains the twelve distinct base photographs; Islamic season is signaled with a tag and a special detail image.
- Interface text stays HTML, bilingual and accessible. Exports use the same palette and local artwork where requested.

## Acceptance criteria
- Verify all local image hashes, check actual crops, all routes, navigation, contrast and portrait/desktop layout. No guessed image URLs.
- Preserve all approved features and user data; no new modules or discarded functionality.
- Test actual iPhone camera/OCR, exports/sharing, offline storage, timer lock-screen behavior, language coverage, and responsive appearance before gifting.
- Generated imagery and source inspection are not a substitute for a physical-device test.

## Book Club and My Kobo
- Book Club: homepage feature with editorial-03 artwork (books and tea); discussion form uses editorial-15 (journal). Existing book covers remain authentic. Club notes stay separate from personal notes and use the same private local backup.
- My Kobo: Settings feature with editorial-07, matching linen and coffee palette; import previews, controls and forms follow the same design system. No password collection, no direct sync claims. StoryGraph CSV import is user initiated; existing records are skipped unless the user expressly opts into refreshing statuses and dates. Kobo TXT/Markdown annotations are attached to a selected book.
- Verified with synthetic CSV and mock DOM tests; real Kobo/StoryGraph exports and physical iPhone file selection and sharing still require testing.
