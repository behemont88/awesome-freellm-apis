# Contributing to Awesome Free LLM APIs

First of all, thank you for considering contributing to this repository! We want to build a high-quality global resource for free LLM APIs.

To ensure this list remains useful and high-quality, please review the following guidelines.

## Submission Guidelines

### 1. No Spam or Pure Advertising
This repository is dedicated to APIs that offer **genuine free tiers** for developers. 
- Do **NOT** submit PRs or Issues that are purely promotional for paid-only services.
- Submissions just asking for inclusion without clear details on the free tier limits will be rejected.
- We welcome services that have paid tiers, provided they have a distinct, usable free tier.

### 2. Formatting Your Contribution
When submitting a new API, include the details needed to maintain the provider
directory accurately:

- Provider name and official website
- OpenAI-compatible or other API base URL
- API-key signup URL
- Free quota or rate-limit details
- Notable free models
- Maximum context window
- Whether a credit card or phone verification is required
- Verified API protocols

**Example submission details:**
```text
Provider: Example AI
Website: https://example.com
Base URL: https://api.example.com/v1
API Key: https://example.com/settings/api-keys
Free Quota: 60 requests per minute
Models: Example 70B
Max Context: 128K
Credit Card: No
Verification: Email
Protocols: OpenAI Chat Completions
```

### 3. Global Project
This is a global project with READMEs in multiple languages (`README.md`, `README.zh-CN.md`, etc.).
- When adding an API, please add it to the primary `README.md` (English) at a minimum.
- If you can, we highly appreciate updates to the localized README files to keep them in sync.

## How to Submit

1. Fork the repository.
2. Create a new branch (`git checkout -b add-new-api`).
3. Add your changes following the formatting guidelines above.
4. Commit your changes (`git commit -m 'Add NewAPI to the list'`).
5. Push to the branch (`git push origin add-new-api`).
6. Open a Pull Request and complete the PR checklist.

Thank you for your contributions!
