# honey extension: what it does now, why the coupon pool shrank, and how to switch to cash back you can actually withdraw

Most people typing "honey extension" into a search box are trying to settle one of two questions. Either they want to know what the little orange "h" in their toolbar is doing, or they've already read something that made them want to delete it and want to know what replaces it.

Both questions have concrete answers, and neither one gets answered by a sentence like "Honey is a free tool that saves you money." So let's go through what the extension does today, what demonstrably changed, and where the cash actually ends up.

## What Honey actually does in 2026

PayPal Honey is a free browser extension that watches for shopping sites, pops up at checkout, and runs through available coupon codes against your cart. It's on Chrome, Firefox, Safari, Edge and Opera, and the company lists support for 30,000+ stores. There's also a mobile app for iOS and Android, a Droplist feature that tracks a product's price and emails you when it drops, and Amazon seller comparison that factors in shipping and Prime status.

That core function still works the way it always did. The "h" icon turns orange on a supported site. At checkout you click Apply Coupons, Honey tests the codes it has, and applies the biggest one that works. If nothing works, it tells you that too.

The part that changed is what Honey gets out of it, and how much it's actually able to find.

## The thing that made "just install Honey" stop being default advice

In December 2024, a YouTuber named MegaLag published an investigation alleging two separate things. First, that Honey was overwriting existing affiliate cookies at checkout — so when a shopper clicked a creator's link and then interacted with Honey's popup, the commission for that sale went to PayPal instead of the person who drove the click, even when Honey found no coupon at all. Second, that Honey was suppressing better coupon codes in favour of ones its merchant partners preferred.

More than 25 lawsuits followed. The creator cases were consolidated as *In re PayPal Honey Browser Extension Litigation*, Case No. 5:24-cv-09470-BLF, in the Northern District of California. The procedural history is genuinely messy and worth stating accurately rather than dramatically: the court dismissed the first consolidated complaint in November 2025 for lack of standing, plaintiffs filed a second amended complaint in January 2026 with actual merchant agreements attached, and in mid-2026 the court declined to dismiss it — so the case is heading into discovery, with a tentative trial date floated for late 2027. PayPal denies the allegations. There's no settlement, no certified class, and nothing for anyone to claim.

Two consequences landed faster than the litigation.

**Google changed the rules.** The Chrome Web Store policy was updated so extensions can only insert affiliate codes when a discount, cashback, or donation is actually provided. Honey responded by updating its extension in early 2025, and testing by 9to5Google found the old "click Got it and we silently take the commission" behaviour was gone.

**The affiliate networks pushed back.** Rakuten Advertising terminated Honey from its network in January 2026, cutting off roughly 2,000 retail partners at once. Honey was later reinstated after Rakuten published a stand-down SDK that Honey implemented.

## The numbers behind the backlash

This is the part people usually miss, because the story is reported as a trust story when it's also a product story. Honey's inventory got smaller.

| What changed | Before the December 2024 investigation | Reported after |
| --- | --- | --- |
| Chrome Web Store installs | 20M+ | ~13–14M |
| Merchant partnerships | ~35,000 | ~28,000 |
| Coupon codes in the database | ~90,000 | ~50,000 |
| User-submitted codes | ~29,000 | ~3,000 |

Of the roughly 50,000 codes still in the pool, reporting on the case says at least 10,000 are expired but still get applied at checkout. That matters more than the politics: coupon harvesting depends on volume, and a database that lost most of its user-contributed codes is a weaker coupon tool than the one that got 20 million installs.

Honey also responded to the Chrome policy by switching on cashback across nearly all partner stores — but reporting on the network data puts most of those rates between 0.1% and 1%. That restores commission eligibility at very low cost to Honey. It does not make the extension a meaningful earner for you.

## How Honey pays, and why that matters

Honey doesn't pay cash. Purchases through it can earn PayPal Rewards points, and the redemption floor is 1,000 points for a $10 gift card from participating stores. If you have a US PayPal account in good standing, you can also apply points at PayPal checkout instead.

So the comparison that actually matters isn't "which extension finds more coupons." It's:

- Honey gives you a discount at checkout plus points that convert to gift cards.
- A cashback platform gives you back a percentage of the order in money you can move to your bank or PayPal.

Those are different products, and the second one has a clearer floor. If Honey's cashback is 0.3% at a store and converts into gift cards at a 1,000-point threshold, that's a rounding error you'll wait months to touch.

## So should you uninstall it?

Here's a straight answer instead of a both-sides shrugging. Honey is not malware. It collects browsing and purchase data, which is stated in its privacy policy and in the Chrome Web Store data disclosure, and it doesn't handle your card details at checkout. Downloads from the official Chrome Web Store listing or joinhoney.com are safe. Fake extensions and phishing emails using the Honey name are the real risk, and both are avoidable.

