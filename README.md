# Postman API Collections

This repository contains Postman collections, environments, and scripts
used for testing, validating, and documenting REST APIs.

It focuses on **real-world API testing scenarios**, including authentication,
token handling, and reusable request structures.

---

## 📌 What’s Included

- Postman collections for different API domains
- Environment configurations
- Authentication and token management scripts
- Reusable test and pre-request scripts
- Example requests for common API patterns

---

## 📂 Repository Structure

```text
postman-collections/
├── collections/
│   ├── auth/
│   │   └── auth_collection.json
│   ├── payments/
│   │   └── payment_collection.json
│   └── orders/
│       └── order_collection.json
│
├── environments/
│   ├── local.environment.json
│   ├── staging.environment.json
│   └── production.environment.json
│
├── scripts/
│   ├── token_extraction.js
│   ├── common_tests.js
│   └── pre_request_setup.js
│
└── README.md
