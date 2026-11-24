# Commercial Proposal: Petrel CDN for Kitefold, Inc.

Date: July 8, 2026

Prepared for: Maya Lindqvist, Founder and CEO, and Arjun Mehra, Co-founder and CTO, Kitefold, Inc., Port Calloway

Prepared by: Petrel CDN, Commercial Team

1. Summary

Thank you for the time your team spent describing how Kitefold delivers WebAR experiences to phones. Your workload is bursty and made up of many small, cacheable assets, such as 3D models, textures, tracking targets and scene bundles. Visitors expect these to load within moments of opening a link or scanning a code. This proposal sets out how Petrel CDN would deliver that content, what it would cost, and how we would help you move over without disrupting experiences that are already published.

In short: a delivery rate of $0.012 per GB delivered, a minimum commitment of $1,500 a month on a 12-month term, migration support at no additional charge, and a named support path that starts with your account executive Corin Vale.

2. Pricing

2.1 Delivery rate. Content delivered from the Petrel network is billed at $0.012 per GB delivered, effective from July 8, 2026. The rate applies to all delivered traffic, whatever the region of the visitor. There are no separate request fees, no charges for cache fills from your origin, and no charges for certificate management.

2.2 Minimum commitment and term. The service is offered with a minimum commitment of $1,500 a month on a 12-month term. Each month, delivery charges accrue at the rate in clause 2.1. If the charges for a month are below the minimum commitment, the minimum is invoiced for that month. If they exceed it, the usage-based amount is invoiced.

2.3 Overage. Usage above the minimum commitment is billed at the same per-GB rate. There is no tiered surcharge for traffic spikes, such as those from a campaign launch or a trade-show demo.

2.4 Invoicing. Invoices are issued monthly in arrears, with a per-region usage breakdown so your finance team can reconcile delivery against your own analytics.

2.5 Taxes. Prices are exclusive of sales tax, which is added where applicable.

3. Network and points of presence

Petrel operates points of presence in the following regions: North America, South America, Europe, the Middle East, Africa, South Asia, East Asia, Southeast Asia and Oceania. Requests are routed to the nearest healthy location. If a location degrades, traffic is redirected automatically to the next best one, so visitors do not see an error page.

Capabilities relevant to Kitefold include:

a) Tiered caching, so that large 3D assets are fetched from your origin once and then served from regional caches.

b) Modern transport protocols and compression tuned for binary model formats and image targets.

c) Configurable cache rules by path, file type or header, so that republished experiences can be refreshed on a schedule you control.

d) Instant purge by URL, prefix or tag, with propagation across the network in seconds.

e) Signed URLs and token authentication for assets that should be available only to specific projects or accounts.

f) Near-real-time logs and a delivery dashboard that can be exported to your own analytics tools.

4. Migration support

We know a CDN change is only successful if nobody notices it. Our migration support is included in the terms above at no additional charge and follows this outline:

4.1 Discovery. We review your current asset paths, cache headers, custom domains and certificate arrangements with your engineering team, and agree a written cutover plan.

4.2 Staging. We configure a parallel Petrel setup that mirrors your current behavior. Your team can test it with internal projects using a temporary hostname before any live traffic moves.

4.3 Gradual cutover. Traffic is shifted in stages through DNS weighting, starting with a small share of requests. We monitor error rates, cache hit ratios and load times at each stage, and you can return to your previous setup at any point during the cutover.

4.4 Verification. Once all traffic has moved, we run a joint check of previously published experiences to confirm that they load and behave as before, and we tune cache rules based on observed traffic.

4.5 Hypercare. Our engineers provide close monitoring and a faster response path during the cutover and for a short period after it, so that any surprise is handled quickly.

5. Support levels

5.1 Standard support. Included with every account. Ticket and email support during business hours, a public status page, and access to documentation and configuration guides.

5.2 Priority support. Included in this proposal at no extra charge. Around-the-clock coverage for production-impacting issues, a target first response of 1 hour for critical incidents, and proactive notification of any degradation affecting your traffic.

5.3 Account management. Your account executive Corin Vale is your single point of contact for commercial questions, contract changes and escalations. Corin will also arrange periodic service reviews covering usage, performance and upcoming needs.

5.4 Incident communication. During an incident we send status updates to your designated contacts at regular intervals until resolution, followed by a written summary of cause and corrective action.

6. Contract terms

6.1 Governing document. The service would be provided under a Master Subscription Agreement and an order form that reflects the pricing and term in section 2.

6.2 Service credits. The Master Subscription Agreement includes a delivery availability commitment, with service credits applied to your invoice if it is not met.

6.3 Data handling. Petrel processes delivery logs and cached content only to provide the service. Details are set out in our data processing terms, which accompany the Master Subscription Agreement.

6.4 Proposal validity. The pricing in this proposal is offered from July 8, 2026 and remains available while we finalize the order form with your team.

7. Next steps

a) Share a current traffic profile with us, such as monthly delivered volume and your busiest periods, so we can confirm that the minimum commitment fits your usage.

b) Review the draft Master Subscription Agreement and order form with your team.

c) Agree a cutover plan and a staging schedule with our engineers.

Please direct questions or requests for changes to account executive Corin Vale at Petrel CDN. We would be glad to walk your engineers through the network and the migration plan in a working session.

We appreciate the opportunity to earn Kitefold's traffic and look forward to working with you.

Corin Vale

Account Executive, Petrel CDN