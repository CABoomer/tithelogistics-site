---
layout: default
title: Support
permalink: /support/
prose: true
---

# Support

Questions, bugs or setup help: email **[{{ site.support_email }}](mailto:{{ site.support_email }})**. We aim to respond within one business day (Monday–Friday, US Eastern time).

Please include your store's `myshopify.com` domain and, if relevant, the order number or booking ID.

## Common questions

### Which carriers are supported?
XPO LTL today. More carriers will be added over time.

### Do I need my own carrier account?
Yes. Tithe Logistics books freight through accounts you hold directly with each carrier, so you keep your negotiated rates and your relationship with the carrier. You enter your carrier credentials in the app under **Settings → Carriers**, and they're checked when you save them.

### Can I try it before connecting a carrier account?
Yes. On a Shopify development store you can turn on simulated rates in **Settings → Carriers** to try quoting, checkout and booking end to end without a carrier account. Simulated rates never show at checkout on a live store.

### Why aren't freight rates showing at checkout?
- Your Shopify plan must support carrier-calculated shipping.
- Register the carrier service in **Settings → Carrier service**, then add the "Tithe Logistics LTL Freight" calculated rate to the shipping profile that holds your freight products. Shopify doesn't add it to profiles automatically.
- The product must be set up and enabled in the app's **Products** page, with carton and pallet details filled in.

If a cart can't be rated, checkout continues without a freight option rather than failing. Every rate attempt, including failures, is listed on the app's **Quotes** page.

### Is Tithe Logistics a freight broker?
No. Tithe Logistics is software only. Freight is contracted directly between you and your carrier. Billing questions, claims for loss or damage, and pickup or delivery issues are handled with the carrier.

### How am I billed?
Through your Shopify invoice. Each plan includes a number of bookings per billing cycle; bookings beyond that are charged per booking.

| Plan | Monthly | Included bookings | Each additional booking |
|---|---|---|---|
| Free | $0 | 10 total | not available |
| Starter | $29 | 10 per month | $5 |
| Growth | $89 | 50 per month | $4 |
| Pro | $149 | 200 per month | $3 |

Only bookings confirmed with the carrier count toward usage. Rate quotes, checkout rates and draft shipments are never charged. A booking still counts if you cancel it after the carrier has confirmed it.

### How do I remove my data?
Uninstall the app from Shopify admin. Your store's data is deleted as described in our [Privacy Policy]({{ '/privacy/' | relative_url }}#retention). You can also email us to request deletion sooner.