Whether to keep it depends on what you're using it for:

- **You want coupon codes auto-tested at checkout.** Honey still does this, on a smaller code pool. Keep it, but expect fewer hits.
- **You want the largest possible coupon pool.** Coupon-only extensions that didn't shrink are a better bet, and Capital One Shopping and RetailMeNot Deal Finder are the usual alternatives.
- **You want money back you can actually withdraw.** Honey was never built for that. Points-to-gift-cards is a different thing from cash, and the difference is the whole point.

That third case is where the rest of this article lives.

## How a cashback platform changes the maths

The mechanic is worth understanding once, because it explains both why you don't pay anything and why the payouts aren't instant.

When you start a shopping session through a cashback platform and click through to a retailer, an affiliate cookie tags your session. If you buy, the retailer's affiliate network confirms the sale and pays the platform a commission — typically a share of order value, sometimes a flat fee. The platform keeps some to run the business and passes the rest to you.

Your checkout price doesn't change. The retailer was already spending that money on marketing; the platform just redirects part of it to you instead of keeping it.

ShopBack has run on that model since 2014 and now operates in 13 markets. The scale figures it publishes are 20M+ active annual members, US$900M+ in cashback paid globally since founding, 20K+ merchant partners overall including 2,000+ in the US, and US$5.5B in annual GMV driven to partner merchants. It was named to Fast Company's 2026 Most Innovative Companies list.

One honest caveat, because it applies to every cashback tool including ShopBack: clicking "Activate Cashback" on a retailer page does overwrite any affiliate cookie you already had from a creator's link. That's how the last-click model works. The difference from the Honey allegations is consent — you're the one clicking activate — but if you specifically want to support a creator's link, buy through their link and skip cashback on that order. You can't do both.

## Cashback shows up twice, and only the second one is spendable

This trips up almost every new user, so here it is plainly. A purchase first shows as **Pending**, usually within 48 hours. It moves to **Confirmed** after the retailer's return window closes — often 30 to 90 days for retail, and after the trip completes for travel bookings. Only confirmed cashback is withdrawable.

That delay isn't a ShopBack invention. Retailers reserve the right to reverse commissions on returns, cancellations and fraud, so every platform holds funds until that window closes. It does mean cashback is a bad tool for short-term budgeting and a good tool for purchases you were making anyway.

## Every way to use ShopBack, and what each one costs

ShopBack has no paid tier, no subscription and no service fee — which is unusual enough that it's worth being explicit: there is no pricing page with a Basic and a Pro column, because everything is free and funded by merchant commissions. So instead of a plan comparison, here's what's actually on offer across the platform, all of it free.

