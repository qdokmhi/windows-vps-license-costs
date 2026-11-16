# Cheap Windows VPS: What the License Really Adds, Which Plan to Pick, and How Far a $300 Credit Goes (Full Price Table)

Vultr's smallest Windows-capable cloud server costs **$10/month** for the hardware and **$16/month** for the Windows license, so the real entry price is **$26/month**. Keep those two numbers separate in your head, because the cheap Windows VPS offers you're about to compare handle licensing in three different ways, and only one of them makes the headline figure the amount that leaves your account.

Below is Vultr's complete Windows plan list with both line items, the arithmetic on which tier is actually worth buying, the terms behind the $300 credit, and a straight comparison with Contabo, OVHcloud, Fasthosts and Liquid Web on the three things that decide whether a cheap Windows VPS stays cheap: whether the license is inside the price, how long the promo price lasts, and whether backups cost extra.

> **Quick picks**
> - **Just need an RDP box for one small tool or a test environment:** 1 CPU / 2 GB at **$26/month** total ($10 server + $16 license). Pick a Core image to keep the RAM footprint down.
> - **Most people, including one small site or a line-of-business app:** 2 CPU / 4 GB at **$52/month** total. The $15 plan saves $5 and halves your RAM, so it's the wrong trade.
> - **SQL Server, several IIS sites, or a desktop you'll sit in front of all day:** 4 CPU / 8 GB at **$104/month** total.
> - 👉 [See the full Windows plan list and current license fees](https://www.vultr.com/servers/windows?ref=9738262-9J)

## Vultr's Windows plans: base price, license, and the total you pay

Vultr bills a Windows instance as two line items on the same invoice. The base price covers CPU, RAM, SSD and bandwidth; the license price is added on top and varies by plan. Both columns come straight from Vultr's own Windows comparison table.

| Plan (CPU / RAM) | SSD | Server price | Windows license | Total per month | Order |
| --- | --- | --- | --- | --- | --- |
| 1 CPU / 2 GB | 55 GB | $10 | $16 | **$26** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 2 CPU / 2 GB | 65 GB | $15 | $32 | **$47** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 2 CPU / 4 GB | 80 GB | $20 | $32 | **$52** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 4 CPU / 8 GB | 160 GB | $40 | $64 | **$104** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 6 CPU / 16 GB | 320 GB | $80 | $96 | **$176** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 8 CPU / 32 GB | 640 GB | $160 | $128 | **$288** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 16 CPU / 64 GB | 1280 GB | $320 | $256 | **$576** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |
| 24 CPU / 96 GB | 1600 GB | $640 | $384 | **$1,024** | [ Choose this plan](https://www.vultr.com/servers/windows?ref=9738262-9J) |

Bandwidth scales with the plan, from 2 TB on the entry tier to 15 TB on the 24-CPU one. Every tier is available with Windows Server 2016, 2019, 2022 or 2025, in Standard or Datacenter, and each of those comes in a Core variant (no graphical shell) or a full desktop experience. Bringing your own license isn't an option: Vultr states that existing Windows Server licenses can't be transferred to the platform, so the license column is unavoidable if you want Windows.

## The license runs $16 per vCPU, and that decides which tier to buy

The license column is close to linear: $16 per CPU, all the way up. One CPU adds $16, two add $32, twenty-four add $384. The server price doesn't scale the same way, which produces two useful quirks.

The first is the 2-CPU pair. At **$15 + $32 = $47** you get 2 GB of RAM; at **$20 + $32 = $52** you get 4 GB on the same CPU count. Five dollars a month for double the memory is the best upgrade on the page, and it's the reason the $15 tier is hard to recommend to anyone.

The second quirk shows up at the top. A 24-CPU plan carries **$384/month** in licensing alone, which is more than fourteen times the entry plan's entire cost. If you need that many cores, the license is now the dominant part of the bill, and a provider that folds Windows into the plan price can come out cheaper even with a higher-looking sticker. Per-core Windows pricing is great for small instances and expensive for large ones.

> Hourly billing is the other thing to get right. Vultr bills by the hour up to a monthly cap (its billing documentation puts the cap at 672 hours), so a short-lived test instance costs cents. A powered-off instance keeps billing until you destroy it.

## The $300 credit: a month of headroom, not a year of free hosting

Vultr's coupon page lists **FLY300VULTR** for $300 in free credit, alongside a $200 code, a $250 code, and VULTRMATCH, which matches your first deposit dollar for dollar up to $100. The terms printed next to all of them are identical: new customers only, the credit applies to select products only, it can't be combined with any other offer, and further restrictions apply.

The detail that changes how you should use it is the expiry. The trial credits are reported to expire **30 days after signup**, not 30 days after first use, and any balance left at expiry simply stops existing while your linked payment method takes over. Do the arithmetic on that and the $300 is worth roughly one month of whatever you run: enough to keep eleven $26 instances going for a month, or to spend four weeks on a 4-CPU / 8 GB box at $104 and still have change. It is a genuinely useful sandbox for a migration test or a load test. It is not a discount on your first year.

Two things to check before you count on it. The terms say "select products only," so confirm at checkout that the Windows license fee on your chosen plan is covered rather than billed separately. And don't stack codes: the page is explicit that offers can't be combined.

👉 [Check the current Vultr coupon codes and their terms](https://www.vultr.com/coupons?ref=9738262-9J)

## Three ways a Windows VPS gets made to look cheap

**Where the license sits.** Liquid Web puts "License Included" in the page title and prices its 2 vCPU / 4 GB / 80 GB plan at $119/month, with Plesk Obsidian, 100 GB of Acronis backups and DDoS protection inside that number. GigeNET takes the opposite approach and lists Windows Server licensing as a flat $20.28/month added to any plan. Contabo and OVHcloud fold Windows into the plan price, so the number you see is the number you pay. None of these is dishonest, but "$3.99/month" and "$3.99/month plus a license" are different products, and the second one is usually the one being sold.

**How long the promo price lasts.** Fasthosts advertises its 2 vCPU / 4 GB plan at £14/month against a £22 list price, saving 36%, and the small print says "for 3 months." You save £24 across the first quarter, then pay £22 from month four onward. Contabo ties its discounted rates to the first 24 months, which is a much longer runway but still a defined one. Liquid Web's 15% discount requires a two-year commitment paid up front: $2,856 today for the entry plan. A price that only exists inside a contract term isn't the price of the server.

**Whether backups are included.** OVHcloud includes a daily backup covering the previous 24 hours on its Windows VPS plans. Contabo includes one to three snapshots depending on tier, with an auto-backup add-on sold separately. Fasthosts sells Cyber Protect as a purchasable add-on. Liquid Web bundles 100 GB of Acronis. On a $26/month server, a $10 backup add-on is a 38% cost increase, which is exactly the kind of line that doesn't appear in a comparison of headline prices.

## Same entry price, very different hardware

Currency matters here, so nothing below has been converted. Read each row as its own quote.

| Provider and plan | vCPU | RAM | Storage | Price | Promo window | Windows license |
| --- | --- | --- | --- | --- | --- | --- |
| Vultr, 1 CPU plan | 1 | 2 GB | 55 GB SSD | $26/mo total | standard rate | separate, $16/vCPU |
| Contabo, CLOUD VPS 6 | 6 | 12 GB | 200 GB SSD or 100 GB NVMe | €6.00/mo | first 24 months | included |
| OVHcloud, VPS-2 | 4 | 8 GB | 75 GB NVMe | from $8.50/mo | standard rate | included |
| Fasthosts, VPS 2 | 2 | 4 GB | 120 GB NVMe | £14/mo, then £22 | first 3 months | included |
| Liquid Web, 4 GB plan | 2 | 4 GB | 80 GB | $119/mo | 15% off on a 2-year prepay | included, plus Plesk and backups |

On raw resources per unit of currency, Contabo's €6.00 tier and OVHcloud's $8.50 tier beat Vultr's $26 entry plan comfortably, and saying otherwise would be silly. What the Vultr price buys instead is hourly billing with a monthly cap, a plan ladder that runs to 24 CPU / 96 GB without changing providers, current Windows Server 2025 images, and a documented API for provisioning. If your workload is a permanent 12 GB Windows box in Europe, Contabo is the cheaper answer. If your workload is four hours of testing on Tuesday, fifty instances for a week, or a machine that has to sit next to a specific application, hourly billing is worth more than the resource gap.

Against Liquid Web the comparison flips. Vultr's 2 CPU / 4 GB Windows instance totals $52/month against Liquid Web's $119, but Liquid Web's price includes Plesk, 100 GB of backups and a choice of management levels (fully managed, core managed, unmanaged). Vultr is self-managed across the board.

👉 [Compare the 4 CPU / 8 GB Windows plan at $104/month all-in](https://www.vultr.com/servers/windows?ref=9738262-9J)

## Who shouldn't buy the cheapest tier

**Anyone who needs a control panel.** Plesk on the $26 plan means running a panel on 2 GB of RAM next to Windows itself, which is unpleasant. Budget for the 4 GB tier, or accept the command line.

**Anyone who wants the provider to manage patching.** Every Vultr tier is unmanaged. If you want someone else to own Windows Update, IIS configuration and incident response, that's a different product category and a different price bracket.

**Anyone who might switch to Linux later.** Windows licensing is attached to the deployment, so a Windows VPS is a Windows VPS. IONOS is unusually explicit about this on its own product page: buy a Windows VPS there and you cannot switch that server to Linux afterwards, you have to place a new order; customers who want to swap operating systems are told to buy the Cloud Server line instead. Other providers vary, so read the OS-change policy before you pay, particularly if you're choosing Windows mainly because it's familiar.

**Anyone who needs 16 or more cores.** At $256 to $384/month in licensing alone, a provider that includes Windows in the plan price is worth pricing out first.

## Setup checklist for a fresh Windows VPS

The order matters more than the individual steps, because a Windows server exposed on RDP before it's patched is the most commonly attacked machine on the internet.

1. Connect over RDP with the IP, username and password Vultr gives you at deploy time.
2. Run Windows Update and reboot until it stops finding updates.
3. Restrict RDP at the firewall to trusted IPs, or put it behind a VPN. Vultr's own firewall and the Windows firewall can both be used, and using both is better.
4. Replace the default administrator password with something long and unique, and create a standard user account for day-to-day work. Log in as administrator only when you're changing something.
5. Remove roles and services you don't use. Every one you leave installed is attack surface.
6. Install what you actually bought the server for: IIS, .NET, SQL Server, then configure DNS if you're hosting sites.
7. Turn on automatic backups and basic monitoring before you put anything real on it. Vultr documents an automatic backup feature; check whether it's billed on top of your plan.

## FAQ

**Is the Windows license included in Vultr's monthly price?**
No. Vultr states plainly that Windows Server licenses are not included in the base monthly price and are charged as an additional fee based on the compute plan you select. On the current table that fee is $16 per vCPU per month.

**Is a $3.99/month Windows VPS real?**
You'll find Windows VPS listings under $5/month, and they aren't necessarily fake. Ask three questions before treating one as your floor: how many vCPUs does that price include, is a Windows license bundled or added at checkout, and is the price a first-term promotion. A 1 vCPU box with a license added can easily land four to six times the advertised figure.

**Can I switch the server to Linux afterwards?**
On Vultr, the license is tied to the plan you deploy, so if there's a real chance you'll want Linux, deploy Linux and skip the $16/vCPU. Providers differ on whether an in-place OS change is allowed at all, and at least one major host requires a fresh order, so check the policy rather than assuming.

**Does hourly billing beat monthly?**
For anything that runs continuously, no: hourly billing is capped at the monthly price, so a server up all month costs the same as the monthly rate. Hourly wins when instances are short-lived. Remember that stopping an instance doesn't stop the meter; only destroying it does.

**How much RAM do I need for RDP plus one small site?**
2 GB works with a Core image and one lightweight app. For a full desktop experience with IIS and a small database on the same box, 4 GB is the realistic minimum, and that's the $52/month plan. SQL Server with a real workload wants the 8 GB tier.

## What to do next

Match the plan to the job rather than to the price list. A single RDP session for a small tool or a build agent: the 1 CPU / 2 GB at **$26/month** total is enough, and paying more buys you capacity you won't use. One site or one line-of-business app: 2 CPU / 4 GB at **$52**. SQL Server, multiple sites, or a machine several people log into: 4 CPU / 8 GB at **$104**, and above that compare included-license providers before you commit, because $256 to $384 a month of licensing changes the ranking.

Before you pay, confirm two things in the cart: that the Windows license fee for your chosen plan is showing as part of the total you calculated, and whether backups are included or billed separately. Those two lines are where a cheap Windows VPS stops being cheap, and they're the two lines most comparison pages leave out.

👉 [Start with the $26 Windows plan or size up on Vultr's full list](https://www.vultr.com/servers/windows?ref=9738262-9J)
