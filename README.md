# KakaoPay (kakaopay)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

KakaoPay is a Korean mobile payment platform and fintech service by Kakao Corp providing REST APIs for payment processing, QR code payments, online checkout, subscription billing, money transfers, and financial product management. The platform enables merchants and developers to integrate KakaoPay's payment infrastructure via secure REST APIs authenticated with admin keys or bearer tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kakaopay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kakaopay/refs/heads/main/apis.yml)

## Tags

- Payments
- Mobile Payments
- QR Code Payments
- Subscription Billing
- Money Transfer
- Fintech
- Korean
- REST API

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### KakaoPay Online Payment API

REST API for integrating KakaoPay online payment functionality into PC and mobile web or app environments. Supports single payments, subscription (recurring) billing, order inquiry, and payment cancellation. Uses admin key authentication via Authorization header.

- **Human URL:** [https://developers.kakaopay.com/docs/payment/online-payment/single-payment](https://developers.kakaopay.com/docs/payment/online-payment/single-payment)
- **Base URL:** `https://open-api.kakaopay.com`

#### Tags

- Online Payment
- Single Payment
- Subscription
- Payment Cancellation

#### Properties

- [Documentation](https://developers.kakaopay.com/docs/payment/online-payment/single-payment)

### KakaoPay Login API

REST API providing KakaoPay authentication services including token issuance, token refresh, user information retrieval, and consent management. Enables applications to authenticate users via their KakaoPay credentials.

- **Human URL:** [https://developers.kakaopay.com/docs](https://developers.kakaopay.com/docs)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- Authentication
- Login
- OAuth
- Token

#### Properties

- [Documentation](https://developers.kakaopay.com/docs)

### KakaoPay Money Transfer API

REST API for code-based money transfers, enabling users to send and receive money via generated links. Supports money transfer link generation, retrieval, deletion, bill-splitting settlements, and service deregistration.

- **Human URL:** [https://developers.kakaopay.com/docs](https://developers.kakaopay.com/docs)
- **Base URL:** `https://open-api.kakaopay.com`

#### Tags

- Money Transfer
- Remittance
- Bill Splitting

#### Properties

- [Documentation](https://developers.kakaopay.com/docs)

### KakaoPay Face Recognition API

REST API providing facial detection and comparison capabilities for identity verification and authentication within KakaoPay financial services.

- **Human URL:** [https://developers.kakaopay.com/docs](https://developers.kakaopay.com/docs)
- **Base URL:** `https://open-api.kakaopay.com`

#### Tags

- Face Recognition
- Biometrics
- Identity Verification

#### Properties

- [Documentation](https://developers.kakaopay.com/docs)

## Common Properties

- [Website](https://www.kakaopay.com)
- [Documentation](https://developers.kakaopay.com/docs)
- [Git Hub Org](https://github.com/kakaopay)
- [LinkedIn](https://www.linkedin.com/company/kakaopay)
- [Blog](https://tech.kakaopay.com)
- [Pricing](https://developers.kakao.com/docs/latest/en/app-setting/paid-api)
- [Status Page](https://developers.kakaopay.com)
- [X (Twitter)](https://x.com/kakaocorpglobal)
- [Plans](plans/kakaopay-plans-pricing.yml)
- [Rate Limits](rate-limits/kakaopay-rate-limits.yml)
- [Fin Ops](finops/kakaopay-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
