# Mock — detection QA (synthetic, not real credentials)
# Intel / domain: `bst-sanity-test.com` (matches `matched_assets` in the Code Repository payload)
```bash
# Synthetic leak lines for CR QA. Replace with realistic-looking test keys only after GitHub push protection allows it (e.g. paths-ignore + secret scanning enabled, or user push protection off).
export STRIPE_KEY="MOCK_STRIPE_SK_NOT_REAL_01"
export AWS_ACCESS_KEY_ID="MOCK_AWS_ACCESS_KEY_NOT_REAL_01"
```
