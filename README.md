# Trustpilot

Trustpilot is a global consumer review platform that connects businesses with their customers to build trust through transparent, verified reviews. Founded in 2007, Trustpilot hosts hundreds of millions of reviews across millions of businesses worldwide. The platform offers business APIs that allow companies to collect, manage, and display reviews programmatically, integrate review data into their own systems, and automate invitation workflows to gather customer feedback at scale.

**Developer Portal:** [developers.trustpilot.com](https://developers.trustpilot.com/)
**Website:** [trustpilot.com](https://www.trustpilot.com/)

---

## APIs

### Business Units API
Retrieve business unit profiles, reviews, images, categories, and search for businesses on Trustpilot.
- [Documentation](https://developers.trustpilot.com/business-units-api)
- [OpenAPI Spec](openapi/trustpilot-business-units-openapi.yml)

### Service Reviews API
Manage service reviews including replies, tags, reviewer identification, and public review retrieval.
- [Documentation](https://developers.trustpilot.com/service-reviews-api/)
- [OpenAPI Spec](openapi/trustpilot-service-reviews-openapi.yml)

### Invitation API
Send review invitations via email, create invitation links, and manage invitation templates.
- [Documentation](https://developers.trustpilot.com/invitation-api)
- [OpenAPI Spec](openapi/trustpilot-invitation-openapi.yml)

### Product Reviews API
Manage product-level reviews, conversations, summaries, and invitation links for specific product SKUs.
- [Documentation](https://developers.trustpilot.com/product-reviews-api/)
- [OpenAPI Spec](openapi/trustpilot-product-reviews-openapi.yml)

### Consumer API
Retrieve reviews written by individual consumers with filtering and sorting options.
- [Documentation](https://developers.trustpilot.com/consumer-api)

---

## Artifacts

### OpenAPI Specifications
| Spec | Description |
|---|---|
| [trustpilot-business-units-openapi.yml](openapi/trustpilot-business-units-openapi.yml) | Business Units API — profiles, reviews, images |
| [trustpilot-service-reviews-openapi.yml](openapi/trustpilot-service-reviews-openapi.yml) | Service Reviews API — replies, tags, retrieval |
| [trustpilot-invitation-openapi.yml](openapi/trustpilot-invitation-openapi.yml) | Invitation API — email invitations and links |
| [trustpilot-product-reviews-openapi.yml](openapi/trustpilot-product-reviews-openapi.yml) | Product Reviews API — product-level reviews |

### Spectral Rules
| File | Description |
|---|---|
| [trustpilot-rules.yml](rules/trustpilot-rules.yml) | Spectral ruleset enforcing Trustpilot API conventions |

### Naftiko Capabilities

#### Shared Definitions
| File | API |
|---|---|
| [shared/business-units.yaml](capabilities/shared/business-units.yaml) | Business Units API |
| [shared/service-reviews.yaml](capabilities/shared/service-reviews.yaml) | Service Reviews API |
| [shared/invitations.yaml](capabilities/shared/invitations.yaml) | Invitation API |

#### Workflow Capabilities
| File | Description | APIs |
|---|---|---|
| [review-management.yaml](capabilities/review-management.yaml) | Review monitoring, response, and invitation management | Business Units + Service Reviews + Invitations |

### JSON Schema
| File | Description |
|---|---|
| [trustpilot-review-schema.json](json-schema/trustpilot-review-schema.json) | Trustpilot review object schema |
| [trustpilot-business-unit-schema.json](json-schema/trustpilot-business-unit-schema.json) | Business unit profile schema |

### JSON Structure
| File | Description |
|---|---|
| [trustpilot-review-structure.json](json-structure/trustpilot-review-structure.json) | Review field structure documentation |

### JSON-LD Context
| File | Description |
|---|---|
| [trustpilot-context.jsonld](json-ld/trustpilot-context.jsonld) | JSON-LD context mapping Trustpilot vocabulary to schema.org |

### Examples
| File | Description |
|---|---|
| [trustpilot-search-business-units-example.json](examples/trustpilot-search-business-units-example.json) | Search business units |
| [trustpilot-get-business-unit-reviews-example.json](examples/trustpilot-get-business-unit-reviews-example.json) | Get business unit reviews |
| [trustpilot-send-email-invitations-example.json](examples/trustpilot-send-email-invitations-example.json) | Send email invitations |
| [trustpilot-create-review-reply-example.json](examples/trustpilot-create-review-reply-example.json) | Reply to a review |

### Vocabulary
| File | Description |
|---|---|
| [trustpilot-vocabulary.yml](vocabulary/trustpilot-vocabulary.yml) | Domain vocabulary for Trustpilot review and trust concepts |

---

## Authentication

Trustpilot APIs support two authentication methods:
- **API Key**: Pass `apikey` as a query parameter for public read-only endpoints
- **OAuth 2.0**: Required for private endpoints (review management, invitations, private data)
  - Supported flows: Authorization Code, Client Credentials, Implicit, Password

[Authentication Guide](https://developers.trustpilot.com/authentication)

---

## GitHub

Trustpilot maintains open source tools and plugins on GitHub:
- [node-trustpilot](https://github.com/trustpilot/node-trustpilot) — Node.js client
- [python-trustpilot](https://github.com/trustpilot/python-trustpilot) — Python client
- [documentation-bruno-collection](https://github.com/trustpilot/documentation-bruno-collection) — Bruno API collection
- [plugin-woocommerce](https://github.com/trustpilot/plugin-woocommerce) — WooCommerce integration
- [plugin-magento2](https://github.com/trustpilot/plugin-magento2) — Magento 2 integration

---

## Links

- [Website](https://www.trustpilot.com/)
- [Developer Portal](https://developers.trustpilot.com/)
- [Sign Up](https://www.trustpilot.com/signup/business)
- [Login](https://businessapp.b2b.trustpilot.com/login)
- [Pricing](https://www.trustpilot.com/pricing)
- [Changelog](https://developers.trustpilot.com/changelog)
- [Support](https://support.trustpilot.com/)
- [Status](https://status.trustpilot.com/)
- [Blog](https://blog.trustpilot.com/)
- [Privacy Policy](https://www.trustpilot.com/legal/privacy-policy)
- [Terms of Service](https://www.trustpilot.com/legal/terms-and-conditions-for-businesses)
- [GitHub](https://github.com/trustpilot)
- [LinkedIn](https://www.linkedin.com/company/trustpilot)
- [X (Twitter)](https://twitter.com/trustpilot)
- [Facebook](https://www.facebook.com/trustpilot)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
