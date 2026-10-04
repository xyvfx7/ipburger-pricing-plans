# ipburger pricing: Every IPBurger Plan and Rate Explained, and the Per-GB Option for High-Volume Scraping

There is no single IPBurger price, and that's the first thing to understand before you compare anything. IPBurger sells five different proxy products plus a VPN, and two of them are billed by bandwidth while three are billed per IP. Depending on which tab you land on, the answer to "how much does IPBurger cost" ranges from a few dollars a month to a monthly bandwidth bill in the hundreds.

Here's the compressed version. The cheapest way in is the 12-month personal VPN at **$5.41/month**. The cheapest proxy line item is a private dedicated IP at **$4.58 per IP per month** on annual billing. If you want rotating residential traffic, the entry plan is **$59/month with 10 GB included**.

Everything below is that in detail, plus the parts of the price list that the headline numbers hide.

## IPBurger pricing at a glance

| Product | Billing model | Entry price | Countries |
| --- | --- | --- | --- |
| ISP Proxy | Per IP, monthly or annual | $14.41/IP/month, billed annually | 6 |
| Mobile | Per GB, monthly | $69/month, 10 GB included | 100+ |
| Residential | Per GB, monthly | $59/month, 10 GB included | 195+ |
| Fresh Dedicated | Per IP, monthly or annual | $9.58/IP/month, billed annually | 12 |
| Private Dedicated | Per IP, monthly or annual | $4.58/IP/month, billed annually | 5 |
| Personal VPN | Subscription | From $5.41/month on the 12-month plan | — |

The gap between the per-IP column and the per-GB column is where most people get confused. A dedicated IP at $4.58 sounds far cheaper than a $59 residential plan, but you're buying different things: five static addresses you control versus 10 GB of traffic rotated across a shared pool.

## Two billing models, and only one of them resets

IPBurger's own pricing FAQ splits its products in half:

- **Bandwidth-billed** (residential, mobile): you pick a monthly GB allowance. Every request your scraper makes eats into it. Generate as many sessions as you like.
- **IP-billed** (ISP, fresh dedicated, private dedicated): you pay per address per month and get unlimited traffic on those addresses.

One detail matters more than the rest of this section: unused GB do not roll over. Bandwidth is allocated per billing cycle and resets every month. If you consistently leave data on the table, IPBurger's own advice is to downgrade rather than hope the balance carries. For a one-off project that runs two weeks and then goes quiet, that's wasted money by design. For steady daily scraping, it's irrelevant.

All plans are monthly with no long-term contract, and you can cancel from the dashboard. Payment options are cards, PayPal, and crypto including Bitcoin.

## The full IPBurger plan list, product by product

**ISP Proxy — $14.41 per IP per month (annual billing)**

The most popular product on IPBurger's comparison table, and it's easy to see why. These are real ISP-registered static addresses, dedicated to you, with unlimited sessions on the same IP. That combination is what account managers and platform sellers actually pay for: the address never rotates mid-session and nobody else is using it. Coverage is narrow, though — six countries.

**Mobile — $69/month for 10 GB**

Carrier IPs from a shared pool of 20M+ addresses across 100+ countries, rotating or sticky for up to 30 minutes. Targeting goes down to carrier, country, and ASN. This is the product for the targets that block everything else.

**Residential — $59/month for 10 GB**

100M+ rotating addresses across 195+ countries, targeting by country, city, and ASN, sticky or rotating up to 30 minutes per session. The bandwidth model is per GB, so the practical question isn't the entry price but your monthly volume.

**Fresh Dedicated — $9.58 per IP per month (annual billing)**

Static addresses that have never been used before, across 12 countries, exclusive to you. Priced for account creation and sign-up workflows where IP history is the whole point.

**Private Dedicated — $4.58 per IP per month (annual billing)**

Previously used static addresses, exclusive to you, in 5 countries. The cheapest way to get a static IP from IPBurger.

**Personal VPN — from $5.41/month**

A separate product on a separate pricing page. You choose 1, 3, 6, or 12 months at checkout, and the $5.41 figure is the 12-month rate. A 30-day money-back guarantee applies.

## VPN pricing versus proxy pricing

These come off different pages and get compared constantly, so keep them separate in your head. The VPN is a consumer-style subscription for your own browsing: one price, unlimited usage, no traffic accounting, refundable for 30 days. The proxies are metered infrastructure billed by IP or by GB. If you're searching for IPBurger pricing because you want to hide your own traffic, the VPN is the answer and the number is $5.41/month on the annual plan. If you need proxies for automation, marketplaces, or scraping, the VPN is irrelevant and the number you actually care about is the $59 residential entry.

