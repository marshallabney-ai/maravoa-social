# Post schedule

One row per post. Times are 7:00 PM Central unless noted. Status values:
`queued` (written, not in Metricool), `draft` (in Metricool as a draft, awaiting Marshall's batch approval),
`scheduled` (approved, will auto-publish), `published`, `dropped`.

| Date | Post file | Metricool uuid | Status |
|---|---|---|---|
| 2026-11-09 Mon | instagram-2026-11/posts/01-what-maravoa-is.md | 6754683254222112966 | scheduled |
| 2026-11-11 Wed | instagram-2026-11/posts/02-color-card.md | -1827604016853006633 | scheduled |
| 2026-11-13 Fri | instagram-2026-11/posts/03-client-booking-no-app.md (fallback carousel) | 2793723756376703452 | scheduled |
| 2026-11-15 Sun | instagram-2026-11/posts/04-booth-renter-money-math.md | -4856691772599545874 | scheduled |
| 2026-11-16 Mon | instagram-2026-11/posts/05-today-page.md (fallback single image) | -5812800889193676496 | draft |
| 2026-11-17 Tue | instagram-2026-11/posts/06-schedule-c-export.md | -2130822273553053628 | scheduled |
| 2026-11-19 Thu | instagram-2026-11/posts/07-switching-from-vagaro-or-glossgenius.md (prices confirmed against maravoa-landing origin/main compare text Nov 12; Metricool create failed Nov 12, retried Nov 13, see note) | 7203855157052392369 | scheduled |
| 2026-11-22 Sun | instagram-2026-11/posts/08-no-show-hour.md (created Nov 13, see note) | -7563914234321744728 | scheduled |

Week 1 moved up from Nov 17 to 22 to Nov 9 to 15 on Marshall's word ("Start tomorrow, right?", Nov 8); the posts' own files still say Week 1 / Week 2 and the old suggested days.

Nov 12 weekly run: 05 and 06 went in as Metricool drafts. Creating 07 failed with "Metricool couldn't process the media at 'https://raw.githubusercontent.com/marshallabney-ai/maravoa-social/main/instagram-2026-11/visuals/07-switching/02.png' right now. Try again in a moment." Per the task rules the run stopped creating, so 07 and 08 stay queued for a Hal session or next week's run to add.

Nov 13 Hal session (Marshall's app request, 8:28 AM Central: "add the 2 missing posts"): the 07 retry succeeded and 08 was created, both as Metricool drafts at 7:00 PM Central with the captions, hashtags, alt text and images from their post files. The full Nov 16 to 22 batch (05 to 08) now awaits Marshall's approval.

Nov 13, 2026: Marshall approved the Nov 16 to 22 batch, "Yes, schedule all 4" (approver Marshall; recorder Hal side session, Claude Opus 5.5). 06, 07 and 08 switched from draft to scheduled in Metricool at about 11:57 AM Central, read back as scheduled for 7:00 PM Central on Nov 17, 19 and 22, content unchanged. 05 (Mon Nov 16) did not switch: the update was blocked by the session's auto-mode permission check, so it stays a draft and needs Marshall to schedule it in Metricool or allow the update.
