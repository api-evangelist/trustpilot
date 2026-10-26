# Trustpilot (trustpilot)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Trustpilot is a global consumer review platform that connects businesses with their customers to build trust through transparent, verified reviews. Founded in 2007, Trustpilot hosts hundreds of millions of reviews across millions of businesses worldwide. The platform offers business APIs that allow companies to collect, manage, and display reviews programmatically, integrate review data into their own systems, and automate invitation workflows to gather customer feedback at scale. Trustpilot's APIs cover business profile management, service reviews, product reviews, invitation management, consumer profiles, and public review data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Consumer Reviews
- Reviews
- Trust
- Ratings
- Business Profiles
- Product Reviews

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Trustpilot Business Units API

The Trustpilot Business Units API provides endpoints to retrieve company profile information, reviews, images, categories, and web links for specific business units on Trustpilot. Developers can search for business units by name, retrieve public and private reviews with filtering options, access business profile images and logos, and list business categories. Public endpoints use API key authentication; private review endpoints require OAuth 2.0.

- **Human URL:** [https://developers.trustpilot.com/business-units-api](https://developers.trustpilot.com/business-units-api)
- **Base URL:** `https://api.trustpilot.com/v1`

#### Tags

- Business Profiles
- Reviews
- Trust
- Ratings

#### Properties

- [Documentation](https://developers.trustpilot.com/business-units-api)
- [Authentication](https://developers.trustpilot.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-business-units-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trustpilot-business-units.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-business-units.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trustpilot-invitation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-invitation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trustpilot Service Reviews API

The Trustpilot Service Reviews API enables businesses to manage service reviews, including posting replies, managing tags, finding reviewers, and retrieving review details. Businesses can respond to customer reviews, organize reviews with custom tags, and retrieve the latest reviews by language. Most management endpoints require OAuth 2.0 Business user tokens; public review endpoints are accessible with API keys.

- **Human URL:** [https://developers.trustpilot.com/service-reviews-api/](https://developers.trustpilot.com/service-reviews-api/)
- **Base URL:** `https://api.trustpilot.com/v1`

#### Tags

- Reviews
- Consumer Reviews
- Trust
- Ratings

#### Properties

- [Documentation](https://developers.trustpilot.com/service-reviews-api/)
- [Authentication](https://developers.trustpilot.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-service-reviews-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trustpilot-business-units.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-business-units.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trustpilot-invitation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-invitation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trustpilot Invitation API

The Trustpilot Invitation API allows businesses to programmatically send review invitations to their customers via email or SMS after a transaction or service interaction. It supports creating invitation links, triggering bulk email invitations for service and product reviews, retrieving invitation templates, and deleting invitation data by email or date range. All endpoints require OAuth 2.0 Business user token authentication.

- **Human URL:** [https://developers.trustpilot.com/invitation-api](https://developers.trustpilot.com/invitation-api)
- **Base URL:** `https://api.trustpilot.com/v1`

#### Tags

- Invitations
- Consumer Reviews
- Email
- Reviews
- Trust

#### Properties

- [Documentation](https://developers.trustpilot.com/invitation-api)
- [Authentication](https://developers.trustpilot.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-invitation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trustpilot-business-units.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-business-units.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trustpilot-invitation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-invitation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trustpilot Product Reviews API

The Trustpilot Product Reviews API enables management of product-level reviews, including retrieving product review summaries, accessing individual reviews, managing conversations and comments on product reviews, creating product review invitation links, and accessing attribute rating summaries. Supports both public and private endpoints with API key and OAuth 2.0 authentication respectively.

- **Human URL:** [https://developers.trustpilot.com/product-reviews-api/](https://developers.trustpilot.com/product-reviews-api/)
- **Base URL:** `https://api.trustpilot.com/v1`

#### Tags

- Product Reviews
- Reviews
- Consumer Reviews
- Trust

#### Properties

- [Documentation](https://developers.trustpilot.com/product-reviews-api/)
- [Authentication](https://developers.trustpilot.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-product-reviews-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trustpilot-business-units.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-business-units.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trustpilot-invitation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-invitation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trustpilot Consumer API

The Trustpilot Consumer API provides access to reviews written by individual consumers. Developers can retrieve a consumer's review history with filtering by stars, language, location, and business unit. Supports pagination and sorting and requires API key authentication.

- **Human URL:** [https://developers.trustpilot.com/consumer-api](https://developers.trustpilot.com/consumer-api)
- **Base URL:** `https://api.trustpilot.com/v1`

#### Tags

- Consumer Reviews
- Reviews
- Trust

#### Properties

- [Documentation](https://developers.trustpilot.com/consumer-api)
- [Authentication](https://developers.trustpilot.com/authentication)
- [Postman Collection](collections/trustpilot-business-units.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-business-units.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trustpilot-invitation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustpilot-invitation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.trustpilot.com/)
- [Portal](https://developers.trustpilot.com/)
- [Documentation](https://developers.trustpilot.com/)
- [Sign Up](https://www.trustpilot.com/signup/business)
- [Login](https://businessapp.b2b.trustpilot.com/login)
- [Pricing](https://www.trustpilot.com/pricing)
- [Authentication](https://developers.trustpilot.com/authentication)
- [Changelog](https://developers.trustpilot.com/changelog)
- [Support](https://support.trustpilot.com/)
- [Terms of Service](https://www.trustpilot.com/legal/terms-and-conditions-for-businesses)
- [Privacy Policy](https://www.trustpilot.com/legal/privacy-policy)
- [Blog](https://blog.trustpilot.com/)
- [Status Page](https://status.trustpilot.com/)
- [X (Twitter)](https://twitter.com/trustpilot)
- [LinkedIn](https://www.linkedin.com/company/trustpilot)
- [Facebook](https://www.facebook.com/trustpilot)
- [Git Hub](https://github.com/trustpilot)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/rules/trustpilot-rules.yml)
- [L L Ms Txt](https://developers.trustpilot.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