## What the bill looks like as volume grows

Published entry prices only tell you where the ladder starts. Two things change as you scale up:

**Per-GB rates drop, then flatten.** IPBurger's residential and mobile plans are tiered by monthly volume, and a third-party price capture from independent comparison trackers put the top residential tier around **$4.48/GB on a $269/month, 60 GB plan** — roughly 25% below the $5.90/GB you effectively pay on the 10 GB starter. IPBurger's own page also offers custom volume pricing for high-traffic operations. If most of your monthly spend is bandwidth, get a quote rather than buying the starter repeatedly.

**Per-IP prices are cheaper on annual billing.** The $14.41 ISP rate and the $4.58 private dedicated rate are both annual-billing figures; pay month to month and you pay more. Third-party trackers have recorded single-IP monthly ISP pricing closer to $29.95, which is a meaningful difference if you're testing before committing. Related note from the same tracking: buying one dedicated datacenter address is bad value at roughly $18/month, while buying five brings the effective rate down sharply. Bundle the IPs rather than buying one at a time.

If your volume is measured in hundreds of gigabytes, budget for real money here. At around $7/GB, 100 GB of residential traffic lands near $700 in a month.

## Refund windows and the fine print

The money-back terms are product-specific, which is unusual and easy to miss:

- **Residential proxies:** 3 days, only if usage stays under 0.5 GB
- **Static ISP proxies:** 5 days, only if usage stays under 1 GB
- **Fresh and Private Dedicated:** 5 days, with no usage limit

Two practical consequences. First, on bandwidth products, testing consumes your refund eligibility — a single afternoon of aggressive scraping can push you past 0.5 GB and out of the window. Second, IPBurger's own pricing FAQ does not advertise a free trial, only these guarantee windows. Independent trackers have reported the terms differently at various points, so confirm the current window for the specific product before you order rather than assuming.

Other conditions worth knowing: unused bandwidth doesn't carry over, overage never gets silently billed (you top up or upgrade), and you can switch between products from the dashboard at any time.

## Who IPBurger pricing suits, and who it doesn't

IPBurger's prices make sense when the address matters more than the gigabyte. Static ISP addresses at $14.41 per IP per month, exclusive to you, aimed at marketplace accounts, agency client work, and long sessions that need to stay on one identity for weeks. In that scenario the per-address cost is a rounding error next to the value of the accounts behind it. Small-volume residential use — occasional geo-checks, ad verification, a few hundred product pages a month — also sits comfortably at the entry tier, where the per-GB premium is too small to argue about.

It stops making sense when your work is measured in gigabytes. Residential entry works out to roughly $5.90/GB, and even the top published tier stays above what dedicated bandwidth buyers are used to paying elsewhere. If your monthly job is 50 GB of collection, the price ladder is the entire decision.

## The per-GB route: 9Proxy's plans and rates

This is where the search usually ends up going, so here's the alternative priced out properly. 9Proxy is a residential-only provider: 20M+ residential IPs across 90+ countries, sold two ways.

| Plan | What you get | Price | Buy |
| --- | --- | --- | --- |
| 5 GB | Bandwidth package, 180-day validity | $15 ($3.00/GB) | Start with the 5 GB package |
| 50 GB + 5 GB | Bandwidth package, 180-day validity | $105 ($2.10/GB) | Take the 55 GB package |
| 100 GB | Bandwidth package, 180-day validity | $150 ($1.50/GB) | Get 100 GB for $150 |
| 200 GB | Bandwidth package, 180-day validity | $200 ($1.00/GB) | Compare the 200 GB plan |
| 1,000 GB | Bandwidth package, 180-day validity | $800 ($0.80/GB) | See the 1 TB package |
| 2,000 GB | Bandwidth package, 180-day validity | $1,500 ($0.75/GB) | Check the 2,000 GB rate |
| Residential by IP | Fixed IP packages, unlimited traffic per IP, IPs stay valid until used | From ~$0.015–0.018 per IP | Look at the per-IP plans |
| Enterprise | Unlimited data validity, 1 owner + up to 5 members, per-member traffic controls, activity logs, VIP pricing | Custom | Ask about Enterprise pricing |

A few things about the structure are worth more than the per-GB number:

**Bandwidth doesn't expire in a month.** GB plans carry 180-day validity, and Enterprise bandwidth doesn't expire at all. That removes the reset problem entirely — buy 200 GB, use it across three months, and nothing evaporates at the start of a billing cycle.

