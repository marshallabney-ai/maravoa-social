# 03 Gift cards

- **Format:** carousel, 2 slides, 1080 x 1350
- **Day:** Fri Nov 27, 2026, 7:00 PM Central
- **Pillar:** the work at the chair; booth renter money
- **Visuals:** `visuals/03-gift-cards/01.png`, `02.png`

## Slides

| # | Overlay text | Screen |
|---|---|---|
| 1 | GIFT CARDS / Gift card season is here. / Issue them, track the balance and redeem them at checkout. | Gift Cards page of the demo Solo account (Juniper Lane), phone, `shots/juniper-solo-gift-cards-mobile-390x844-20260729.png`, cropped |
| 2 | SOLO, $29 A MONTH / Gift cards live at the same checkout. / Gift cards issued and redeemed in checkout; sales tax on retail, kept apart from services; inventory counts down as you sell. | Text slide, no screen |

## Caption

```
Somebody is going to ask you for a gift card this weekend.

In Maravoa's Solo plan, gift cards are issued and redeemed at the same checkout as the service. Each card shows its code, who bought it, who it is for, and the balance left. Retail and sales tax ring up at the same checkout too, and all of it lands in the same numbers.

Solo is $29 a month and every plan starts with 14 days free. Gift cards are part of Solo, not Stylist.

See it on the live demo, no login needed. Link in bio.
```

## Hashtags (8)

```
#giftcards #salonsuite #hairstylist #independentstylist #smallbusinesssaturday #hairstylistlife #salonbusiness #salonsoftware
```

## Alt text

1. Maravoa Gift Cards page on a phone for a demo solo owner, showing 2 active cards, $100.00 outstanding balance, and a card with $40.00 remaining, its buyer, issue date and expiry.
2. Text slide: Gift cards live at the same checkout. Gift cards issued and redeemed in checkout. Sales tax on retail, kept apart from services. Inventory counts down as you sell.

## Claim check

- "Gift cards issued and redeemed in checkout", "Sales tax on retail, kept apart from services", "Inventory counts down as you sell": /for-solo, 11:00 am "Retail, gift cards and sales tax, without a second app" (`maravoa/__init__.py`).
- "Solo, $29: adds inventory, retail, gift cards, sales tax": `llms.txt`; FAQ "Solo is $29 and adds ... gift cards"; homepage plan card. Stylist ($19) does not list gift cards.
- "14 days free": FAQ, "A new signup gets 14 days free and enters a card at signup".
- Code, buyer, for, issued, expires and balances are visible on the real screen.
- Checked against maravoa-landing origin/main on Nov 15, 2026.
