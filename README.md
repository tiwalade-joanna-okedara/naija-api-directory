# Naija API Directory 🇳🇬

**Every outside service one Nigerian e-commerce app needs: 68 of them, with honest notes on what works, what's slow and what's closed.**

I compiled this while building [Shopinbos](https://shopinbos.com), a store builder for Nigerian sellers. Founders, investors and policymakers talk about "the Nigerian tech ecosystem" without seeing what a small team actually has to stitch together to ship one product. This is that list.

🔎 **Searchable version:** https://tiwalade-joanna-okedara.github.io/naija-api-directory/

![Screenshot](screenshot.png)

Status key: ✅ works well · ⏳ slow approval · 💸 paid per use · 🚫 closed to Nigeria · 🤝 partnership first · ⚠️ unreliable

> Notes reflect my own experience building one product in 2026. They're not a ranking, and things change. Spotted something out of date? [Open an issue or PR](CONTRIBUTING.md).

## Must sort out first (8)

| Service | What it's for | Notes |
|---|---|---|
| **TikTok developer app** | for TikTok Login and posting videos. | ⏳ slow approval Audits and approvals take time. |
| **Meta Business verification** | unlocks WhatsApp, Instagram, Facebook and ads. Needs a CAC certificate, a utility bill and a website. | ⏳ slow approval Gate in front of WhatsApp, Instagram, Facebook messaging and ads. Needs a CAC certificate, a utility bill in the business name and a matching website. If any don't line up, you wait. |
| **WhatsApp platform number and first message templates** | sign-in codes, order updates, delivery codes. |  |
| **Paystack live mode** | needs CAC documents, director IDs and a business bank account. | ✅ works well Solid. Split payments let money go straight to the seller's own bank through a subaccount. |
| **SMS sender ID** | so texts arrive from "Shopinbos", not a random number. Approval takes days. | ⏳ slow approval Approval takes days. Build with a fallback SMS provider from day one. |
| **Apple Developer (organisation)** | needs a D-U-N-S number, which can take one to two weeks. | ⏳ slow approval Needs a D-U-N-S number, which can take one to two weeks. |
| **Google Play Console (organisation)** | identity checks, and new personal accounts must run a closed test first. | ⏳ slow approval New personal accounts must run a closed test first. |
| **KYC provider business account** | for BVN, NIN and CAC checks. | 💸 paid per use BVN, NIN and CAC lookups are paid per check, often from a prepaid wallet. |

## The core platform (9)

| Service | What it's for | Notes |
|---|---|---|
| **Supabase** | database, sign-in, file storage, live updates. | ✅ works well Works the same in Ibadan as in San Francisco. Billed in dollars. |
| **Vercel** | hosts the web app, the API and every seller's store. |  |
| **GitHub** | code, reviews, automatic checks. | ✅ works well Excellent. Billed in dollars. |
| **Expo (EAS)** | builds and updates the phone apps. | ✅ works well Excellent. Billed in dollars. |
| **Apple Developer** | iPhone apps and push notifications. |  |
| **Google Play and Firebase** | Android apps and push notifications. |  |
| **Upstash (Redis and QStash)** | rate limits, caching and background jobs. | ✅ works well Excellent. Billed in dollars. |
| **Sentry** | error alerts. | ✅ works well Excellent. Billed in dollars. |
| **PostHog** | analytics and feature switches. |  |

## Payments and money (8)

| Service | What it's for | Notes |
|---|---|---|
| **Paystack Transactions** | card, transfer and USSD at checkout. | ✅ works well Solid for card, transfer and USSD. |
| **Paystack Webhooks** | tells us when a payment succeeds, fails or is refunded. |  |
| **Paystack Transfers and Recipients** | payouts to sellers, suppliers and delivery companies. |  |
| **Paystack Resolve Account** | shows the account name when someone types a bank number. |  |
| **Paystack Dedicated Virtual Accounts** | a pay-in account for each delivery company. |  |
| **Paystack Refunds** | returns and cancelled orders. |  |
| **Dojah or Youverify** | BVN, NIN, CAC and selfie checks. | 💸 paid per use Paid per check. Worth having more than one provider as backup. |
| **Exchange rate source** | the naira price of yuan for China imports. |  |

## Messaging and sign-in (8)

| Service | What it's for | Notes |
|---|---|---|
| **WhatsApp Cloud API** | sign-in codes, order and delivery updates. |  |
| **WhatsApp Embedded Signup** | sellers connect their own WhatsApp Business number. |  |
| **WhatsApp message templates** | codes, orders, receipts, broadcasts. Every template needs Meta's approval. | ⏳ slow approval Every template needs Meta's approval. |
| **WhatsApp Catalog (Commerce API)** | sellers' products in their WhatsApp catalogue. |  |
| **Termii or Sendchamp** | SMS codes and delivery codes. |  |
| **Supabase Send SMS hook** | sends sign-in codes through WhatsApp or SMS. |  |
| **Resend** | email codes, receipts and payout notices. | ✅ works well Excellent. Billed in dollars. |
| **Expo Push (Apple and Google)** | "new order", "new message", "rider is coming". |  |

## AI and media (9)

| Service | What it's for | Notes |
|---|---|---|
| **Anthropic (Claude)** | powers Rex, who builds stores, and Peggy, who helps run them. |  |
| **Embeddings** | product search by meaning, not just keywords. |  |
| **Image generation** | logo ideas and banners. |  |
| **Background removal** | clean product photos. |  |
| **Video generation** | product videos for Reels, TikTok and WhatsApp Status. |  |
| **Text to speech** | voiceovers in English, Pidgin, Yorùbá and Hausa. |  |
| **Speech to text** | voice notes and voice typing. |  |
| **Translation** | Chinese product titles into English. Our AI handles this, so no extra service. |  |
| **Rive or Lottie** | animation files for Rex and Peggy. |  |

## Selling channels and ads (10)

| Service | What it's for | Notes |
|---|---|---|
| **Instagram messaging** | Instagram DMs in one inbox. |  |
| **Messenger Platform** | Facebook Page messages in the same inbox. |  |
| **Instagram content publishing** | post photos, carousels and Reels. |  |
| **Meta Catalog API** | Instagram and Facebook shops. |  |
| **Meta Marketing API** | click-to-WhatsApp adverts. |  |
| **TikTok Shop Partner API** | products and orders on TikTok Shop. | 🚫 closed to Nigeria When checked, Nigeria was not on TikTok Shop's list of seller markets, and partner developers must register in their own local market. |
| **TikTok Content Posting API** | post product videos to sellers' TikTok accounts. |  |
| **TikTok Marketing API** | TikTok adverts. |  |
| **Google Merchant Center** | free product listings on Google. |  |
| **Jumia and Konga** | marketplace listings. Manual applications first, APIs only after partner agreements. | 🤝 partnership first No open self-serve APIs. Partner agreement first. |

## Delivery and addresses (8)

| Service | What it's for | Notes |
|---|---|---|
| **Shipbubble** | quotes and bookings across couriers. |  |
| **GIG Logistics** | interstate delivery. |  |
| **Kwik** | same-day bikes in Lagos. |  |
| **Konga KOS, Dreacot and Travo** | more delivery options, partner agreements first. | 🤝 partnership first Partner agreements first. |
| **NIPOST postcode API** | correct postcodes at checkout. |  |
| **Google Maps Places** | address search at checkout. |  |
| **Google Maps Geocoding and Distance Matrix** | rider distance and delivery price. |  |
| **Google Maps SDK (mobile)** | the rider map in the apps. |  |

## Domains, imports and the website (8)

| Service | What it's for | Notes |
|---|---|---|
| **Vercel Domains API** | sellers' own web addresses with SSL. |  |
| **Domain registrar API** | sellers buy a web address inside the app. |  |
| **NiRA-accredited registrar** | .ng and .com.ng addresses. |  |
| **Cloudflare for SaaS** | a backup option for custom domains. |  |
| **China sourcing partner** | buying, quality-check photos and shipping from China. |  |
| **Shopify and WooCommerce import** | bring a seller's products and customers across. |  |
| **Instagram post import** | turn Instagram posts into products. |  |
| **WordPress** | the website, blog and help centre. |  |

## Also worth knowing

| Service | Notes |
|---|---|
| **CAC VAS API** | ⚠️ unreliable Worked in testing, then checks failed in production. Support form, chatbot and phone calls didn't resolve it. Backup identity providers were added. |
| **Africa's Talking** | ✅ works well Calls and SMS have been reliable. |

## What the list taught me

- **Payments are not the problem.** Paystack is solid, and split payments mean we never hold customers' money.
- **Plan for fallbacks from day one.** SMS, identity checks and some government data services can fail; have a second provider ready.
- **Approvals take weeks.** D-U-N-S numbers, sender IDs, Meta verification and app store reviews aren't technical problems. They're waiting.
- **Dollar billing hurts.** Most developer tools bill in dollars while customers pay in naira.
- **Partnerships come before APIs.** Several marketplaces and delivery companies need an agreement before you can integrate.

Full write-up: *Nigeria's API marketplace is thin, and builders are paying for it* (on my [LinkedIn](https://www.linkedin.com/in/tiwalade-joanna-okedara-kalu/)).

## Contributing

Building in Nigeria too? Add a service, update a note or share your experience. See [CONTRIBUTING.md](CONTRIBUTING.md).

---
Made by [Tiwalade Joanna Okedara-Kalu](https://github.com/tiwalade-joanna-okedara) · MIT licence