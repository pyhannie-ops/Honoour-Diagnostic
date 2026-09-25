# Wix Invoices setup: Honour™ Diagnostic (USD)

This guide sets up Wix Invoices on **Hannie Consultants cc** to match
`Hannie_Invoice_Template_USD.docx`. The settings have to be entered in the
Wix dashboard. See the status note below for why.

## Status (checked 2026-09-25)

| Item | State |
|---|---|
| Wix Invoices app | Installed |
| Site currency | USD ✅ |
| Premium plan | Yes |
| Business name / email / address | Filled in (Callington Crescent, Cape Town, WC 7441) |
| Phone | +27 63 931 0758 ✅ (updated 2026-09-25 to match the template) |
| Logo, company registration no. | Not set in Business Info |
| Invoice numbering, template, items | **Enter these in the dashboard.** The new Wix Invoices API returns `428 INVOICES_API_UNAVAILABLE` for this site. Wix is moving sites off the older invoicing system gradually, and this one hasn't moved yet. |

## Dashboard links

- Invoice settings (numbering, customization, automations, price quotes):
  https://manage.wix.com/dashboard/10ff78fd-eec0-44fa-bd46-69fb2d58c790/wix-invoices/settings
- Invoice items & services:
  https://manage.wix.com/dashboard/10ff78fd-eec0-44fa-bd46-69fb2d58c790/wix-invoices/products/list
- New invoice:
  https://manage.wix.com/dashboard/10ff78fd-eec0-44fa-bd46-69fb2d58c790/wix-invoices/invoice/new
- Accept payments (online payment methods):
  https://manage.wix.com/dashboard/10ff78fd-eec0-44fa-bd46-69fb2d58c790/wix-cashier/payments
- Business Info (name, contact, logo): Settings > Business Info

## 1. Business Info

- Business name: `Hannie Consultants cc`
- Email: `hello@hannieonline.co.za`
- Phone: `+27 63 931 0758` (done)
- Address: Cape Town, South Africa (already set)
- Company ID / Reg. No.: *[Reg. number]*
- Logo: upload the Hannie logo

## 2. Numbering (Invoice settings)

- Prefix: `HC-2026-`
- Next number: `1`, padded to 3 digits if the setting is offered, which gives `HC-2026-001`
- Change the prefix to `HC-2027-` in January 2027. Wix gives each prefix its own counter.

## 3. Invoice customization (Settings > Invoice Customization)

Show on invoices:
- Business: email, phone, address, company ID (Reg. No.)
- Customer: company name, billing address, email, VAT / tax ID
- Items: description

Custom fields for the header:
- `Client PO / ref`
- `Engagement` (e.g. `Honour-001`)

Invoice title: `Honour™ Diagnostic`

## 4. Items & services

| Name | Price (USD) | Description |
|---|---|---|
| Honour™ Diagnostic: Deposit (50%) | 1,650.00 | Confirms booking. 3 facilitated sessions (90 min), organisational and individual reports, Gifts of Clarity. Engagement fee $3,300.00. |
| Honour™ Diagnostic: Balance (50%) | 1,650.00 | Balance of the $3,300.00 engagement fee, due on delivery of the Honour Report. |

Tax: none on either item. Hannie Consultants cc isn't registered for VAT, so
don't add a tax rate.

## 5. Default notes / footer

Paste this into the default note or footer. Fill in the two bracketed bank
fields first.

```
PAYMENT SCHEDULE
Deposit (50%), due to confirm booking: $1,650.00
Balance (50%), due on report delivery: $1,650.00 (invoiced separately)

PAYMENT BY BANK TRANSFER
Account name: Hannie Consultants cc
Bank: First National Bank (FNB), South Africa
Account type: [Business account type]
Account number: [Account number]
Branch code: 250655 (universal)
SWIFT / BIC: FIRNZAJJ
Payment reference: your invoice number
International transfers: please select bank charge code OUR so that the full
invoice amount is received. Payment is due in US dollars.

TERMS
Payment terms are set out in Clause 2 of the Service Agreement. The deposit
confirms the booking and secures Session 1. The balance is due on delivery of
the Honour Report. Fees are quoted in US dollars. Any bank charges on the
sending side are for the client's account.
Hannie Consultants cc is not registered for VAT. This is not a tax invoice.
```

## 6. Online payments (optional)

Bank transfer is the main way clients pay. To also let clients pay an invoice
online, turn on a payment method on the Accept payments page linked above.

## 7. Test

Make an invoice for yourself with the Deposit item. Check the number
(`HC-2026-001`), the custom fields, the footer and the total ($1,650.00).
Then delete it, or cancel it if Wix has already issued it.
