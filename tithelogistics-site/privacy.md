---
layout: default
title: Privacy Policy
permalink: /privacy/
prose: true
---

# Privacy Policy

<p class="meta">Effective {{ site.policy_effective_date }}</p>

This Privacy Policy explains how {{ site.legal_name }} ("**Tithe Logistics**", "**we**", "**us**") collects, uses, shares and protects information when a merchant installs and uses the Tithe Logistics app for Shopify (the "**App**"), and how that affects the merchant's customers.

## 1. Who this applies to

- **Merchants** — Shopify store owners and their staff who install the App.
- **Customers** — people who shop at a merchant's store. The merchant is the controller of customer data; we process it on the merchant's behalf and only to provide the App.

## 2. Information we collect

| Category | Examples | Source |
|---|---|---|
| Store information | Shop domain, store name, contact email, currency, locations and addresses you ship from | Shopify API, when you install |
| Shopify access credentials | The OAuth access token Shopify issues to the App | Shopify, when you install |
| Carrier account credentials | Account numbers, API keys, usernames/passwords or tokens for the carrier accounts you connect | Entered by you in the App |
| Product data | Product and variant titles, SKUs, weight, dimensions, freight class, carton and pallet configuration | Shopify API and your settings in the App |
| Checkout rate requests | Destination address (street, city, state, postal code, country) and cart contents sent by Shopify to calculate freight rates | Shopify, at checkout |
| Order and shipment data | Order number, line items, ship-to name, company, address, phone number and email; delivery notes; bookings, PRO/BOL numbers and tracking status | Shopify API and the carrier |
| Billing and usage | Plan, number of confirmed bookings, connected carrier count | Shopify Billing API and App usage |
| Technical data | Server logs, IP addresses of requests, error reports | Automatically, when the App is used |

We do **not** collect payment card information. Customer payments are processed by Shopify, and App subscription charges are billed through Shopify.

## 3. How we use information

- To calculate and display freight rates at checkout.
- To create, manage and track shipments with the carriers you choose.
- To bill you for confirmed bookings under your plan.
- To provide support, troubleshoot problems and secure the App.
- To comply with legal obligations and enforce our [Terms of Service]({{ '/terms/' | relative_url }}).

We do not sell personal information, use it for advertising, or use customer data for any purpose other than providing the App to the merchant.

## 4. How we share information

- **Carriers you connect.** Shipment details (including ship-to name, address and phone) are sent to the carrier you select, under your account, to quote and book freight. Each carrier's use of that data is governed by its own privacy policy and your agreement with it.
- **Shopify.** We exchange data with Shopify to operate the App and for billing.
- **Service providers.** Infrastructure and hosting ({{ site.hosting_provider }}), and similar vendors who process data only on our instructions and under confidentiality obligations.
- **Legal reasons.** When required by law, subpoena or court order, or to protect the rights, property or safety of us, our users or others.
- **Business transfers.** In connection with a merger, acquisition or sale of assets, subject to this Policy.

## 5. Security

Carrier credentials and Shopify access tokens are encrypted at rest. Data is encrypted in transit using TLS. Access to production systems is limited to personnel who need it to operate the App. No method of transmission or storage is completely secure, but we work to protect your information using industry-standard safeguards.

## 6. Data retention and deletion {#retention}

- **While the App is installed**, we keep data as long as needed to provide the service. Shipment and booking records are kept so you can view history and for billing.
- **When you uninstall**, we stop accessing your store. When Shopify sends the `shop/redact` request (typically 48 hours after uninstall), we delete your store's data, including carrier credentials, within 30 days, except billing records we must keep for tax and accounting purposes.
- **Customer requests.** We honor Shopify's `customers/data_request` and `customers/redact` requests. When a merchant's customer asks to see or delete their data, we provide or delete the data we hold for that customer within 30 days, except where we must keep it by law.
- Server logs are kept for up to [90] days.

## 7. Your rights

Depending on where you live (for example under the GDPR, UK GDPR, or the California Consumer Privacy Act), you may have the right to access, correct, delete, or receive a copy of your personal information, and to object to or restrict certain processing.

- **Merchants** can exercise these rights by emailing [{{ site.privacy_email }}](mailto:{{ site.privacy_email }}).
- **Customers** should contact the merchant they shopped with first, since the merchant controls their data. We will assist the merchant in responding.

We will not discriminate against you for exercising any of these rights.

## 8. International transfers

We are based in the United States, and data is processed and stored in the United States. Where required, we rely on appropriate safeguards for transfers of personal data from the EEA or UK.

## 9. Children

The App is a business tool not directed to children under 16, and we do not knowingly collect their personal information.

## 10. Changes to this Policy

We may update this Policy from time to time. We will post the new version on this page with a new effective date and, for material changes, notify merchants by email or in the App.

## 11. Contact

{{ site.legal_name }}<br>
{{ site.mailing_address }}<br>
[{{ site.privacy_email }}](mailto:{{ site.privacy_email }})
