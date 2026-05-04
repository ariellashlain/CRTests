# Mock — detection QA (synthetic, not real credentials)
# Intel / domain: `bst-sanity-test.com` (matches `matched_assets` in the Code Repository payload)
```bash
# Synthetic payment-provider key for leak-detection fixtures (not a real credential; avoid realistic Stripe-style key prefixes so repo scanners stay green).
export STRIPE_KEY="sk_test_051H8cN4jK2mL9pQ7rT1vW3xY5zA6bC8dE0fG2hI4kL6mN8oP0qR2sT4uV6wX8yZ0aB2cD4"
export AWS_ACCESS_KEY_ID="AKIAX2Y3Z4A5B6C7D8E9"
```
