# HT-AIOS Implementation Status

HT-AIOS is the product-facing/static MVP layer for the Thoroughbred Moving Services Moving Operations Command System.

## Production priorities
1. Persistent jobs/customers/quotes/bookings data.
2. Admin dispatch board and crew assignment.
3. Pricing engine for 27/49/99-mile zones and 2/3/4-person crews.
4. U-Box/container tracking and profitability.
5. Deposit/payment-status workflow without embedded secrets.
6. Review-request and review-velocity tracking.
7. Revenue, crew-pay, job-margin, and utilization dashboards.
8. Authentication/roles and audit history.
9. Customer communication/status workflow.
10. Import/export and backup-safe data handling.

## Safety
- Never commit live credentials.
- Never silently delete production/customer data.
- External integrations should expose setup requirements rather than invent credentials.
- Preserve audit history for material operational changes.
