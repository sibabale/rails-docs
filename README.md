# Rails Banking Infrastructure API Documentation

Official documentation for the Rails Banking Infrastructure API and official SDKs (TypeScript, Go, Java, Kotlin, C#). This site provides comprehensive guides, API reference documentation, and integration examples for developers building with Rails.

## Project Overview

Rails is a modern banking infrastructure API that enables seamless financial transactions, multi-currency support, and intelligent transaction routing. This documentation covers:

- **API Reference**: Complete endpoint documentation and request/response schemas
- **SDK Guides**: Integration guides for the official SDKs (TypeScript, Go, Java, Kotlin, C#)
- **Getting Started**: Quickstart guide, development setup, and core concepts
- **Examples & Best Practices**: Real-world code examples and integration patterns

## Quick Links

- **[Quickstart Guide](./quickstart.mdx)** - Get started in minutes
- **[Development Guide](./development.mdx)** - Set up your development environment
- **[API Reference](./api-reference/introduction.mdx)** - Full endpoint documentation
- **[SDK Installation](./guides/sdk-installation.mdx)** - Install and configure the SDK

## Official SDKs

Rails provides five official, auto-generated SDKs: **TypeScript** (`@rails/sdk`), **Go**, **Java**, **Kotlin**, and **C#**. Each is type-safe and exposes the same public API.

**Features:**
- Full TypeScript type definitions
- Request validation and error handling
- API key authentication (X-API-Key); explicit sandbox/production environment
- Comprehensive examples and integration guides

**Repository:** [`mvp/rails-typescript`](../rails-typescript)

For SDK setup and generation instructions, see [SDK_SETUP.md](../rails-typescript/SDK_SETUP.md).

## Local Development

To preview documentation changes locally:

```bash
npm install -g @rails/sdk
cd rails-docs
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

## Making Changes

- Edit `.mdx` files in the root and subdirectories
- Update `docs.json` to modify navigation, theme, or configuration
- **API spec:** `api-reference/openapi.json` is the public API spec and should be kept in sync with `mvp/rails-sdks/.stainless/openapi-rails.json` (single source of truth: SDK repo). When adding or changing public endpoints, update `mvp/rails-sdks/PUBLIC_API.md` and the OpenAPI spec there, then copy the spec here.
- Changes are automatically hot-reloaded in the dev server


## Resources

- [Rails SDK Repository](../rails-typescript)
- [API Server Repository](../api)
- [Quickstart Guide](./quickstart.mdx)
- [API Reference](./api-reference/introduction.mdx)
