# AI & SaaS tool pricing dataset (October 2026)

**257 AI and SaaS tools: free plan, trial length, cheapest paid plan, student/education pricing and refund rule, read from each vendor's official pricing, help and terms pages, with the date of each record.**

Maintained by [Kuponaut](https://kuponaut.com/), an English/Turkish site that documents AI-tool pricing and the discounts vendors actually offer. This repository is the open-data mirror of the tables on [kuponaut.com/ai-tool-price-index](https://kuponaut.com/ai-tool-price-index/), [ai-tools-with-free-plans](https://kuponaut.com/ai-tools-with-free-plans/), [ai-tools-free-trials](https://kuponaut.com/ai-tools-free-trials/) and [ai-tools-student-discounts](https://kuponaut.com/ai-tools-student-discounts/).

- Edition: **October 2026** (compiled 2026-10-15); each row also carries the date its record was last checked.
- 112 tools have a free plan, 67 state a trial length, 23 have an official student or education price.
- Files: [`ai-tool-pricing.csv`](ai-tool-pricing.csv) and [`ai-tool-pricing.json`](ai-tool-pricing.json).
- License: [CC BY 4.0](LICENSE). Reuse freely; credit "Kuponaut (kuponaut.com)".

## What is (and is not) in here

Every field was read from the vendor's own pages. When a page does not state something, the field says `unknown` or is empty rather than guessing. Prices change often: the `kuponaut_url` column leads to the dated record with the official source link for that tool.

This repository contains **no promo codes and no affiliate links**. The links below go to plain Kuponaut pages. Kuponaut itself is funded by affiliate commissions on some of the tools it covers; that is disclosed on every page there, and it does not affect which tools appear in this dataset.

## Fields

| Field | Meaning |
|---|---|
| `free_plan` | `yes` / `no` / `unknown`: a permanent free tier, not a trial |
| `free_limits` | What the free tier includes, as stated by the vendor |
| `trial_days` | Free-trial length in days, when stated |
| `trial_card_required` | Whether the trial asks for a card (`yes` / `no` / `unknown`) |
| `cheapest_amount`, `currency`, `period`, `plan` | Cheapest paid plan on the public pricing page |
| `yearly_note` | What the vendor says about annual billing |
| `student_discount`, `student_note` | Official student / education / non-profit pricing, if any |
| `refund` | Refund or money-back rule, when stated |
| `record_updated` | Date the Kuponaut record was last checked |

## Tables by category

### Builders & Websites

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [1ClickWebsite.ai](https://kuponaut.com/1clickwebsite-discount-code/) | Not stated | – | 49 USD/month (Starter) | Not stated | 2026-10-19 |
| [Appy Pie](https://kuponaut.com/appy-pie-discount-code/) | Not stated | 7 days, no card | 16 USD/month (Basic (per app)) | Yes: Students with .edu email get a special discount on yearly plans | 2026-10-15 |
| [Base44](https://kuponaut.com/base44-discount-code/) | Yes: 25 message credits a month (up to 5 a day), 100 integration credits, up to 5 apps | – | 20 USD/month (Starter) | Yes: 50% off Starter or Builder for students, teachers and staff (first paid subscription) | 2026-10-25 |
| [BasePrice](https://kuponaut.com/baseprice-discount-code/) | Yes: 1 project, 2 products, PPP and exchange-rate pricing; no card | – | 9 USD/month (Start) | Not stated | 2026-10-19 |
| [ChatAndBuild](https://kuponaut.com/chatandbuild-discount-code/) | Not stated | – | not stated | Not stated | 2026-09-20 |
| [ClickFunnels](https://kuponaut.com/clickfunnels-discount-code/) | Not stated | 14 days | not stated | Not stated | 2026-09-23 |
| [Create](https://kuponaut.com/create-net-discount-code/) | Not stated | – | 9.99 USD/month (Portfolio) | Not stated | 2026-10-15 |
| [Decktopus](https://kuponaut.com/decktopus-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [Gamma](https://kuponaut.com/gamma-discount-code/) | Yes: Up to 10 slides per prompt, Gamma branding; PDF/PPTX/PNG export | – | not stated | Not stated | 2026-10-19 |
| [Lovable](https://kuponaut.com/lovable-discount-code/) | Yes: Limited daily messages | – | 25 USD/month (Pro) | Not stated | 2026-10-25 |
| [MeDo](https://kuponaut.com/medo-discount-code/) | Yes: No subscription credits; daily login bonus 80 credits, up to 400/month | – | 20 USD/month (Pro) | Not stated | 2026-10-19 |
| [Mixo](https://kuponaut.com/mixo-discount-code/) | Yes: One branded single-page site on a Mixo subdomain | – | 20 USD/month (Business) | Not stated | 2026-10-25 |
| [Plugins for WordPress](https://kuponaut.com/plugins-for-wp-discount-code/) | Not stated | – | 59 USD/year (In-Depth Malware Scanner Pro) | Not stated | 2026-10-11 |
| [Shopify](https://kuponaut.com/shopify-discount-code/) | No | 3 days, no card | 39 USD/month (Basic) | No | 2026-10-14 |
| [Suitcase Designs](https://kuponaut.com/suitcase-designs-discount-code/) | Not stated | – | 1990 USD/year (Beginner) | Not stated | 2026-10-19 |
| [Weblium](https://kuponaut.com/weblium-discount-code/) | Yes: Up to 3 pages, 100 MB storage/bandwidth, subdomain, branding, not indexed; pricing page shows '60 days' under Free (23 Oct 2026, unexplained) | 14 days | 16 USD/month (Starter) | Not stated | 2026-10-23 |
| [Wegic](https://kuponaut.com/wegic-discount-code/) | Not stated | – | 39.9 USD/month (Starter) | Not stated | 2026-10-23 |

### Business & Legal

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [BusinessAnywhere](https://kuponaut.com/business-anywhere-discount-code/) | Not stated | – | 25 USD/month (Virtual mailbox Basic) | Not stated | 2026-09-22 |
| [Markavo](https://kuponaut.com/markavo-discount-code/) | Not stated | – | 99 USD/one-time (Basic (per application, plus government fees)) | Not stated | 2026-09-21 |
| [QuoteIQ](https://kuponaut.com/quoteiq-discount-code/) | Not stated | 14 days, card | 29.99 USD/month (Essentials) | Not stated | 2026-10-19 |

### Career & Research

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [AI Expert Academy](https://kuponaut.com/ai-expert-academy-discount-code/) | Not stated | – | 799 USD/year (Team) | Not stated | 2026-10-15 |
| [Blue Collar Nerd](https://kuponaut.com/blue-collar-nerd-discount-code/) | Not stated | – | 197 USD/month (Team membership) | Not stated | 2026-10-19 |
| [CastMeNow](https://kuponaut.com/castmenow-discount-code/) | Not stated | 7 days, no card | 12 USD/month (Basic) | Not stated | 2026-10-19 |
| [Jibreel](https://kuponaut.com/jibreel-discount-code/) | No | 3 days | 4.25 GBP/month (Subscription) | Not stated | 2026-09-27 |
| [Learnology AI](https://kuponaut.com/learnology-ai-discount-code/) | Not stated | – | 5 USD/month (Co-ops & Groups (per user)) | Not stated | 2026-10-19 |
| [Litmaps](https://kuponaut.com/litmaps-discount-code/) | Yes: Small maps only; unlimited maps and monitoring need Pro | – | not stated | Not stated | 2026-08-27 |
| [Maven Analytics](https://kuponaut.com/maven-analytics-discount-code/) | Yes: Starter: learning plan, assessments, portfolio, badges, live workshops; no card | – | 34 USD/month (Pro) | Not stated | 2026-10-19 |
| [Rezi](https://kuponaut.com/rezi-discount-code/) | Yes: Build and ATS-score resumes; AI credits, unlimited resumes, PDF/DOCX export are paid | – | not stated | Not stated | 2026-08-27 |
| [SciSummary](https://kuponaut.com/scisummary-discount-code/) | Yes: Free monthly word allowance | – | not stated | Not stated | 2026-08-27 |
| [TopDecile](https://kuponaut.com/topdecile-discount-code/) | Not stated | 5 days | 65 GBP/3 months (Core (3 months)) | Not stated | 2026-10-19 |
| [Yomu AI](https://kuponaut.com/yomu-ai-discount-code/) | Not stated | – | 21 USD/month (Pro) | Not stated | 2026-10-19 |

### Chatbots & Support

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Chatbase](https://kuponaut.com/chatbase-discount-code/) | Yes: Limited message credits | – | 40 USD/month (Entry paid plan (unnamed)) | Not stated | 2026-08-31 |
| [Chatfuel](https://kuponaut.com/chatfuel-discount-code/) | Not stated | – | 20 USD/month (Business) | Not stated | 2026-10-19 |
| [Stammer AI](https://kuponaut.com/stammer-ai-discount-code/) | Not stated | – | 197 USD/month (Lowest agency plan) | Not stated | 2026-08-31 |

### Data & Analysis

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Dumpling AI](https://kuponaut.com/dumpling-ai-discount-code/) | Not stated | – | 49 USD/month (Starter) | Not stated | 2026-10-19 |
| [Insightful Pipe](https://kuponaut.com/insightful-pipe-discount-code/) | Not stated | – | 29.99 USD/month (Starter (8 connections)) | Not stated | 2026-10-19 |
| [Julius AI](https://kuponaut.com/julius-ai-discount-code/) | Yes: Free plan with daily credits; exact daily allowance not confirmed | – | 20 USD/month (Plus) | Not stated | 2026-10-19 |
| [Retailed](https://kuponaut.com/retailed-discount-code/) | Not stated | – | 49 USD/month (Premium (API)) | Not stated | 2026-10-19 |

### Design & Photo

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [123RF](https://kuponaut.com/123rf-discount-code/) | Yes: Free account: personal, non-commercial images and some AI tools | 7 days | 16.1 USD/month (PLUS Team (from, per seat)) | Not stated | 2026-10-24 |
| [Aragon AI](https://kuponaut.com/aragon-ai-discount-code/) | Not stated | – | 35 USD/one-time (Basic) | Not stated | 2026-10-19 |
| [ArtSmart AI](https://kuponaut.com/artsmart-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [Clarity AI (image upscaler)](https://kuponaut.com/clarity-ai-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-19 |
| [HeadshotPro](https://kuponaut.com/headshotpro-discount-code/) | Not stated | – | 29 USD/one-time (Basic) | Not stated | 2026-08-17 |
| [Photoroom](https://kuponaut.com/photoroom-discount-code/) | Yes: Limited features; personal, non-commercial use only | – | not stated | Not stated | 2026-10-19 |
| [Piktochart](https://kuponaut.com/piktochart-discount-code/) | Yes: 2 PNG downloads in total, 60 AI credits, 1 GB storage | – | 15 USD/month (Pro (per member)) | Yes: Education $39.99/member/year with a school email | 2026-10-19 |
| [Pixlr](https://kuponaut.com/pixlr-discount-code/) | Yes: Free in browser, no account; ads, limited saves, small batch of free AI credits | – | 2.49 USD/month (Plus) | Yes: Pixlr for Education free; school staff must apply with school email | 2026-10-14 |
| [Reel Unlimited](https://kuponaut.com/reel-unlimited-discount-code/) | Not stated | – | 895 USD/month (Graphics & Video) | Not stated | 2026-09-21 |
| [Rewarx Studio AI](https://kuponaut.com/rewarx-discount-code/) | Yes: 10 AI product photo credits, main generators and 4K export, no card | – | 29.9 USD/month (Starter) | Not stated | 2026-09-21 |
| [Sketch To Image](https://kuponaut.com/sketch-to-image-discount-code/) | Not stated | – | 20 USD/month (Standard (220 credits)) | Not stated | 2026-10-19 |
| [TinderProfile.ai](https://kuponaut.com/tinderprofile-ai-discount-code/) | Not stated | – | 14 USD/one-time (Like) | Not stated | 2026-10-19 |
| [Zoviz](https://kuponaut.com/zoviz-discount-code/) | Not stated | – | 29 USD/month (Starter) | Not stated | 2026-09-22 |

### E-commerce & Print on Demand

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [AnyListingSEO](https://kuponaut.com/anylistingseo-discount-code/) | Not stated | – | 79.95 USD/one-time (Emergency Boost / Holidays and Events Boost (per listing)) | Not stated | 2026-09-22 |
| [eDojo](https://kuponaut.com/edojo-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-19 |
| [Oink for Influencers](https://kuponaut.com/oink-discount-code/) | Yes: Free forever: storefront cross-check, earnings tracking, untagged-video check, 1 media kit | – | 29.99 USD/month (Pro) | Not stated | 2026-10-19 |
| [PODspy](https://kuponaut.com/podspy-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-19 |
| [ShopChief](https://kuponaut.com/shopchief-discount-code/) | Yes: 1,500 non-expiring sign-up credits, no card | – | 19 USD/month (Starter) | Not stated | 2026-10-19 |
| [Tickvio](https://kuponaut.com/tickvio-discount-code/) | Yes: Up to 20,000 timer views/month, web timers, no credit card | – | 7 USD/month (Entry paid plan (name not stated)) | Not stated | 2026-10-19 |
| [Vendoo](https://kuponaut.com/vendoo-discount-code/) | Not stated | 14 days | 14.99 USD/month (Starter) | Not stated | 2026-10-19 |

### Finance & Investing

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Bench](https://kuponaut.com/bench-discount-code/) | Not stated | – | 199 USD/month (Bookkeeping Light) | Not stated | 2026-10-19 |
| [DealCheck](https://kuponaut.com/dealcheck-discount-code/) | Yes: Starter: up to 15 saved properties | 14 days | 14 USD/month (Plus) | Not stated | 2026-10-19 |
| [Funded Futures Network](https://kuponaut.com/funded-futures-network-discount-code/) | Not stated | – | 149 USD/one-time ($25,000 account evaluation) | Not stated | 2026-09-24 |
| [Godel Terminal](https://kuponaut.com/godel-terminal-discount-code/) | Not stated | 14 days | 118 USD/month (Standard plan (name not stated)) | Not stated | 2026-10-19 |

### Fleet & Logistics

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [OneWayBIT](https://kuponaut.com/onewaybit-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-19 |

### Games, Makers & Hobbies

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Handle (Bridge128)](https://kuponaut.com/handle-bridge-discount-code/) | No | 30 days | not stated | Not stated | 2026-10-19 |
| [Printago](https://kuponaut.com/printago-discount-code/) | Yes: First production slot free: 5 GB storage, cloud slicing, community support | 14 days, no card | 3.67 USD/month (Commercial (per slot)) | Not stated | 2026-10-19 |

### Health & Wellness Software

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Auralink Pro](https://kuponaut.com/auralink-discount-code/) | Not stated | 30 days, no card | 29 USD/month (Auralink Pro) | Not stated | 2026-10-19 |
| [Constance](https://kuponaut.com/constance-discount-code/) | Not stated | – | 26.99 USD/month (Monthly subscription (App Store)) | Not stated | 2026-10-11 |

### Marketing & Listings

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [AI Just Better](https://kuponaut.com/ai-just-better-discount-code/) | Yes: Free listing via the normal manual review queue | – | 4.9 USD/one-time (Fastpass Listing) | Not stated | 2026-10-19 |
| [LeadCalculators](https://kuponaut.com/leadcalculators-discount-code/) | Yes: Basic free forever; limits not stated | – | 37 USD/month (Essentials) | Not stated | 2026-10-19 |
| [Omnisend](https://kuponaut.com/omnisend-discount-code/) | Yes: 500 emails a month, 250 contacts; no card | – | 16 USD/month (Standard (251-500 contacts)) | Not stated | 2026-10-14 |

### Other tools

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [1of10](https://kuponaut.com/1of10-discount-code/) | Yes: 60 credits/month, limited research results, no card | – | 19 USD/month (Basic) | Not stated | 2026-10-08 |
| [Actorio](https://kuponaut.com/actorio-discount-code/) | Not stated | 14 days | 79 EUR/month (Starter) | Not stated | 2026-10-19 |
| [Akool](https://kuponaut.com/akool-discount-code/) | Yes: Full-screen watermark, 720p, avatar videos up to 10 minutes | – | 12 USD/month (Starter (per seat)) | Not stated | 2026-10-08 |
| [Autoclips](https://kuponaut.com/autoclips-discount-code/) | Not stated | – | 29 USD/month (Essential) | Not stated | 2026-10-19 |
| [Avarup](https://kuponaut.com/avarup-discount-code/) | Not stated | 7 days | not stated | Not stated | 2026-10-13 |
| [BigIdeasDB](https://kuponaut.com/bigideasdb-discount-code/) | Not stated | – | 49 USD/month (Pro) | Not stated | 2026-10-08 |
| [BoldSign](https://kuponaut.com/boldsign-discount-code/) | Yes: Essential plan: 25 envelopes a month | 30 days, no card | 15 USD/month (Growth (per user)) | Not stated | 2026-10-09 |
| [BounceBan](https://kuponaut.com/bounceban-discount-code/) | Yes: Single verifications free and unlimited in Free Mode; bulk needs paid credits | – | not stated | Not stated | 2026-10-08 |
| [CaptionX](https://kuponaut.com/caption-x-discount-code/) | Yes: 5 captions, 5 silence removals, 3 profanity-filter, 2 eye-contact uses; no card | – | 13.95 USD/month (Pro) | Not stated | 2026-10-26 |
| [Circleboom](https://kuponaut.com/circleboom-discount-code/) | Yes: Limited free tier on Circleboom Twitter only; Circleboom Publish is paid | 90 days | 29.99 USD/month (Publish Pro) | Not stated | 2026-10-09 |
| [Collov AI](https://kuponaut.com/collov-ai-discount-code/) | No | – | 27 USD/month (Standard (60 photo credits)) | Not stated | 2026-10-09 |
| [DataFeedWatch](https://kuponaut.com/datafeedwatch-discount-code/) | Not stated | 15 days | 64 USD/month (Shop) | Not stated | 2026-10-08 |
| [Devi AI](https://kuponaut.com/devi-ai-discount-code/) | Not stated | 10 days | 49 USD/month (Facebook Groups Monitoring) | Not stated | 2026-10-08 |
| [Dreamwave](https://kuponaut.com/dreamwave-discount-code/) | Yes: Free AI headshot generator with limited daily spots; main packages paid | – | 35 USD/one-time (Starter (40 photos)) | Not stated | 2026-10-09 |
| [DSQR Studio](https://kuponaut.com/dsqr-studio-discount-code/) | Not stated | – | 473 USD/month (Graphic Design) | Not stated | 2026-10-19 |
| [GimmeFeedback](https://kuponaut.com/gimmefeedback-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-19 |
| [HomeDesigns AI](https://kuponaut.com/homedesigns-ai-discount-code/) | Yes: 3 free credits refill every 24 hours without a plan | – | 369 TRY/month (Standard (100 credits/month)) | Not stated | 2026-10-09 |
| [Innertune](https://kuponaut.com/innertune-discount-code/) | Not stated | 3 days | 19.99 USD/month (Premium) | Not stated | 2026-10-13 |
| [LearningStudioAI](https://kuponaut.com/learningstudioai-discount-code/) | Not stated | – | 39 USD/month (Starter) | Not stated | 2026-10-08 |
| [LinkMatch](https://kuponaut.com/linkmatch-discount-code/) | Not stated | 14 days, no card | 15.99 EUR/month (Standard (per user)) | Not stated | 2026-10-08 |
| [Loudly](https://kuponaut.com/loudly-discount-code/) | Yes: Most features, daily generation allowance, tracks limited to 30 seconds | – | not stated | Not stated | 2026-10-09 |
| [Magai](https://kuponaut.com/magai-discount-code/) | No | – | 20 USD/month (Standard) | Not stated | 2026-10-09 |
| [Markifact](https://kuponaut.com/markifact-discount-code/) | Not stated | – | 79 USD/month (Pro (1 seat)) | Not stated | 2026-10-08 |
| [Mureka](https://kuponaut.com/mureka-discount-code/) | Yes: 4 songs a day with the free model | – | 10 USD/month (Pro) | Not stated | 2026-10-08 |
| [Musicfy](https://kuponaut.com/musicfy-discount-code/) | Yes: Free-tier limits not stated; start free without a card | – | 8 USD/month (Starter) | Not stated | 2026-10-09 |
| [Mystrika](https://kuponaut.com/mystrika-discount-code/) | Yes: Free Forever plan, no credit card; limits not stated | – | not stated | Not stated | 2026-10-13 |
| [Narration Box](https://kuponaut.com/narration-box-discount-code/) | Yes: 1,000 words, one voice clone, watermarked exports | – | 15 USD/month (Plus (20,000 words)) | Not stated | 2026-10-09 |
| [Niceboard](https://kuponaut.com/niceboard-discount-code/) | No | 7 days | 399 USD/month (Core) | Not stated | 2026-10-08 |
| [No Code MBA](https://kuponaut.com/nocode-mba-discount-code/) | Not stated | – | 29.99 USD/month (Membership) | Not stated | 2026-10-08 |
| [OnlySocial](https://kuponaut.com/onlysocial-discount-code/) | Not stated | – | 29 USD/month (Freelancer) | Not stated | 2026-10-13 |
| [Packsia](https://kuponaut.com/packsia-discount-code/) | Yes: AI-only $0 plan; downloading stock clips needs Membership or Campaign Pass | – | 39 USD/month (Membership) | Not stated | 2026-10-08 |
| [Palette](https://kuponaut.com/palette-fm-discount-code/) | Yes: Unlimited watermarked previews up to 500×500 px + 1 full-resolution credit | – | 6 USD/month (Subscription (480 credits/year)) | Not stated | 2026-10-08 |
| [PhotoPacks AI](https://kuponaut.com/photopacks-ai-discount-code/) | Not stated | – | 24 USD/one-time (Headshot package (40+ headshots)) | Not stated | 2026-10-09 |
| [PostingCat](https://kuponaut.com/postingcat-discount-code/) | Yes: 2 channels, 10 scheduled posts per channel; no card needed | – | 12.49 USD/month (Professional) | Not stated | 2026-10-08 |
| [Quickchat AI](https://kuponaut.com/quickchat-ai-discount-code/) | Yes: Personal, non-commercial use; 50 AI credits/month; no card | – | 9 USD/month (Starter) | Not stated | 2026-10-09 |
| [Rasayel](https://kuponaut.com/rasayel-discount-code/) | Not stated | 7 days, no card | 30 USD/month (Start (per user, min. 5 users)) | Not stated | 2026-10-08 |
| [RB2B](https://kuponaut.com/rb2b-discount-code/) | Yes: Forever Free: company-level identification, 150 resolutions a month | 7 days, no card | 79 USD/month (Starter (300 resolutions, no emails)) | Not stated | 2026-10-09 |
| [Real Fake Photos](https://kuponaut.com/real-fake-photos-discount-code/) | No | – | 9.99 EUR/one-time (1 style (40 headshots)) | Not stated | 2026-10-08 |
| [SalesBlink](https://kuponaut.com/salesblink-discount-code/) | Not stated | 14 days, no card | 29 USD/month (Starter) | Not stated | 2026-10-13 |
| [Secure Privacy](https://kuponaut.com/secure-privacy-discount-code/) | Yes: Free plan per domain; limits not stated | 30 days | 15 USD/month (Small (per domain)) | Not stated | 2026-10-13 |
| [SEO Scout](https://kuponaut.com/seo-scout-discount-code/) | Not stated | 7 days | 49 USD/month (Starter) | Not stated | 2026-10-08 |
| [SEOWRITEE](https://kuponaut.com/seowritee-discount-code/) | Yes: FREE plan: 3 SEO analyses a month, no card | – | 189 CZK/month (HEAVY) | Not stated | 2026-10-08 |
| [Setmore](https://kuponaut.com/setmore-discount-code/) | Yes: Free for up to 4 users | – | not stated | Not stated | 2026-10-13 |
| [Shaka Guide](https://kuponaut.com/shaka-guide-discount-code/) | Not stated | – | 6.99 USD/one-time (Individual tour (from)) | Not stated | 2026-10-08 |
| [SJinn](https://kuponaut.com/sjinn-discount-code/) | Not stated | – | 12 USD/month (Standard (20,000 credits)) | Not stated | 2026-10-08 |
| [StrataScratch](https://kuponaut.com/stratascratch-discount-code/) | Yes: 50 AI credits/month, 75+ questions; AI mock interviews and solutions paid | – | 24 USD/month (Premium) | Yes: Students and educators get up to 20% off Premium | 2026-10-09 |
| [Supermeme.ai](https://kuponaut.com/supermeme-ai-discount-code/) | Yes: 10 credits a month, watermark, no credit card | – | 9.99 USD/month (Solo) | Not stated | 2026-10-19 |
| [Swell AI](https://kuponaut.com/swell-ai-discount-code/) | Yes: Hobby plan $0 with 1 upload | – | 29 USD/month (Studio (300 minutes)) | Not stated | 2026-10-08 |
| [Trackify](https://kuponaut.com/trackify-discount-code/) | Not stated | 30 days | 99 unknown/month (Premium (per truck)) | Not stated | 2026-10-08 |
| [Typedesk](https://kuponaut.com/typedesk-discount-code/) | Yes: 1 user, unlimited templates, 50 uses a week | – | 5 USD/month (Premium (per user)) | Not stated | 2026-10-08 |
| [Uplisting](https://kuponaut.com/uplisting-discount-code/) | Not stated | 14 days, no card | 40 GBP/month (Independent Host (up to 4 properties)) | Not stated | 2026-10-08 |
| [Uploadcare](https://kuponaut.com/uploadcare-discount-code/) | Yes: 1,000 operations/month, personal use | – | 66 USD/month (Pro (5,000 operations, 3 seats)) | Not stated | 2026-10-08 |
| [UX Pilot](https://kuponaut.com/ux-pilot-discount-code/) | Yes: 80 credits a day, free forever, no card | – | 29 USD/month (Pro (750 credits/month)) | Not stated | 2026-10-09 |
| [Vapi](https://kuponaut.com/vapi-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-09 |
| [WebsitePolicies](https://kuponaut.com/websitepolicies-discount-code/) | Yes: Basic free: one policy | – | 59 USD/year (Starter) | Not stated | 2026-10-13 |
| [Winning Hunter](https://kuponaut.com/winning-hunter-discount-code/) | No | – | 49 USD/month (Basic) | Not stated | 2026-10-09 |
| [Wisesheets](https://kuponaut.com/wisesheets-discount-code/) | No | – | 60 USD/year (Pro) | Not stated | 2026-10-09 |
| [Wispform](https://kuponaut.com/wispform-discount-code/) | Yes: Unlimited forms, 10 questions each, 100 responses a month | – | 8 USD/month (Essential) | Not stated | 2026-10-08 |
| [WordCrafter](https://kuponaut.com/wordcrafter-discount-code/) | Not stated | 14 days, card | 29 USD/month (Pro) | Not stated | 2026-10-19 |
| [WorkBeaver](https://kuponaut.com/workbeaver-discount-code/) | Yes: Free starter with 500 credits | – | 21.95 USD/month (Essentials) | Not stated | 2026-10-13 |
| [Ycode](https://kuponaut.com/ycode-discount-code/) | Yes: Self-hosting free; a free Cloud project tier is available | – | 30 USD/month (Ycode Cloud (per project)) | Not stated | 2026-10-13 |
| [zcal](https://kuponaut.com/zcal-discount-code/) | Yes: Free Forever: unlimited links and calendars | – | not stated | Not stated | 2026-10-08 |

### PDF & Documents

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [DocHub](https://kuponaut.com/dochub-discount-code/) | Yes: Core actions (edit, sign, sign requests) about 3 times a month; 3 folders | 30 days, card | 8 EUR/month (Basic) | Yes: Schools: academic site licences or 20% off; nonprofits 20% off | 2026-10-16 |
| [eSign: Sign PDF DOCX Documents](https://kuponaut.com/esign-app-discount-code/) | Not stated | – | 10.99 USD/month (Monthly subscription) | Not stated | 2026-09-21 |
| [PDF Reader Pro](https://kuponaut.com/pdf-reader-pro-discount-code/) | Yes: Free download covers basic reading; editing, OCR and AI tools paid | – | 79.99 USD/year (Advanced) | Not stated | 2026-08-18 |
| [PDFelement](https://kuponaut.com/pdfelement-discount-code/) | Not stated | 14 days, no card | 51.99 USD/one-time (Perpetual PDFelement 13 (single platform)) | Yes: Up to 63% off for verified students via Student Beans | 2026-10-14 |

### Photo & Print

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Persnickety Box](https://kuponaut.com/persnickety-box-discount-code/) | Not stated | – | 19.99 USD/month (Monthly box (30 prints)) | Not stated | 2026-10-19 |

### Productivity & AI Agents

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [AI Flow Chat](https://kuponaut.com/ai-flow-chat-discount-code/) | No | 7 days | 29 USD/month (Basic) | Not stated | 2026-10-19 |
| [BetterDay AI](https://kuponaut.com/betterday-ai-discount-code/) | Not stated | – | not stated | Not stated | 2026-09-23 |
| [BizzBox.ai](https://kuponaut.com/bizzbox-discount-code/) | Not stated | 14 days | 39 GBP/unknown (Entry plan (per user)) | Not stated | 2026-10-24 |
| [Cal.com](https://kuponaut.com/cal-com-discount-code/) | Yes: Individual plan free forever; teams, routing forms paid | – | not stated | Not stated | 2026-08-18 |
| [EdrawMind](https://kuponaut.com/edrawmind-discount-code/) | Yes: 100 topics, 7 themes, 500 AI tokens, 100 MB cloud; watermarked exports | – | 39 USD/6 months (Semi-annual) | Yes: Education: $49/yr, $35 semi-annual, $7.95/mo with student verification | 2026-10-14 |
| [Fireflies.ai](https://kuponaut.com/fireflies-ai-discount-code/) | Yes: Limited AI summaries, 400 minutes of storage per team | – | 18 USD/month (Pro) | Not stated | 2026-09-23 |
| [Fyxer AI](https://kuponaut.com/fyxer-ai-discount-code/) | Yes: 400 credits a month | 14 days | 49 USD/month (Pro) | No | 2026-10-25 |
| [Lindy](https://kuponaut.com/lindy-discount-code/) | Yes: Monthly credit allowance | – | 50 USD/month (Pro) | Not stated | 2026-08-31 |
| [Locus Founder](https://kuponaut.com/locus-founder-discount-code/) | Not stated | – | 25 USD/month (Founder) | Not stated | 2026-10-19 |
| [Mailbutler](https://kuponaut.com/mailbutler-discount-code/) | Not stated | 14 days, no card | 4 USD/month (Starter (listed as "$0 / $4")) | Not stated | 2026-10-19 |
| [Maniana AI](https://kuponaut.com/maniana-ai-discount-code/) | Yes: $0 plan, no card: collaborative workspaces, version history, email support (beta) | – | 20 USD/month (Starter) | Not stated | 2026-09-21 |
| [MaxAI](https://kuponaut.com/maxai-discount-code/) | Yes: Free plan; limits not stated | – | 30 USD/month (Pro) | Not stated | 2026-10-19 |
| [Motion](https://kuponaut.com/motion-discount-code/) | Not stated | 7 days | 19 USD/month (Pro AI) | Not stated | 2026-08-31 |
| [Poppy AI](https://kuponaut.com/poppy-ai-discount-code/) | No | – | 99 USD/month (Entry plan (unnamed, ~$99+)) | Not stated | 2026-10-25 |
| [Relevance AI](https://kuponaut.com/relevance-ai-discount-code/) | Yes: Monthly free credit allowance | – | not stated | Not stated | 2026-08-27 |
| [Scribe Mail](https://kuponaut.com/scribe-mail-discount-code/) | Yes: Up to 2 users; templates, social icons, brand library; Scribe watermark stays | 14 days, no card | 68 USD/month (Business (30 users)) | Not stated | 2026-10-19 |
| [Snagit](https://kuponaut.com/snagit-discount-code/) | Not stated | 15 days | 39 USD/year (Individual) | Yes: Students $19.99/yr; educators, military, charity 30% off (US/UK/CA) | 2026-10-15 |
| [Synthflow AI](https://kuponaut.com/synthflow-discount-code/) | Not stated | – | 29 USD/month (Entry plan) | Not stated | 2026-08-31 |
| [tabExtend](https://kuponaut.com/tabextend-discount-code/) | Yes: Up to 30 saves with no time limit (labelled a free trial) | – | 8 USD/month (Pro) | Yes: Students and teachers contact tabExtend; no percentage stated | 2026-10-19 |
| [Taskade](https://kuponaut.com/taskade-discount-code/) | Yes: Up to 3 live apps, 10 automation runs a month, 2 people | – | 20 USD/month (Pro) | No | 2026-10-22 |
| [Teable](https://kuponaut.com/teable-discount-code/) | Yes: 1,000 rows/space, 1 GB attachments, 100 automation runs, 200 AI credits a month | – | 24 USD/month (Pro (per seat)) | Not stated | 2026-10-19 |
| [Wispr Flow](https://kuponaut.com/wispr-flow-discount-code/) | Yes: Weekly word limit, full feature set | – | 15 USD/month (Pro) | Yes: Verified students: Pro $6/mo billed annually (50% off) + 3 months free | 2026-10-19 |

### Sales & Outreach

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Artisan](https://kuponaut.com/artisan-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-25 |
| [High iQ](https://kuponaut.com/high-iq-discount-code/) | Yes: Free account to test the platform, no card | – | 2000 USD/month (Team (10 licenses, 6-month agreement)) | Not stated | 2026-10-19 |
| [Inbox](https://kuponaut.com/inbox-app-discount-code/) | No | 7 days | 29 USD/month (Basic) | Not stated | 2026-10-19 |
| [SelfCRM](https://kuponaut.com/selfcrm-discount-code/) | Not stated | – | 49999 INR/one-time (Starter) | Not stated | 2026-10-13 |
| [Sendblue](https://kuponaut.com/sendblue-discount-code/) | Yes: Free Sandbox test environment, up to 10 verified contacts, inbound-first | – | 100 USD/month (AI Agent (per line)) | Not stated | 2026-10-19 |
| [UpLead](https://kuponaut.com/uplead-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [ZipISA](https://kuponaut.com/zipisa-discount-code/) | No | 3 days | 69 USD/month (Starter) | Not stated | 2026-10-19 |

### Social Media

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Blip](https://kuponaut.com/blip-discount-code/) | No | 7 days, no card | 49 USD/month (Starter) | Not stated | 2026-10-19 |
| [CreatorFlow](https://kuponaut.com/creatorflow-discount-code/) | Yes: 500 DMs per month with core comment-to-DM automation | 14 days | 15 USD/month (Pro) | Not stated | 2026-09-20 |
| [Dynal.AI](https://kuponaut.com/dynal-ai-discount-code/) | Not stated | 3 days, no card | 40 USD/month (Starter) | Not stated | 2026-10-19 |
| [Fastlane](https://kuponaut.com/fastlane-discount-code/) | Not stated | 7 days | 29 USD/month (Starter (500 credits)) | Not stated | 2026-10-19 |
| [Favikon](https://kuponaut.com/favikon-discount-code/) | No | 7 days | 199 USD/month (Core) | Not stated | 2026-09-20 |
| [Lyter](https://kuponaut.com/lyter-discount-code/) | Not stated | 7 days | not stated | Not stated | 2026-09-27 |
| [Metricool](https://kuponaut.com/metricool-discount-code/) | Yes: One brand with core scheduling and analytics | – | 22 USD/month (Entry paid plan (unnamed, ~$22)) | Not stated | 2026-08-18 |
| [Nuelink](https://kuponaut.com/nuelink-discount-code/) | No | 7 days | 24 USD/month (Standard) | Not stated | 2026-10-19 |
| [Ocoya](https://kuponaut.com/ocoya-discount-code/) | Not stated | – | 15 USD/month (Entry plan (unnamed)) | Not stated | 2026-08-18 |
| [OneUp](https://kuponaut.com/oneup-discount-code/) | No | 7 days | 18 USD/month (Starter) | Not stated | 2026-10-19 |
| [Posttar](https://kuponaut.com/posttar-discount-code/) | Not stated | – | 49 USD/month (Essential) | Not stated | 2026-10-19 |
| [Reflare](https://kuponaut.com/reflare-discount-code/) | Not stated | – | 49 USD/month (Creator) | Not stated | 2026-10-19 |
| [Sked Social](https://kuponaut.com/sked-social-discount-code/) | Not stated | 14 days, no card | not stated | Not stated | 2026-10-19 |
| [SocialPilot](https://kuponaut.com/socialpilot-discount-code/) | Not stated | 14 days, no card | not stated | Not stated | 2026-09-03 |
| [SpamGuard](https://kuponaut.com/spamguard-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-15 |
| [Taplio](https://kuponaut.com/taplio-discount-code/) | Not stated | 7 days | 39 USD/month (Entry plan (name not stated)) | Not stated | 2026-08-31 |
| [TikControl](https://kuponaut.com/tikcontrol-discount-code/) | Not stated | 7 days | 24.99 USD/month (Premium) | Not stated | 2026-10-19 |
| [Tweet Hunter](https://kuponaut.com/tweet-hunter-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [Typefully](https://kuponaut.com/typefully-discount-code/) | Yes: Core composer and scheduling; AI, deeper analytics, multi-account are paid | – | not stated | Not stated | 2026-08-27 |
| [Wordflux](https://kuponaut.com/wordflux-discount-code/) | Not stated | 14 days | 10 EUR/month (Solo Basic) | Not stated | 2026-10-19 |

### Sports & Coaching

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [CoachThem](https://kuponaut.com/coachthem-discount-code/) | Yes: Basic drill creation and practice planning | – | not stated | Not stated | 2026-10-19 |
| [Fit3D](https://kuponaut.com/fit3d-discount-code/) | Not stated | – | 83 USD/month (SNAP) | Not stated | 2026-10-19 |
| [MacroPath](https://kuponaut.com/macropath-discount-code/) | No | 7 days, card | 9.99 USD/month (Monthly) | Not stated | 2026-10-19 |
| [Trophi AI](https://kuponaut.com/trophi-ai-discount-code/) | Not stated | 7 days | 89.99 USD/year (Premium) | Not stated | 2026-10-19 |

### Utilities & Security

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Amrev Software](https://kuponaut.com/amrev-discount-code/) | Yes: Free scan and preview; saving recovered files needs a licence (Data Recovery $39 for a 30-day licence, buy page 23 Oct 2026) | – | 19 USD/licence (Duplicate Photo Finder (1 PC)) | Not stated | 2026-10-23 |
| [BelkaVPN](https://kuponaut.com/belkavpn-discount-code/) | Not stated | – | 11.99 USD/month (Monthly) | Not stated | 2026-10-11 |
| [Database Mart](https://kuponaut.com/database-mart-discount-code/) | Not stated | 1 days | 2.69 USD/month (Windows desktop VPS (promo)) | Not stated | 2026-10-24 |
| [Donemax](https://kuponaut.com/donemax-discount-code/) | Yes: Free Data Recovery for Windows: scan, preview, recover up to 200 MB | – | 89.95 USD/year (Data Recovery (1 year, 2 PCs)) | Not stated | 2026-10-19 |
| [Dr.Fone](https://kuponaut.com/dr-fone-discount-code/) | Yes: Free download only scans and previews; Phone Transfer trial moves 5 contacts | – | 4.97 USD/month (Virtual Location module) | Yes: Up to 50% off via Wondershare education page (from $69.95 a year) | 2026-10-14 |
| [FastestVPN](https://kuponaut.com/fastestvpn-discount-code/) | Not stated | – | 5 USD/month (1 month) | Not stated | 2026-10-24 |
| [LogMeOnce](https://kuponaut.com/logmeonce-discount-code/) | Yes: Free forever: unlimited passwords, autofill, sync, 2FA, 1 MB encrypted storage | – | 2.5 USD/month (Professional) | Not stated | 2026-10-19 |
| [MiniTool](https://kuponaut.com/minitool-discount-code/) | Yes: Power Data Recovery Free recovers up to 1 GB; free Partition Wizard and ShadowMaker | – | 59 USD/year (Partition Wizard Pro (1 PC)) | Not stated | 2026-10-26 |
| [MobileTrans](https://kuponaut.com/mobiletrans-discount-code/) | Not stated | – | 25.99 USD/month (Single module (Windows)) | Not stated | 2026-10-14 |
| [NordVPN](https://kuponaut.com/nordvpn-discount-code/) | No | 7 days, card | 14.99 USD/month (Basic) | Yes: Extra 15% off the 2-year plan via Student Beans | 2026-10-14 |
| [Parallels Desktop](https://kuponaut.com/parallels-discount-code/) | Not stated | 14 days | 99.99 EUR/year (Standard (1-year subscription)) | Yes: Students/educators: Standard €49.99, Pro €59.99 first year (50% off) | 2026-10-23 |
| [Recoverit](https://kuponaut.com/recoverit-discount-code/) | Yes: Free scan/preview; recover 500 MB on Windows (another page says 100 MB) | – | 69.99 USD/month (Standard (1 PC)) | Yes: 30% off; yearly $48.99/$55.99/$69.99 on Windows | 2026-10-25 |
| [Scothosts](https://kuponaut.com/scothosts-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-07 |
| [Surfshark](https://kuponaut.com/surfshark-discount-code/) | Not stated | 7 days | not stated | Not stated | 2026-09-23 |
| [TroubleBuddy](https://kuponaut.com/troublebuddy-discount-code/) | Not stated | – | 7.5 GBP/month (Basic) | Not stated | 2026-10-14 |
| [Wallper](https://kuponaut.com/wallper-discount-code/) | Not stated | 7 days | 14.99 USD/one-time (Pro (up to 3 Macs)) | Not stated | 2026-10-19 |

### Video & Audio

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [AIVideo.com](https://kuponaut.com/aivideo-discount-code/) | Not stated | – | 19 USD/month (Starter) | Not stated | 2026-10-19 |
| [Arcads AI](https://kuponaut.com/arcads-ai-discount-code/) | Not stated | – | 110 USD/month (Entry plan (unnamed)) | Not stated | 2026-10-25 |
| [Argil AI](https://kuponaut.com/argil-discount-code/) | Not stated | – | 39 USD/month (Entry plan (unnamed)) | Not stated | 2026-08-07 |
| [BasedLabs AI](https://kuponaut.com/basedlabs-ai-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-25 |
| [Camtasia](https://kuponaut.com/camtasia-discount-code/) | Not stated | – | 39 USD/year (Starter) | Yes: Students $45 a year; educators $162.36 | 2026-10-15 |
| [CloneViral](https://kuponaut.com/cloneviral-discount-code/) | Not stated | – | 15 USD/month (Starter) | Not stated | 2026-10-19 |
| [Creatify](https://kuponaut.com/creatify-discount-code/) | Yes: 10 credits per month, watermarked output | – | 39 USD/month (Starter) | Not stated | 2026-08-20 |
| [Daydream](https://kuponaut.com/daydream-discount-code/) | Yes: 1 h transcription, 1 h video processing, 100 MCP calls a month | – | 20 USD/month (Creator) | Not stated | 2026-10-19 |
| [Descript](https://kuponaut.com/descript-discount-code/) | Yes: 60-minute monthly limit | – | 16 USD/month (Hobbyist) | Yes: EDU/NFP plan: $8/editor/mo billed annually ($12 monthly) | 2026-10-19 |
| [Elai.io](https://kuponaut.com/elai-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [ElevenLabs](https://kuponaut.com/elevenlabs-discount-code/) | Yes: 10,000 credits/month, no commercial licence | – | 6 USD/month (Starter) | Yes: Creator plan free for 3 months for verified university students (US, Canada, EU, Australia, UK) | 2026-10-25 |
| [Filmora](https://kuponaut.com/filmora-discount-code/) | Yes: Free forever; exported videos carry a watermark | – | 49.99 USD/year (Basic) | Yes: Up to 50% off for verified students via Student Beans | 2026-10-19 |
| [FlexClip](https://kuponaut.com/flexclip-discount-code/) | Yes: 720p, watermark, up to 10 min, 1 stock video+1 audio/project, 12 projects | – | 11.99 USD/month (Plus) | Yes: 40% off Plus and Business for verified students/educators; not combinable | 2026-10-24 |
| [Hailuo AI](https://kuponaut.com/hailuo-ai-discount-code/) | Yes: One-time trial credits, Hailuo models only, watermarked downloads | – | 10.5 USD/month (Standard) | Not stated | 2026-10-22 |
| [InVideo](https://kuponaut.com/invideo-discount-code/) | Yes: Limited credits reset weekly, watermark on videos, no card | – | 20 USD/month (Starter) | Not stated | 2026-10-14 |
| [Klap](https://kuponaut.com/klap-discount-code/) | Not stated | – | 29 USD/month (Basic) | Not stated | 2026-10-22 |
| [Movavi](https://kuponaut.com/movavi-discount-code/) | Not stated | 7 days | 19.95 USD/month (Video Editor 1 month) | Yes: Education pricing on edu.movavi.com (academic edition) | 2026-10-24 |
| [Murf AI](https://kuponaut.com/murf-ai-discount-code/) | Yes: 10 minutes of generation; no downloads or commercial rights | – | 29 USD/month (Creator) | Yes: 20% off for students/educators/non-profits; 6 months monthly or 1 annual | 2026-10-19 |
| [Opus Clip](https://kuponaut.com/opus-clip-discount-code/) | Yes: 60 credits/mo; watermark, 1080p cap, exports expire after 3 days | – | 15 USD/month (Starter) | Not stated | 2026-10-25 |
| [Pictory](https://kuponaut.com/pictory-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-25 |
| [PixVerse](https://kuponaut.com/pixverse-discount-code/) | Yes: Daily credits; free videos carry a watermark | – | 10 USD/month (Standard) | Not stated | 2026-10-15 |
| [Revid.ai](https://kuponaut.com/revid-discount-code/) | Not stated | – | not stated | Not stated | 2026-09-20 |
| [SpeakerSplit](https://kuponaut.com/speakersplit-discount-code/) | Not stated | – | not stated | Not stated | 2026-10-19 |
| [Speechify](https://kuponaut.com/speechify-discount-code/) | Yes: 10 basic voices | – | 29 USD/month (Premium) | Not stated | 2026-09-23 |
| [Submagic](https://kuponaut.com/submagic-discount-code/) | Not stated | – | 16 USD/month (Entry paid plan (unnamed)) | Not stated | 2026-10-25 |
| [Synthesia](https://kuponaut.com/synthesia-discount-code/) | Yes: 10 min video/dubbing a month, 500 credits, watermark, no downloads | – | 29 USD/month (Starter) | Not stated | 2026-10-07 |
| [Thematic](https://kuponaut.com/thematic-discount-code/) | Yes: Unlimited videos, no subscription; download limits, license link required | – | 9.99 USD/month (Premium) | Not stated | 2026-09-20 |
| [TTS Buddy](https://kuponaut.com/tts-buddy-discount-code/) | Yes: 120 TTS minutes + 30 downloads a month, API/CLI, 3 shared links, no card | – | 9.99 USD/month (Pro) | Not stated | 2026-10-19 |
| [UniConverter](https://kuponaut.com/uniconverter-discount-code/) | Not stated | – | 45.99 USD/year (Yearly (Windows)) | Yes: Up to 60% off (from $7.99 a month) on the education page | 2026-10-14 |
| [Vidlo](https://kuponaut.com/vidlo-discount-code/) | Not stated | – | 79 USD/month (Capture (2 campaigns)) | Not stated | 2026-10-19 |
| [Vidpal](https://kuponaut.com/vidpal-discount-code/) | Yes: 4 lifetime credits with a watermark, no card required | – | 19 USD/month (Starter) | Not stated | 2026-10-19 |
| [Vizard AI](https://kuponaut.com/vizard-discount-code/) | Yes | – | 29 USD/month (Entry paid plan (unnamed)) | Not stated | 2026-10-25 |
| [WayinVideo](https://kuponaut.com/wayinvideo-discount-code/) | Yes: 100 one-time credits (help says 200), 720p, 3-day export, no watermark, no card | – | 13.99 USD/month (Starter) | Not stated | 2026-10-19 |
| [Zebracat](https://kuponaut.com/zebracat-discount-code/) | Yes: Free-plan exports carry a watermark | – | 19 USD/month (Entry paid plan (unnamed)) | Not stated | 2026-08-12 |
| [Zeemo](https://kuponaut.com/zeemo-discount-code/) | Yes: 120 credits a year, captions up to 1 minute, 720p export | – | 9.99 USD/month (Pro) | No | 2026-10-22 |

### Writing & SEO

| Tool | Free plan | Trial | Cheapest paid | Student / education | Record |
|---|---|---|---|---|---|
| [Easy-Peasy.AI](https://kuponaut.com/easy-peasy-ai-discount-code/) | Yes: Monthly word allowance; unlimited generation and premium models are paid | – | not stated | Not stated | 2026-08-27 |
| [GPTZero](https://kuponaut.com/gptzero-discount-code/) | Yes: Basic scans; word volume, batch files, plagiarism and API are paid | – | not stated | Not stated | 2026-08-27 |
| [Greenlight Coverage](https://kuponaut.com/greenlight-coverage-discount-code/) | Not stated | – | 75 USD/month (Basic) | Not stated | 2026-10-19 |
| [Hoppy Copy](https://kuponaut.com/hoppy-copy-discount-code/) | Not stated | 7 days | not stated | Not stated | 2026-08-27 |
| [Jenni AI](https://kuponaut.com/jenni-ai-discount-code/) | Yes: 10 AI autocompletes a day and 10 PDF uploads | – | 30 USD/month (Plus) | Not stated | 2026-10-09 |
| [Moz Pro](https://kuponaut.com/moz-discount-code/) | No | 7 days, card | 49 USD/month (Starter (one website)) | No | 2026-10-14 |
| [Muze Writer](https://kuponaut.com/muze-writer-discount-code/) | Yes: Free tier described as generous; product in beta | – | not stated | Not stated | 2026-10-25 |
| [NeuronWriter](https://kuponaut.com/neuronwriter-discount-code/) | Not stated | – | 23 EUR/month (Entry plan (unnamed, ~€23)) | Not stated | 2026-08-18 |
| [Originality.ai](https://kuponaut.com/originality-ai-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [otomatic.ai](https://kuponaut.com/otomatic-discount-code/) | Not stated | – | 39 EUR/month (Standard) | Not stated | 2026-10-19 |
| [Outrank](https://kuponaut.com/outrank-discount-code/) | Not stated | – | 99 USD/month (Organic Growth) | Not stated | 2026-10-19 |
| [Squirrly SEO](https://kuponaut.com/squirrly-seo-discount-code/) | Yes: 1 site, 1 Focus Page, 5 AI keyword researches, 1 audit page a month | – | 9.99 USD/month (PRO) | Not stated | 2026-09-22 |
| [Vocable AI](https://kuponaut.com/vocable-ai-discount-code/) | Not stated | – | 48 USD/year (Basic) | Not stated | 2026-10-19 |
| [Winston AI](https://kuponaut.com/winston-ai-discount-code/) | Not stated | – | not stated | Not stated | 2026-08-27 |
| [Wordflow](https://kuponaut.com/wordflow-discount-code/) | Yes: ChatGPT only, 25 prompts, 100 answers/month | 14 days | 99 USD/month (Starter) | Not stated | 2026-10-19 |
| [WriteHuman](https://kuponaut.com/writehuman-discount-code/) | Yes: Limited requests | – | not stated | Not stated | 2026-08-27 |

## How to contribute

Open an issue with the tool name, the official page URL and what changed (price, free-tier limit, trial length, student policy). We re-read the page and update both this dataset and the Kuponaut record. Please do not submit coupon codes or referral links; they are out of scope here.

## Citation

> Kuponaut (2026). *AI & SaaS tool pricing dataset, October 2026 edition.* https://kuponaut.com/ai-tool-price-index/ (CC BY 4.0).
