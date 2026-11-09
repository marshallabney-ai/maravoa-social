# Maravoa on Instagram: launch plan (November 2026)

Drafted Nov 8, 2026, approved for drafting by Marshall the same day. Drafts only: no account has been created, nothing has been posted, no one has been messaged, and nothing has been spent. Marshall creates the account and approves every post before it goes out. Hal may later schedule approved batches.

Every product claim in this folder was checked against `origin/main` at `aa538cf` (`llms.txt`, `maravoa/homepage.py`, the homepage, pricing, FAQ and features data, `landing_page_status.md`), the live www.maravoa.com pages /for-stylists, /compare/vagaro and /compare/glossgenius, and the vetted wording in PR 19 (`drafts/review-listings-2026-11/`). Every image is a real Maravoa screen: either a file already in `shots/` or a fresh capture of the public demo at https://demo.maravoa.com/demo on Nov 8, 2026 (demo data only).

## What is in this folder

| Path | What it is |
|---|---|
| `plan.md` | This plan |
| `posts/01-...md` to `posts/08-...md` | Eight posts for weeks 1 and 2: format, visual, caption, hashtags, alt text, day |
| `visuals/` | Finished images at Instagram sizes, one folder per post, plus `profile-picture-1080.png` |

## 1. Who the account is for

US hair professionals who run their own book:

- **Booth renters** (independent contractors) who pay rent on a chair in someone else's salon and file their own Schedule C. Maravoa's Stylist plan, $19/month.
- **Single-chair owners**: a suite, a studio or a mobile business where they are the whole shop. Solo, $29/month.
- **Small studios** with up to 5 working professionals, some renting and some employed. Studio, $59/month. (Salon at $119 for up to 10 exists, but this account speaks first to the people at one chair.)

What they care about, in the site's own terms: a book that belongs to them and moves with them, clients who book without an app, the last formula in front of them before they mix, no-shows on an hour they still pay rent on, and knowing what the chair actually made when tax time comes.

The account does not speak to consumers looking for a stylist. Maravoa has no marketplace.

## 2. Account setup (Marshall does these by hand)

**Account type: professional, Business.** Business (rather than Creator) gives a category label and an email contact button. Both types work with everything below.

