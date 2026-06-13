# PayU

PayU is a global payment platform operating in 50+ emerging markets across Central & Eastern Europe, Latin America, the Middle East, and Africa. It processes 4 million financial transactions daily for 450,000+ merchants through 450+ local payment methods.

PayU provides REST APIs for payment processing, order management, refunds, payouts, subscriptions, fraud detection, checkout optimization, marketplace operations, tokenization, and financial services across multiple regional platforms.

## APIs

- **PayU Europe REST API** — Payment processing for CEE markets (Poland, Czech Republic, Hungary, Romania). OAuth 2.0 authentication. Supports orders, refunds, payouts, BLIK, 3DS 2.0, marketplace operations, and multi-currency pricing.
- **PayU India REST API** — Payment processing for India. Covers hosted checkout, payment links, recurring payments, subscriptions, save cards/vault, split settlements, wallets, cross-border payments, pre-authorization, payouts, and settlements.
- **PayU Latam Payments API** — Payment processing across Latin America (Argentina, Brazil, Chile, Colombia, Mexico, Peru). Includes HMAC-authenticated Pricing API for querying installment financing options.
- **PayU Enterprise API (PaymentsOS)** — Enterprise payment orchestration via a single API across multiple payment providers. Dynamic routing, risk management, network tokens, webhooks, and settlement reporting.

## Developer Resources

- Developer Portal (Global): https://corporate.payu.com/developer-documentation/
- Europe API Docs: https://developers.payu.com/europe/
- India API Docs: https://docs.payu.in/
- LatAm API Docs: https://developers.payulatam.com/
- Enterprise/PaymentsOS Docs: https://developers.paymentsos.com/docs.html
- GitHub Organization: https://github.com/PayU
- Blog: https://corporate.payu.com/blog/

## Status Pages

- Europe: https://status.secure.payu.com/
- Hub (Enterprise): https://status.paymentsos.com/
- LatAm: https://status.payulatam.com/
- India: https://pp2admin.payu.in/

## Files

- `apis.yml` — APIs.json 0.19 provider catalog
- `plans/payu-plans-pricing.yml` — Plan and pricing information
- `rate-limits/payu-rate-limits.yml` — Rate limit details by API region
- `finops/payu-finops.yml` — FinOps guidance for cost optimization and governance
