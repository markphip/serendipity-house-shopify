# Serendipity House Shopify Theme

This repository contains the District Shopify theme used by
the Serendipity House retail website.

## Development rules

- Never modify the published Shopify theme directly.
- Never publish a theme without explicit approval.
- Never modify products, collections, or store metadata.
- Preserve existing merchant customizations.
- Use existing District theme components whenever possible.
- Prefer small, targeted changes over major rewrites.
- Follow Shopify Liquid best practices.
- Use Shopify Dev MCP for Shopify-specific API guidance.
- Run Shopify Theme Check after modifications.
- Never introduce credentials or API tokens into the repository.

## Workflow

1. Analyze existing code before proposing changes.
2. Explain the intended modifications.
3. Make changes on a feature branch.
4. Validate changes using Shopify Theme Check.
5. Preview changes using Shopify CLI.
6. Create a pull request for review.

## Important

The theme is used by a live retail business.

Avoid modifying existing product or collection references
without understanding their purpose.

The merchant also makes changes through Shopify Admin,
so preserve compatibility with the visual theme editor.