# akile review: is it reliable, which plan should you pick, and can you actually get a refund? (full plan table + the refund limits most reviews skip)

AkileCloud is a UK-registered host (AKILE LTD, London) that has been selling since 2023 on its own network, AS61112, and now claims 50+ nodes across 18 countries. Entry pricing sits around **¥14.99–¥30.82/mo (≈$2.23–$4.59)**, which is cheap enough that the real question is not whether you can afford to try it, but whether you can afford to depend on it. The catch that most write-ups skip: refunds go to **account balance only, never back to your card**, discounted and coupon orders are non-refundable outright, and the public notice channel is Chinese-language Telegram.

Below is what the plans actually cost, how the series differ, where the network falls apart for Chinese users, and what the incident history says about backups.

> **Quick pick.** Pick the cheapest monthly plan on the line you actually need: **JPHyper-Lite at ¥14.99/mo (≈$2.23)** if a fast Japan port for streaming is the goal, or **Light Server 1C-1G-20GB-200G at ¥30.82/mo (≈$4.59)** if you need one specific city. Want unmetered bandwidth instead of a traffic quota? The **Los Angeles 2C-1G-30GB-Unlimited at ¥38.45/mo (≈$5.73)** is the cheapest entry. Prices here were captured from a public plan listing and should be re-checked at checkout. 👉 [Check current AkileCloud plans and pricing](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## What AkileCloud actually is

AKILE LTD is a private company registered in London, operating since 2023, and it runs its own network under AS61112 rather than reselling someone else's racks. The product line is high-bandwidth cloud VPS with large traffic quotas and multi-gigabit ports, plus a slower "Light Server" tier on 5–30 Mbps links for Southeast Asia, the Middle East and South America. It advertises its own lines in Hong Kong, Japan, Taiwan, Singapore, the US, Germany, the UK, Italy and the Netherlands, and a single node usually carries both a metered plan and an unmetered shared-bandwidth plan.

Checkout takes Alipay, WeChat Pay, credit card and crypto. Support runs through email and Telegram. The control panel is built in-house, and LowEndTalk users noted it was swapped for a new one recently, which is worth knowing if you are following an older tutorial.

## Full plan table

The listing below covers every plan tier I could confirm from a public plan page. It is not a guaranteed complete catalogue: the source page was truncated after the Manila section, and other series (HK Lite, SG GSL, LAX Lite) appear in third-party aggregators with lower prices that I could not verify against a plan page, so they are left out rather than guessed at.

### Japan: JPHyper and JPBase

JPHyper is the fast-port series; JPBase trades port speed for lower prices and cheaper unmetered options.

| Plan | vCPU · RAM · Disk | Port / Monthly traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- |
| JPHyper-Lite | 1 · 1.5 GB · 10 GB | 2.5 Gbps / 1 TB | ¥14.99 ≈ $2.23 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Mini | 2 · 2 GB · 10 GB | 2.5 Gbps / 2.5 TB | ¥25.99 ≈ $3.87 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Starter | 2 · 2 GB · 10 GB | 2.5 Gbps / 5 TB | ¥49.99 ≈ $7.45 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Standard | 2 · 2 GB · 20 GB | 2.5 Gbps / 10 TB | ¥99.99 ≈ $14.91 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Pro | 2 · 4 GB · 20 GB | 2.5 Gbps / 30 TB | ¥289.99 ≈ $43.23 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-300M dedicated | 4 · 4 GB · 20 GB | 300 Mbps / unmetered | ¥599.99 ≈ $89.45 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-500M dedicated | 4 · 8 GB · 30 GB | 500 Mbps / unmetered | ¥999.99 ≈ $149.09 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-1000M dedicated | 8 · 16 GB · 50 GB | 1 Gbps / unmetered | ¥1899.99 ≈ $283.27 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-Mini | 1 · 0.5 GB · 5 GB | 1 Gbps / 1.5 TB | ¥19.99 ≈ $2.98 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-Lite | 1 · 1 GB · 10 GB | 2 Gbps / 3 TB | ¥35 ≈ $5.22 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-Standard | 1 · 2 GB · 10 GB | 2 Gbps / 6 TB | ¥70 ≈ $10.44 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-UNLIMITED-500M | 1 · 2 GB · 10 GB | 500 Mbps / unmetered | ¥235 ≈ $35.04 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-UNLIMITED-1000M | 1 · 3 GB · 20 GB | 1 Gbps / unmetered | ¥360 ≈ $53.67 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

### TWLite

| Plan | vCPU · RAM · Disk | Port / Monthly traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- |
| TWLite-Mini | 1 · 2 GB · 10 GB | 1 Gbps / 1.5 TB | ¥24.99 ≈ $3.73 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| TWLite-Starter | 1 · 2 GB · 10 GB | 2 Gbps / 3 TB | ¥43.74 ≈ $6.52 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| TWLite-Standard | 2 · 4 GB · 20 GB | 2 Gbps / 6 TB | ¥99.99 ≈ $14.91 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| TWLite-Pro | 2 · 4 GB · 20 GB | 2 Gbps / 18 TB | ¥237.49 ≈ $35.41 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

### Light Server (30 Mbps links)

The same eleven tiers and the same prices apply across London, Ho Chi Minh City, Tokyo, Singapore, Hong Kong, Seoul, Dubai, Mumbai and Manila. Los Angeles offers these plus three unmetered variants listed separately below.

| Plan | vCPU · RAM · Disk | Port / Monthly traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- |
| 1C-1G-20GB-200G | 1 · 1 GB · 20 GB | 30 Mbps / 200 GB | ¥30.82 ≈ $4.59 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 1C-1G-40GB-200G | 1 · 1 GB · 40 GB | 30 Mbps / 200 GB | ¥38.45 ≈ $5.73 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 1C-2G-40GB-400G | 1 · 2 GB · 40 GB | 30 Mbps / 400 GB | ¥51.98 ≈ $7.75 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 1C-1G-40GB-1024G | 1 · 1 GB · 40 GB | 30 Mbps / 1 TB | ¥51.98 ≈ $7.75 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 2C-2G-60GB-600G | 2 · 2 GB · 60 GB | 30 Mbps / 600 GB | ¥65.59 ≈ $9.78 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 1C-2G-40GB-1024G | 1 · 2 GB · 40 GB | 30 Mbps / 1 TB | ¥65.59 ≈ $9.78 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 2C-4G-80GB-800G | 2 · 4 GB · 80 GB | 30 Mbps / 800 GB | ¥78.05 ≈ $11.64 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 2C-2G-60GB-2048G | 2 · 2 GB · 60 GB | 30 Mbps / 2 TB | ¥81.43 ≈ $12.14 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 2C-4G-80GB-3072G | 2 · 4 GB · 80 GB | 30 Mbps / 3 TB | ¥99.88 ≈ $14.89 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 4C-4G-100GB-3072G | 4 · 4 GB · 100 GB | 30 Mbps / 3 TB | ¥208.90 ≈ $31.14 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 4C-8G-120GB-4096G | 4 · 8 GB · 120 GB | 30 Mbps / 4 TB | ¥254.12 ≈ $37.89 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

### Light Server, Los Angeles: unmetered additions

| Plan | vCPU · RAM · Disk | Port / Traffic | Price (monthly) | Order |
| --- | --- | --- | --- | --- |
| 2C-1G-30GB-Unlimited | 2 · 1 GB · 30 GB | 200 Mbps / unmetered | ¥38.45 ≈ $5.73 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 2C-2G-40GB-Unlimited | 2 · 2 GB · 40 GB | 200 Mbps / unmetered | ¥51.98 ≈ $7.75 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| 2C-4G-50GB-Unlimited | 2 · 4 GB · 50 GB | 200 Mbps / unmetered | ¥81.43 ≈ $12.14 | [ Check price](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

## Which series fits which job

The jump from ¥14.99 to ¥1899.99 is not a linear quality curve. It is four different products wearing the same brand.

**JPHyper** is the one to look at if port speed matters. 2.5 Gbps on a ¥14.99 plan is unusual, and the traffic allowances scale steeply: ¥99.99 buys 10 TB where the same money on Light Server buys 3 TB at 30 Mbps. If you are pulling large files or running a media proxy, this is the series where the money goes furthest.

**JPBase** sits underneath it with a 1–2 Gbps port and a genuinely cheap entry at ¥19.99 for 1.5 TB. The unmetered JPBase tiers (¥235 and ¥360) are the "I don't want to think about quotas" option, and they are far cheaper than the dedicated-port JPHyper unmetered plans at ¥599.99 and up.

**TWLite** is the smallest series: four plans, 1–2 Gbps, ¥24.99 to ¥237.49. Chinese review coverage of the TWlite line on Akile's sister brand Acck rated it 3.0/5 and described it as a pure "landing" box, meaning it exists to give you an IP in the region with DNS-based streaming unlock, not to run anything heavy.

**Light Server** is the geographic coverage play. 30 Mbps is a real ceiling. It is fine for a single 4K stream, a small site or a monitoring box, and painful for anything involving bulk transfer. You are paying ¥30.82 for the city, not for the bandwidth.

Two configuration limits apply across the board. Entry disks run 5–10 GB, and a VPSIUM review notes that the OS plus logs fills a 5 GB disk fast. The ¥19.99 JPBase-Mini, with 0.5 GB RAM and 5 GB of disk, is a toy for testing a route, not a server you put a database on.

## The refund rules most reviews skip

"AkileCloud offers refunds" is technically true and practically misleading. Here is the actual policy as published:

- **Refunds are credited to your account balance only.** You do not get money back on your card, Alipay or crypto wallet.
- **24-hour window, 5 GB traffic cap.** Full refund within 24 hours of provisioning, provided you have used no more than 5 GB.
- **Three machines per account per calendar month**, and **one machine per node per month**.
- **Discounted plans and anything bought with a coupon cannot be refunded at all.** Not partially, not to balance. Zero.
- **Setup fees, special configuration fees and leftover prepaid balance are never returned.**

There is an additional wrinkle worth knowing before you pay. A coupon-tracking site that reproduces the service agreement reports that the English-language version declines refund requests once service begins, while the Chinese agreement contains the 24-hour/5 GB balance provision. If the English terms are the ones that bind your order, the 24-hour window may not exist for you. Confirm with support before paying, and read the special-price acknowledgement that discounted plans require at checkout.

The practical consequence: **using a coupon is a one-way door.** You save some percentage up front and give up your only exit. On a ¥14.99 plan that is a fine trade. On a ¥1899.99 plan it is not. 👉 [Start with a monthly plan and keep the refund window open](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## Streaming unlock is DNS, not native IP

This is the distinction that decides whether AkileCloud works for you.

Multiple third-party sources describe the streaming unlock as DNS-based: the provider runs its own DNS service, and pointing your server at it makes Netflix and Disney+ resolve as if you were in the right region. A Chinese review site testing the LAX Hyper plan found that after switching DNS, the IP itself would not unlock natively. Hong Kong machines were reported as working out of the box for Netflix and Disney+, with enough bandwidth for everyday viewing and a light website.

What that means in practice:

- **Watching streaming through a browser or app that respects your DNS settings:** works, per multiple user reports.
- **Needing a clean native IP for account registration, banking, or anything that fingerprints the IP rather than the DNS resolver:** does not work, at least on the LAX Hyper plan tested.
- **Running a service where the client controls DNS:** the unlock does nothing.

If a seller promises "native IP" and the mechanism is DNS, those are different products. AkileCloud's own marketing leans on streaming unlock as a feature, and the third-party evidence supports DNS unlock specifically.

## China routing: mobile yes, telecom and Unicom maybe not

User reports on VPSIUM are consistent about the direction of travel. Mobile users report decent latency. Telecom and Unicom users report circuitous routing with latency reaching 300 ms+, and obvious packet loss at the evening peak, which makes it unsuitable for latency-sensitive work.

The budget annual plans illustrate the trade. A Chinese review of the UK BGP plan (¥127.99/year at the time of that review) recorded 9929 return routing on all three Chinese carriers, with 1 core, 512 MB RAM, 5 GB SSD and a 496 Mbps port. The LAX Hyper plan at ¥77.77/year had no China route optimisation at all, and the reviewer's only positive was DNS unlock. A JPPro promotional plan advertised three-carrier optimisation with IIJ for telecom and Unicom and CMI for mobile, but tested as CMI across all three.

Cheap does not mean "optimised for your carrier." Test on a monthly plan with your own connection before committing to a year. None of this is published as an SLA by the provider, so treat it as community observation, not a guarantee.

## Reliability and what the incident log says

LowEndTalk users in August 2025 reported good uptime and no hard failures, with rare locations at low prices as the main draw. The same thread lists the drawbacks plainly: sometimes the IP address changes at random, there is no rDNS, and service notifications appear only on a Chinese-language Telegram channel.

The official notice channel backs up the last point. Three recent entries:

- **A US core router replacement and cutover**, scheduled for a two-hour window at Beijing time, with all BGP sessions and uplinks fully disconnected and roughly 15 minutes of complete outage, followed by latency fluctuation during BGP reconvergence. LAX Hyper and other US nodes were affected.
- **A Singapore switch software upgrade** in a two-hour window with about 30 minutes of impact, including possible brief interruptions and session resets.
- **The molu2 node suffered physical damage.** The machine was rebuilt, **data on the node was lost**, affected customers received a 7-day service credit, and the IP address stayed the same. The rebuild was still in progress when the notice went out.
- **A Hong Kong core router fault** was resolved and service restored.

The molu2 entry is the one to plan around. A physical failure cost customers their data and was compensated with seven days of service time. That is a normal outcome for a budget host and an argument for keeping your own backups regardless of what any provider promises.

If you do not read Chinese, you will find out about maintenance after it happens, if at all. 👉 [Open a monthly plan and verify the route yourself first](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## Who should skip AkileCloud

Some requirements are disqualifying here, and no plan fixes them:

- **You need a native IP.** The unlock is DNS-based, and at least one tested plan would not unlock natively.
- **You need rDNS.** Multiple users report it is not available.
- **You need a stable IP for mail, allowlists or long-lived DNS records.** IPs have been reported to change without warning.
- **You run latency-sensitive traffic on telecom or Unicom.** Evening packet loss and 300 ms+ latency are reported, not hypothetical.
- **You need English-language notifications or documented support.** The public notice channel is Chinese-only.
- **You need storage.** 5–20 GB system disks on most plans rule out anything resembling a data-heavy application.

For those cases, look at providers with published SLAs, native IP options and English support. AkileCloud is not competing for that customer.

## FAQ

**Is AkileCloud a real company?**
It is operated by AKILE LTD, described as a private company registered in London, active since 2023, with its own network under AS61112. The domain registration runs to 2033.

**What payment methods work?**
Alipay, WeChat Pay, credit card and cryptocurrency.

**Can I get my money back?**
To account balance, within 24 hours of provisioning, if you have used 5 GB or less, subject to monthly limits of three machines per account and one per node. Discounted and coupon orders are excluded entirely. The English version of the agreement reportedly declines refunds once service begins, so confirm before paying.

**Does it unlock Netflix and Disney+?**
User reports say Hong Kong machines work out of the box for both, via DNS unlock. That is not the same as a native IP, and one tested US plan would not unlock natively even after changing DNS.

**Is there an annual discount?**
Third-party reviews mention annual promotional plans and describe annual pricing as aggressive, but no current annual price list was verifiable for this article. Treat annual pricing as something to confirm on the order page, not a fixed number.

**Can I host a website on it?**
A light site, yes. Entry disks of 5–10 GB and 0.5–1 GB RAM on the cheapest plans limit you quickly, and there is no rDNS. Keep backups off the machine.

**Is support in English?**
Email and Telegram contact exist. The public notice channel, `akile_notice`, posts in Chinese only, which is the practical constraint for non-Chinese buyers.

## How to decide

Three rules cover most readers:

**Testing whether the route works for your carrier:** take the cheapest monthly plan on the relevant series, JPHyper-Lite at ¥14.99 (≈$2.23) for Japan or any Light Server 1C-1G-200G at ¥30.82 (≈$4.59) for a specific city, and do not touch a coupon. You are buying information, and the 24-hour refund window stays open.

**Streaming and bulk transfer:** JPHyper is the series that pays. ¥99.99 (≈$14.91) for 10 TB at 2.5 Gbps is the value point, and ¥49.99 for 5 TB is enough for most households.

**Unmetered bandwidth without a big budget:** the Los Angeles 2C-1G-30GB-Unlimited at ¥38.45 (≈$5.73), accepting 200 Mbps and no China optimisation.

Before you pay, confirm three things on the order page: the price as it stands today, whether a coupon is applied (which voids the refund), and that you are comfortable with balance-only refunds. 👉 [Compare the current AkileCloud plan list and pick a monthly tier](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)
