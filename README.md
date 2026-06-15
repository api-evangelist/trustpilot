# Trustpilot (trustpilot)

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
