# 0001: Use Wix Invoices for invoicing (Sept 2026 to Sept 2027)

- **Status:** Accepted
- **Date:** 2026-09-25
- **Review by:** 2027-09 (at the Wix plan renewal)

## Decision

From September 2026 to September 2027, Honour Diagnostic sends its invoices
through **Wix Invoices** on the existing Wix site, **Hannie Consultants cc**.

## Why

- **It's already paid for.** The current Wix subscription includes invoicing,
  so this adds no new cost.
- **It covers the Q1 2027 launch.** The plan runs to September 2027, which is
  past the launch and the first months of billing after it.
- **It's one less tool.** Clients, invoices and payments stay in the same
  dashboard as the website.

## Consequences

- Invoices, quotes and payment records live in Wix for this period.
- If we move to another tool later, we'll have to export the invoice history
  and client list out of Wix.
- Revisit this decision before the Wix plan renews in September 2027. Check
  invoice volume after launch, whether recurring billing is needed, whether it
  should connect to accounting software, and the cost at renewal.

## Setup checklist (before the Q1 2027 launch)

The values for each step are in [`docs/invoicing/wix-invoice-setup.md`](../invoicing/wix-invoice-setup.md).


- [x] Wix Invoices is installed, the site is on a Premium plan and the currency is USD (checked 2026-09-25)
- [ ] Note the plan's renewal date
- [ ] Add business details for invoices: legal name, address, VAT/tax number and logo
- [ ] Set the currency, tax rates and default payment terms
- [ ] Connect a payment provider so clients can pay invoices online
- [ ] Set invoice numbering (prefix and starting number) and default notes/terms
- [ ] Make a template for the Honour Diagnostic service line items
- [ ] Send a test invoice to ourselves and pay it from start to finish
- [ ] Set a calendar reminder for mid-2027 to review this decision
