# OCEAN-SYSTEM GitHub profile

This repository owns the public OCEAN-SYSTEM organization profile in [`profile/README.md`](profile/README.md). It records stable, public operating principles; it is not an inventory of internal projects or an authority for product-specific requirements.

## Source of truth

For a change, use this order:

1. the current approved Issue or owner decision;
2. accepted documentation in the repository being changed;
3. OCEAN-SYSTEM engineering standards available to maintainers;
4. current code, tests, pull requests, CI, and deployed readback.

The profile should link to a public authoritative source when one exists instead of copying details that are likely to drift. Product contracts, deployment procedures, and legal copy remain in the repository that owns them.

## Update workflow

1. Open or identify an Issue that states the purpose, public facts, scope, non-goals, and acceptance checks.
2. Make the smallest complete change on a branch. Keep unrelated cleanup and unreleased-product details out.
3. Preview the rendered Markdown and verify every link without organization credentials.
4. Use a pull request. Complete the current exact-head checks and review gate before merge when they are configured.
5. Treat merge and publication as distinct decisions when the change also depends on a release, domain, provider, credential, legal, or billing action.

## Public-content boundary

Do not add:

- secrets, tokens, account IDs, private endpoints, or operational access details;
- private repository or unreleased-product names;
- personal data that has not been explicitly approved for public use;
- claims of legal compliance, certification, security guarantees, availability, or support levels without current evidence and authority;
- production status inferred from source code, a preview, or an old deployment.

Keep statements factual, dated when freshness matters, and understandable without internal context. Accessibility, privacy, security, operating cost, reversibility, and maintenance load are part of acceptance, not optional follow-up work.

## Review checklist

- The profile has one clear organization description and no unsupported promotional claim.
- Heading order, link text, and language are readable and accessible.
- All linked destinations are public, intentional, current, and HTTPS.
- The change exposes no internal inventory, credential material, or unapproved personal data.
- Repository-specific facts stay with their owning repository.
- The rendered GitHub profile has been checked after merge.

## Repository boundary

This repository controls only the organization profile and its maintenance notes. It does not change organization settings, repository permissions, branch protection, secrets, billing, DNS, provider configuration, or production deployments.