| Option | What you get | Cost | Where it's available | Get started |
| --- | --- | --- | --- | --- |
| Free account (web + app) | Cashback at 20,000+ merchants globally, tracker, payouts via PayPal or bank | Free — no sign-up, monthly or withdrawal fee | All 13 markets | [Create a free ShopBack account](https://bit.ly/ShopbacK) |
| Browser extension (Chrome) | Detects partner stores as you browse, activates cashback with one click, also surfaces coupon codes | Free | Most markets | [Install the ShopBack cashback extension](https://bit.ly/ShopbacK) |
| Travel Planner | Price comparison across integrated OTAs (Trip.com, Pelago, Dida) with cashback on top | Free | Select markets | [Check ShopBack travel cashback rates](https://bit.ly/ShopbacK) |
| Quests | Limited-time, merchant-specific bonus cashback challenges | Free | Select markets | [See current ShopBack quests](https://bit.ly/ShopbacK) |
| ShopBack Play | Cash for completing game milestones and sign-up offers | Free | Select markets | [Browse ShopBack Play offers](https://bit.ly/ShopbacK) |
| Snaps (receipt scanning) | Cashback from uploading receipts for eligible offline purchases | Free | US | [Try ShopBack Snaps](https://bit.ly/ShopbacK) |
| ShopBack Pay | In-store and in-app payment earning extra cashback | Free | Select markets only | [Check ShopBack Pay availability](https://bit.ly/ShopbacK) |
| Gift cards and vouchers | Earn instant cashback buying gift cards in-app, then spend them in store or online | Free | Select markets | [Buy gift cards with cashback](https://bit.ly/ShopbacK) |

Rates themselves are set per merchant and change constantly, which is why nobody credible publishes a fixed list. Everyday retail tends to sit in the 1–5% range, promotional categories can go much higher, and flat-dollar offers exist alongside percentage ones.

## The new-user bonus, and the terms attached to it

ShopBack's referral programme currently pays a **$15 sign-up bonus** to the new account in the US, with the referrer earning a separate bonus once conditions are met. It is not instant cash, and the conditions are the reason most people never see it:

- You have to sign up through a referral link (or enter the referral code during sign-up) for the platform to attribute it to anyone.
- You need to add a payout method — PayPal or a bank account, depending on market.
- You need a small amount of confirmed cashback from real purchases. Sources citing ShopBack's terms have put the threshold at $5 in some markets and higher in others, and the window is 180 days from account creation.
- Self-referrals, orders that get cancelled or refunded, and stacking with other new-customer promotions don't count.
- Your first purchase needs to go through ShopBack's link, not direct to the retailer, or the tracking never starts.

👉 [Set up your shopback account](https://bit.ly/ShopbacK) — the code is applied at sign-up, so you don't need to type anything.

## What to expect once you're in, including the annoyances

Reviews of the Chrome extension sit around 4.3 stars across roughly 80 ratings, and the complaints are consistent and worth knowing before you install:

- The pop-up notifications on partner sites can't be switched off per-site, and some users find them intrusive.
- Cashback confirmation can take weeks or months, particularly on slower-retail categories.
- Some purchases don't track at all. Ad blockers, aggressive privacy settings and clearing cookies mid-session are the usual culprits; missed purchases have to be reported manually.
- Performance on Edge and some desktop setups is less consistent than Chrome.
- Amazon cashback in the US was cut back significantly — the current structure is $1 on your first-ever ShopBack Amazon purchase and $0.50 on subsequent orders, capped at five cashback rewards a month on orders over $5. Anyone who signed up purely for Amazon should know that going in.

The structural limits apply to every platform in this category: cashback works on online purchases only (with limited card-linked exceptions), 1–3% is the realistic everyday rate, and the feedback loop is measured in months. Where cashback earns its keep is on high-value purchases. A $1,200 laptop routed through a 3% merchant is $36 back; the same effort on a $12 phone case isn't worth the tab.

## Honey vs ShopBack, side by side

|  | Honey | ShopBack |
| --- | --- | --- |
| What it's built for | Auto-testing coupon codes at checkout | Cashback on purchases |
| Cost | Free | Free |
| Rewards currency | PayPal Rewards points, redeemable from 1,000 points for a $10 gift card | Cash, withdrawn via PayPal or bank transfer |
| Cashback depth | Reported at 0.1–1% at most cashback-active partners | Merchant-set, commonly 1–5%, higher in promotions |
| Cashout floor | 1,000 points | Low — $5 confirmed balance in the US per support docs |
| Payout speed | Points post after purchase; redemption at threshold | Pending ~48 hours, confirmed after the retailer's return window, typically 30–90 days |
| Store coverage | 30,000+ claimed; ~28,000 merchant partnerships reported | 20,000+ globally, 2,000+ US |
| Extra tools | Droplist price tracking, Amazon seller comparison | Travel Planner, Quests, Play, Snaps receipts, ShopBack Pay |
| Track record | Active class action at the pleading/discovery stage; no settlement | Operating since 2014, US$900M+ paid out |

The cleanest way to read that table: Honey is a discount tool with a small rewards layer bolted on, and ShopBack is a payout tool with a coupon layer bolted on. They solve different halves of the same problem.

## Short answers to the questions people actually search

**Is the Honey extension still safe to use?** Yes, if you installed it from the official Chrome Web Store listing or joinhoney.com. It doesn't take your card details. The unresolved issues are about affiliate attribution and coupon quality, not data security.

**Does Honey still find coupons?** Yes, on a significantly smaller database. Reporting on the case puts the code pool at roughly 50,000, down from 90,000, with a chunk of what remains expired.

**Were the allegations proven?** No. PayPal denies them, earlier complaints were dismissed for standing, and the case is still being litigated with no settlement or certified class.

**Do I have to uninstall Honey to use cashback?** No, but don't run both at checkout on the same order. Coupon and cashback extensions override each other's tracking, which is one of the most common reasons a purchase fails to register. Pick one as your primary and keep the other off during checkout.

**Is ShopBack free, with no upsell?** Yes. No subscription, no sign-up fee, and no withdrawal fee on standard payouts.

If your goal was always to get something back on purchases you'd make anyway, points you can only spend on gift cards was never the right vehicle. 👉 [Start your shopback account and claim the new-user bonus](https://bit.ly/ShopbacK), or if you'd rather see the numbers before committing, 👉 [look at what ShopBack currently pays at the stores you use](https://bit.ly/ShopbacK) — the rates are public, the terms are on every merchant page, and reading them takes about thirty seconds per store.
