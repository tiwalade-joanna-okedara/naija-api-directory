# Naija API Directory 🇳🇬

**The APIs you need to build software in Nigeria, in one list.** Payments, identity and KYC, bank data and banking-as-a-service, SMS and WhatsApp, bills and airtime, delivery, and free reference data such as banks, states and LGAs.

🔎 **Searchable version:** https://tiwalade-joanna-okedara.github.io/naija-api-directory/

![Screenshot](screenshot.png)

## Why

Building a product in Nigeria means stitching together a dozen outside services, and the useful facts are scattered across blog posts, docs and group chats: who does virtual accounts, who checks BVN, which open banking API has shut down. This keeps them in one place, with plain-English descriptions and a status for each.

Last checked: 2026-11. Inclusion is not an endorsement; always check the provider's current docs, pricing and terms.

**Status key:** 🟢 operating · 🟡 acquired (still operating) · 🔴 shut down

## Payments and checkout

Accept cards, bank transfers, USSD and wallets, and pay out to Nigerian bank accounts.

| Service | What it does | Notes |
|---|---|---|
| 🟡 [Paystack](https://paystack.com) | Online checkout, payment links, subscriptions, transfers and split payments. Cards, bank transfer, USSD and QR. | Acquired by Stripe in 2020. Widely used by Nigerian startups and SMEs. |
| 🟢 [Flutterwave](https://flutterwave.com) | Pan-African payments: cards, transfers, mobile money, USSD and payment links across many currencies. Also offers bills payment APIs. | Good fit if you plan to sell in several African countries. |
| 🟢 [Monnify (Moniepoint)](https://monnify.com) | Collections through dedicated virtual accounts, payouts to any Nigerian bank, and a bills payment API. | Monnify says it was the first Nigerian gateway to offer virtual accounts. |
| 🟢 [Squad (GTCO)](https://squadco.com) | Collections by card, bank transfer and more, from Guaranty Trust's payments arm. |  |
| 🟢 [Kora](https://korahq.com) | Pay-ins and payouts, including card, bank transfer and wallets such as OPay and PalmPay. |  |
| 🟢 [Interswitch (Webpay / IPG)](https://www.interswitchgroup.com) | Long-standing payment gateway and switch. Verve cards, Quickteller and more. | Some developers find the integration heavier than newer gateways. |
| 🟢 [Remita](https://www.remita.net) | Collections and payments, widely used for government and institutional payments. |  |
| 🟢 [Fincra](https://fincra.com) | Pay-ins (gateway, payment links, virtual accounts) and payouts, including cross-border. |  |
| 🟢 [SeerBit](https://seerbit.com) | Payment gateway for cards, transfers and more. |  |
| 🟢 [eTranzact](https://www.etranzact.com) | Payment processing and switching, one of the older Nigerian players. |  |

## Identity and KYC

Check NIN (via NIMC), BVN (via NIBSS), documents, faces and businesses before you onboard someone.

| Service | What it does | Notes |
|---|---|---|
| 🟢 [Smile ID](https://usesmileid.com) | Pan-African ID verification: NIN, BVN, phone and document checks, selfie matching and business checks. |  |
| 🟢 [Dojah](https://dojah.io) | Identity verification, KYC widgets, fraud checks and lookups for African businesses. |  |
| 🟢 [Prembly (formerly IdentityPass)](https://prembly.com) | Identity and business verification APIs for Nigeria and other markets. |  |
| 🟢 [Youverify](https://youverify.co) | KYC, KYB and AML screening for banks and fintechs. |  |
| 🟢 [QoreID (VerifyMe)](https://qoreid.com) | Identity, address and business verification in Nigeria. |  |
| 🟢 [Didit](https://didit.me) | Global identity platform with Nigerian NIN and BVN checks and published per-check pricing. |  |

## Bank data and banking-as-a-service

Read account data with consent, open accounts for your users, issue virtual accounts and cards.

| Service | What it does | Notes |
|---|---|---|
| 🟡 [Mono](https://mono.co) | Open banking: connect bank accounts, read statements and balances, direct debit. | Acquired by Flutterwave in January 2026. |
| 🔴 [Okra](https://okra.ng) | Open banking API. | Shut down in May 2025. Remove it from old integrations. |
| 🟢 [Anchor](https://getanchor.co) | Banking-as-a-service: accounts, transfers, virtual accounts, cards, bill payments and bulk payouts. | Publishes an MCP server so AI coding tools can read its API docs. |
| 🟢 [OnePipe](https://onepipe.io) | Embedded finance through partner banks: accounts, payments and lending products. |  |
| 🟢 [Maplerad](https://maplerad.com) | Accounts, cards and payments infrastructure for African businesses. |  |

## SMS, OTP, voice and WhatsApp

Send OTPs, alerts and messages. In Nigeria, a registered sender ID and a backup route matter.

| Service | What it does | Notes |
|---|---|---|
| 🟢 [Termii](https://termii.com) | SMS, OTP, voice, WhatsApp and email APIs built in Nigeria, with a DND route for transactional messages. |  |
| 🟢 [Africa's Talking](https://africastalking.com) | SMS, voice, USSD and airtime APIs across Africa. |  |
| 🟢 [Sendchamp](https://sendchamp.com) | SMS, voice, WhatsApp and email APIs for African businesses. |  |
| 🟢 [Twilio](https://www.twilio.com) | Global SMS, voice, WhatsApp and Verify APIs. Works for Nigeria, usually at higher local prices. |  |
| 🟢 [WhatsApp Business Platform (Meta)](https://developers.facebook.com/docs/whatsapp) | Official WhatsApp API. Needs a verified Meta business; you pay Meta per message plus any provider fee. | Meta business verification asks for registration documents and a website that match. |

## Bills, airtime and data (VAS)

Sell airtime, data, electricity tokens, cable TV and more inside your product.

| Service | What it does | Notes |
|---|---|---|
| 🟢 [VTpass](https://www.vtpass.com/developers) | Airtime, data, cable TV, electricity, education and insurance payments, with a sandbox. |  |
| 🟢 [Baxi (Onafriq)](https://onafriq.com) | Bill payments through a large agent network and API. Onafriq lists 248 billers. |  |
| 🟢 [Flutterwave Bills](https://developer.flutterwave.com) | Airtime, data, cable, utilities and tax payments from your Flutterwave wallet. Nigerian billers only. |  |
| 🟢 [Monnify Bills Payment](https://monnify.com/products/bills-payment) | Airtime, data, electricity tokens, cable TV and education payments. API only. |  |

## Delivery and logistics

Quote, book and track deliveries inside Nigeria and abroad.

| Service | What it does | Notes |
|---|---|---|
| 🟢 [Shipbubble](https://shipbubble.com) | Shipping aggregator: one API for many couriers (DHL, UPS, GIG, Topship and others), with rate comparison. |  |
| 🟢 [GIG Logistics](https://giglogistics.com/developer) | Courier with APIs for shipping inside Nigeria and internationally. | Contact them for API access details. |
| 🟢 [Kwik Delivery](https://kwik.delivery) | Same-day last-mile delivery API, mainly Lagos and Abuja. |  |
| 🟢 [Sendbox](https://sendbox.co) | Local and international shipping and fulfilment. |  |
| 🟢 [Topship](https://topship.africa) | International shipping from Nigeria. |  |

## Free data and open-source helpers

Reference data you'll need on day one: banks, states, LGAs and holidays.

| Service | What it does | Notes |
|---|---|---|
| 🟢 [ng-banks (npm)](https://github.com/BolajiOlajide/ng-banks) | Zero-dependency package listing CBN-recognised Nigerian banks. |  |
| 🟢 [Nigerian Banks API](https://github.com/supermx1/nigerian-banks-api) | Static JSON of Nigerian banks with logos and USSD codes, served from GitHub Pages. |  |
| 🟢 [States and Cities API](https://github.com/devcenter-square/states-cities) | Open-source API for states, cities and LGAs. |  |
| 🟢 [OpenNG](https://openng-docs.vercel.app) | Nigerian public data as a REST API: holidays, states, LGAs, with fuel and food prices planned. |  |
| 🟢 [API Ninjas: Nigeria bank holidays](https://api-ninjas.com/bank-holidays/nigeria) | Nigerian bank holidays by year, useful for settlement and payroll dates. |  |

## Before you launch

| Requirement | Why it matters |
|---|---|
| CAC business registration | Most payment, KYC and WhatsApp providers ask for CAC documents before you go live. |
| Nigeria Data Protection Act 2023 (NDPC) | Applies whenever you process personal data of people in Nigeria, including ID checks. |
| CBN open banking framework | Went live on 1 August 2025. Affects how account-data and payment-initiation APIs work. |
| SMS sender ID registration | Branded sender IDs need approval per network. Plan a fallback route. |

## Contribute

Know a service that's missing, closed or renamed? Edit [`services.json`](services.json) and open a pull request. See [CONTRIBUTING.md](CONTRIBUTING.md). Facts only, with a link; no affiliate links.

---
Made by [Tiwalade Joanna Okedara-Kalu](https://github.com/tiwalade-joanna-okedara) · MIT licence
