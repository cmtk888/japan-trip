# Japan Trip · Dec 7–13, 2026

Itinerary website for a 12-person trip to Osaka, Hakone and Tokyo.

- **Website:** https://cmtk888.github.io/japan-trip/
- **Source of truth:** the claude.ai artifact (https://claude.ai/artifact/FHHoz5iBPqetqdxFigCg9f). Edit the itinerary there, then sync `index.html` to this repo. GitHub Pages deploys `main` automatically.

## How syncing works

1. Edit the artifact.
2. Download its `index.html` and strip the artifact service's outer page wrapper (the leading `<!doctype html><html><head>…<body>` line and the trailing `</body></html>`).
   Edits can also go the other way: change `index.html` here and publish it to the artifact (done this way on 2026-11-24). Either way, diff the two first so neither side's edits get lost.
3. Before committing, check for booking/confirmation/order numbers: this repo and site are **public**.
4. Commit and push to `main`. Pages rebuilds in about a minute; browsers may cache the old page for up to 10 minutes (hard-refresh to see the update).

## Privacy rule

Never commit flight order numbers, hotel confirmation numbers, passport details or personal contact info. These were removed on 2026-10-22, and the repo was recreated with a clean history so they don't appear in any commit.

## Trip overview

| Dates | Base | Plan |
|---|---|---|
| 12/7 Mon | Osaka | Arrive: Hong Kong group (7) via KIX; Fuzhou group (5) via Narita → KIX |
| 12/8 Tue | Osaka | Kyoto day by private car (10:00 departure): Fushimi Inari, Takashimaya lunch, Kiyomizu-dera, Arashiyama, back to Osaka by car |
| 12/9 Wed | Osaka | Kobe beef lunch (Ishida), Umeda shopping, eel dinner (備長) |
| 12/10 Thu | Hakone | Kuromon Market, Shinkansen Shin-Osaka → Odawara, onsen hotel (dinner included) |
| 12/11 Fri | Tokyo | Hakone half day (pirate ship, Owakudani, Glass Forest), private car to Shinjuku |
| 12/12 Sat | Tokyo | Shibuya lunch (ひろかつ) and shopping, Kabukicho seafood dinner |
| 12/13 Sun | Depart | Private car to Narita T1; HX609 15:20 to HKG, MF810 15:30 to Fuzhou |

## Status (as of 2026-11-24)

### Booked
- All flights (outbound and return, both groups)
- Osaka Airbnb × 2 (12/7–12/10)
- Hakone hotel, 6 twin rooms with dinner + breakfast (12/10–12/11)
- Tokyo Airbnb, Shinjuku (12/11–12/13)

### Urgent
- **Shinkansen, 12/10 Shin-Osaka → Odawara, 12 seats.** Sales opened 11/10. Pick option A (ひかり654, 14:18) or B (ひかり650, 12:18) and book on smartEX in two orders of 6 by about 12/3 so the group sits together.

### To book
- Kyoto private car, 12/8 full day (10:00 pickup at Nihonbashi, drop-off at Tsurutontan Soemoncho around 18:00; about 8 hours). The driver sheet on the site is ready to send.
- Hakone private car, 12/11 half day + drop-off in Shinjuku
- Narita private car, 12/13, 10:30 from Shinjuku
- Restaurant reservations for 12: Ishida 12/9 12:00 (first confirm it's open Wednesday lunch), 備長 12/9 18:30, ひろかつ 12/12 12:30
- Hakone Glass Forest advance tickets (after group A headcount is set)

### To confirm
- Osaka host: luggage pickup after lunch on 12/10
- Tokyo host: arrival around 18:00 on 12/11
- Hakone hotel: arrival time and dinner slot on 12/10

### Still open
- Meals: 12/7 dinner, 12/13 breakfast

### Decided against
- Sagano scenic train on 12/8 (removed 2026-11-24). The car now picks the group up at Arashiyama and drives straight back to Osaka, so no train tickets are needed.
- Kifune on 12/8: too far north, would add about 1.5 hours of driving.

## Progress log

| Date | Change |
|---|---|
| 2026-10-22 | Repo recreated with clean history after removing booking numbers. Itinerary page published on GitHub Pages. |
| 2026-11-09 | Synced booking alert, Shinkansen options A/B and restaurant reservation details from the artifact. README added. |
| 2026-11-24 | Dropped the Sagano train. Kyoto day shifted one hour later (10:00 departure, Arashiyama 15:40–16:45, dinner still 18:00). Map, driver sheet, booking alert and to-do list updated on both the artifact and the site. |

## Next steps
1. Book the Shinkansen (see Urgent).
2. Confirm the three restaurant reservations, starting with whether Ishida serves Wednesday lunch.
3. Book the three private cars (Kyoto 12/8, Hakone 12/11, Narita 12/13).
4. Send the Kyoto driver sheet once the car is booked.