**Endpoints are unlimited on GB plans.** You're buying data, not addresses. Generate as many proxy endpoints as you want inside your balance, with country, state, city, ZIP, or ISP targeting, and choose sticky or rotating sessions per endpoint. Authentication is username/password or IP whitelisting, and it all runs from the dashboard without a desktop client.

**The IP-based model is the opposite trade.** Fixed IP packages with unlimited traffic per IP, no natural rotation, addresses valid from a few hours up to 24 hours, and a desktop app for local port forwarding. Different tool for a different job — pick it when traffic volume is what you can't predict.

Payment on 9Proxy covers cards, crypto (USDT, BTC, ETH, LTC, DOGE, and others), bank cards, Alipay, Apple Pay, and Google Pay. Registering through the link above applies an invite code at sign-up. The provider has also advertised limited new-user trials subject to availability, so it's worth asking before you buy blind.

## Same job, two bills: residential side by side

|  | IPBurger Residential | 9Proxy Bandwidth |
| --- | --- | --- |
| Entry price | $59/month for 10 GB (≈$5.90/GB) | $15 for 5 GB ($3.00/GB) |
| Effective rate at 100 GB | Around $7/GB, ≈$700/month | $1.50/GB, $150 total |
| Balance expiry | Monthly, no rollover | 180 days |
| Pool size | 100M+ IPs, 195+ countries | 20M+ IPs, 90+ countries |
| Targeting | Country, city, ASN | Country, state, city, ZIP, ISP |
| Proxies sold | Residential, mobile, ISP, fresh and private dedicated | Residential only |
| Refund window | 3 days under 0.5 GB used | Confirm current terms before ordering |

Where IPBurger still wins is coverage. 195+ countries against 90+, and a pool roughly five times the size. If your targets sit in thin geographies or you need static ISP and dedicated addresses, that's decisive and 9Proxy simply doesn't compete there — it has no ISP, mobile, or dedicated product.

Where price decides is anything counted in gigabytes. At 100 GB a month, the difference between the two is hundreds of dollars, recurring. Pool size doesn't offset a four-to-five-fold rate gap on general web collection.

## How to pick in two minutes

1. **You need static, exclusive IPs for marketplace or client accounts.** Buy IPBurger ISP, billed annually. Nothing in the residential-only category replaces it.
2. **You need never-used IPs for account creation.** IPBurger Fresh Dedicated at $9.58/IP/month, and buy more than one — single-IP pricing is the worst value on the page.
3. **You need to hide your own browsing.** IPBurger's VPN at $5.41/month on the 12-month plan, with a 30-day refund window.
4. **You scrape tens to hundreds of GB a month.** Go per-GB. At $1.00–1.50/GB with six months of validity, 9Proxy's bandwidth plans cost a fraction of IPBurger's residential tiers.
5. **You want one address with unlimited traffic and don't care about rotation.** 9Proxy's per-IP packages start around $0.015–0.018 per IP, which is far below IPBurger's $4.58 floor for a static IP — different products, but the gap is worth understanding before you pay for either.
6. **You're unsure and the budget is real.** Start small on both fronts. A 5 GB bandwidth package is $15, and IPBurger's refund window closes after 0.5 GB anyway, so treat the first order as the test.

## FAQ

**Is IPBurger billed monthly or annually?**
Proxies are billed monthly with no long-term contract. The advertised ISP and dedicated rates ($14.41, $9.58, $4.58 per IP per month) assume annual billing; monthly billing costs more. The VPN is sold in 1, 3, 6, or 12-month terms.

**Does IPBurger have a free trial?**
Its pricing page advertises money-back guarantee windows rather than a free trial — 3 days on residential under 0.5 GB, 5 days on ISP under 1 GB, and 5 days with no usage limit on dedicated IPs. Third-party trackers have described the terms inconsistently, so confirm the current window for your exact product before ordering.

**Why do different sites quote different IPBurger residential prices?**
Because the residential product is priced per GB in volume tiers, and reviewers snapshot different tiers on different dates. IPBurger's own comparison table lists $59/month for 10 GB as the starting point; independent captures have recorded roughly $4.48/GB at the top tier. Trust the live pricing page over any article, including this one.

**Is 9Proxy cheaper than IPBurger?**
Per gigabyte of residential traffic, yes — clearly. $1.50/GB at 100 GB against roughly $7/GB at the same volume leaves little room for debate. Per static IP, the comparison doesn't apply, because 9Proxy doesn't sell static ISP or dedicated addresses. Match the product before comparing the number.

If you're weighing a residential bill that keeps climbing, the bandwidth model is the fastest lever you have — 👉 check 9Proxy's current GB packages and per-IP rates, then compare them against whatever tier IPBurger quotes you for your monthly volume.