**No Facebook at any step.** Creating an Instagram account does not need Facebook. During the switch to a professional account, Instagram may offer to connect a Facebook Page and may prompt to add the account to an Accounts Center with Facebook. Skip both every time. Nothing in this plan needs either. (Meta's developer overview says professional accounts are served "without requiring a linked Facebook Page"; I did not walk the in-app setup screens myself, so if any screen will not let you continue without Facebook, stop and tell the session, do not work around it.)

**Handle ideas, in order of preference. Check each in the app; none was checked here:**

1. `@maravoa`
2. `@maravoa.app`
3. `@maravoahq`
4. `@getmaravoa`
5. `@usemaravoa`

**Name field** (searchable, separate from the handle): `Maravoa | Salon Software`

**Category:** Software (or Product/service if Software is not offered).

**Bio** (Instagram's limit is 150 characters; this is 131):

> Salon software for booth renters, suite owners and small studios. Booking, color cards, money. Your book stays yours. 14 days free.

**Link** (the only clickable link on the profile):

```
https://www.maravoa.com/?utm_source=instagram&utm_medium=social&utm_campaign=launch-2026-11
```

Label it "Try the live demo or start a free trial". The homepage carries both buttons, so the bio link does not need to pick one.

**Contact button:** email, hello@maravoa.com. No phone.

**Profile picture:** `visuals/profile-picture-1080.png`, the canonical mark from `favicon.svg` (not redrawn) centered on the site's alabaster background, sized so Instagram's circle crop keeps it whole. At thumbnail size the thin strands read lighter than the mark in the site nav; if it looks too faint on your phone after upload, say so and a later session can try a tighter crop of the same mark (no redraw).

**Highlights:** none at launch. After two weeks, pin three feed posts instead (01 What Maravoa is, 03 Client booking, 07 Switching); pinning is free and needs nothing else.

## 3. Content pillars

1. **The work at the chair.** Real screens doing real jobs: the color card, client booking with no app, the Today page, the waitlist. Posts 02, 03, 05, 08.
2. **Booth renter money.** What the plan costs per year, no cut of services, income beside expenses, the Schedule C export. Posts 04, 06.
3. **Your book is yours.** Portability, and fair comparisons for people already on another tool. Posts 01 (last slide), 07.
4. **Try it yourself.** Every post points to the live demo (no login) and the 14-day trial. Reels are screen recordings of the demo, so people see exactly what they would click.

Rules every post follows: no em dashes; real screens only, marked "Real screen · Maravoa demo data"; no mockups, stock photos or people; no testimonials and no customer story (the eclips story is still unpublished); no appointment import claim (client list import from a CSV is the only import mentioned); no feature the site or feature registry does not back; nothing about Facebook.

## 4. Cadence

Four feed posts a week for the first two weeks, then three or four a week. Suggested schedule (adjust freely; the days matter more than the dates):

| # | Post | Format | Suggested day |
|---|---|---|---|
| 01 | What Maravoa is | Carousel, 5 | Week 1 Tue (Nov 17) |
| 02 | The color card | Single image | Week 1 Wed (Nov 18) |
| 03 | Client booking, no app | Reel (fallback: carousel, 5) | Week 1 Fri (Nov 20) |
| 04 | Booth renter money math | Carousel, 4 | Week 1 Sun (Nov 22) |
| 05 | The Today page | Reel (fallback: single image) | Week 2 Mon (Nov 23) |
| 06 | The Schedule C export | Carousel, 3 | Week 2 Tue (Nov 24) |
| 07 | Switching from Vagaro or GlossGenius | Carousel, 5 | Week 2 Wed (Nov 25) |
| 08 | The no-show hour | Single image | Week 2 Sun (Nov 29) |

Week 2 skips Thanksgiving (Thu Nov 26) and the Friday and Saturday after it, when stylists are fully booked. Sunday and Monday are common salon days off, which is when people in the trade scroll. Suggested time: evening, 7 to 9 pm in the audience's time zone; after two weeks, move it to whatever Instagram Insights says.

Optional and free: share each feed post to Stories the same day with a link sticker. Stories expire, so they are a nudge, not a second calendar. If you do, use the Story link below so Story traffic shows separately from the bio link:

```
https://www.maravoa.com/?utm_source=instagram&utm_medium=story&utm_campaign=launch-2026-11
```

## 5. Measuring it (first-party only, no Meta pixel)

The site already records every visit's `utm_source`, `utm_medium` and `utm_campaign` (`maravoa/monitoring.py`, `classify_source`). A visit that arrives through the bio link is classed as source "other" with detail `instagram`, and the admin dashboards label it "instagram". Nothing needs to change on the site, and no Meta code goes on it.

Where to look:

- **Funnel:** `https://www.maravoa.com/admin/measurement?source=other:instagram`, with the date range set to the launch weeks. Shows sessions from Instagram and how far they got (demo clicks, signup clicks).
- **Visit list:** `https://www.maravoa.com/admin/measurement/visits?source=other:instagram`. One row per confirmed, non-automated visit.
- **Sunday review:** the weekly metrics feed groups this traffic under "Other", so Hal's Sunday numbers will show it there rather than as its own line.
- **Instagram's own Insights** (free in the app, no pixel): reach, profile visits, and link taps on the bio link. Link taps compared with site sessions from `instagram` shows how many taps survive the in-app browser.

Note on bots: Meta's link preview fetcher (`facebookexternalhit`) is already filtered out as automated, so pasting the link into a chat will not inflate the numbers.

What counts as working after two weeks: a steady trickle of sessions from `instagram` in the visit list, some of them reaching the demo, and at least one trial start you can trace to it. For scale, the site had about 20 human visits and 0 trials in the week of Nov 1 to 7. A new account with no followers and no spend should be judged on those first-party numbers, not on likes.

## 6. Scheduling without Facebook: what I found

**Short answer: yes. Instagram's own app, Instagram's publishing API, Buffer's free plan, and Later can all post to an Instagram business or creator account with no Facebook Page and no Facebook profile.** Each has limits, listed below. Checked Nov 8, 2026.

**1. Instagram's built-in scheduling (free, recommended for launch).** Instagram's Help Center ("How to create and manage scheduled posts and Reels on Instagram", https://help.instagram.com/439971288310029/) says a public account can schedule Reels, photos and carousel posts from the app, "up to 25 posts a day, up to 30 days in advance". Flow: Create, pick Post or Reel, add the caption, More options, turn on Schedule this post, pick the time. Scheduled posts can be edited, rescheduled or deleted from Profile, Menu, Scheduled content. No Facebook anywhere. This covers everything in this plan, and Marshall approves each post by being the one who schedules it.

**2. Instagram's content publishing API (for a script Hal might run later).** Meta's developer overview (https://developers.facebook.com/docs/instagram-platform/overview) describes two setups: "The Instagram API with Instagram Login serves Instagram professional accounts without requiring a linked Facebook Page", and its comparison table lists Content publishing as supported on that path. The content publishing guide (https://developers.facebook.com/docs/instagram-platform/content-publishing) covers single images, videos, Reels and carousels of up to 20 items, JPEG only for images, and a limit of 100 API-published posts in a rolling 24 hours (one section says 50; either is far above this plan's needs). Caveat: using the API means registering an app with Meta's developer platform. I did not verify whether a Meta developer account can be created without a Facebook profile, so treat that step as **unverified and a likely blocker**. Nothing in this plan needs the API.

**3. Buffer (free plan works).** Buffer's help page "Connecting your Instagram account to Buffer" (https://support.buffer.com/articles/connecting-your-instagram-account-to-buffer-n9Ad6veXsu) describes connecting a Business or Creator account through Instagram login (Channels, Connect Channel, Instagram, Professional, Connect to Instagram) and says: "This connection method supports automatic publishing, analytics in Insights, and comment management on all plans." Without a Facebook Page it cannot add locations, add collaborators, like Community mentions, or add music to Reels that publish automatically. Buffer's pricing page (https://buffer.com/pricing) lists a Free plan with up to 3 channels and 10 scheduled posts per channel, refilled as posts go out. One older Buffer article still says a Page is required; the current connection guide supersedes it. Signing up is a new account for Marshall or Hal to create, at $0.

**4. Later (works, but no free plan).** Later's help page "Instagram and Facebook Page Requirements in Later" (https://help.later.com/hc/en-us/articles/1500001601602) says: "You can connect your Instagram profile and publish posts without a Page", while Social Inbox, location tagging, hashtag search, Story analytics and a few shopping features need one. Later's pricing page (https://later.com/pricing/) shows only a 14-day free trial; the cheapest plan is Starter at $18.75/month billed yearly. That is a paid tool, so it is out of scope unless Marshall decides otherwise.

**Recommendation:** schedule in the Instagram app itself for the first two weeks. If Hal takes over scheduling later, Buffer's free plan is the no-cost, no-Facebook option; Hal would need his own Buffer login with access to the Instagram account, which is Marshall's call.

## 7. Boosting a post without Facebook: what I found

**Short answer: yes, once.** Instagram's Help Center ("About Meta Ad Account options for ads on Instagram", https://help.instagram.com/1338916436473267/) says: "If you are boosting a post from your Instagram professional profile for the first time, you won't have to connect to a Meta Ad Account or Facebook Page." The same page adds that "The ability to create Instagram ads without an ad account connection is limited to businesses who are boosting their Instagram posts for the first time." Payment details are entered in Instagram on the first boost, and the campaign is managed inside Instagram. Boosting with a Meta Ad Account, which Meta recommends, needs a Facebook login, so that path is a **blocker** under the no-Facebook rule.

Two cautions from the same page: on the Instagram iPhone app, Apple may add a service fee of up to 30% when you add funds there; and "the first time" wording means the no-Facebook route may not stay open for repeat boosts.

**Costs are Marshall's decision.** This plan assumes no spend. If you ever boost, boost a post that has already brought visits in the first-party numbers, not the newest one.

## 8. Before each post goes out (5-minute check)

1. Open the post file and the matching folder in `visuals/`.
2. Read the caption once against today's site. Prices and plan details come from `maravoa/homepage.py`; if pricing changed since Nov 8, fix the caption first.
3. Post 07 only: the Vagaro and GlossGenius prices are as checked on their own pricing pages on Sep 1, 2026, the date the compare pages carry. Re-check both pricing pages on the day; if either number moved, update the slide and caption or skip the price line.
4. Paste the alt text (Advanced settings, Accessibility, Write alt text), schedule, done.

## 9. What Marshall needs to decide or do

1. **Create the account** with the setup in section 2, skipping every Facebook prompt. Pick the first free handle from the list.
2. **Approve or edit each of the eight posts.** Nothing goes out without your yes.
3. **Reels:** posts 03 and 05 are Reels. Each file has a shot list for a 15 second phone screen recording of the demo. I did not record them: this machine has no MP4 encoder, and Instagram takes MP4 or MOV. You or a later session can record them on a phone with its built-in screen recorder in a few minutes. If you would rather not, each Reel has a finished fallback (a carousel for 03, a single image for 05).
4. **Spend:** none needed. Boosting and paid schedulers are your call.
5. **Hal scheduling later:** whether Hal gets access through Buffer's free plan, or keeps scheduling to the Instagram app on your phone.
6. **One wording question for later, not blocking:** the homepage and /for-stylists say the $19 Stylist plan includes the Schedule C export, and the demo's Stylist account shows the Export tax summary CSV button, but one line in the feature registry says the tax summary export is "not the Stylist tier". Post 06 follows the site and does not name a tier. Worth a look in salon-new so the registry and the site agree.
