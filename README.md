# Rails Banking Infrastructure API Documentation

Official documentation for the Rails Banking Infrastructure API and TypeScript SDK. This site provides comprehensive guides, API reference documentation, and integration examples for developers building with Rails.

## Project Overview

Rails is a modern banking infrastructure API that enables seamless financial transactions, multi-currency support, and intelligent transaction routing. This documentation covers:

- **API Reference**: Complete endpoint documentation and request/response schemas
- **SDK Guides**: Integration guides for the auto-generated TypeScript SDK (`@rails/sdk`)
- **Getting Started**: Quickstart guide, development setup, and core concepts
- **Examples & Best Practices**: Real-world code examples and integration patterns

## Quick Links

- **[Quickstart Guide](./quickstart.mdx)** - Get started in minutes
- **[Development Guide](./development.mdx)** - Set up your development environment
- **[API Reference](./api-reference/introduction.mdx)** - Full endpoint documentation
- **[SDK Installation](./guides/sdk-installation.mdx)** - Install and configure the SDK

## TypeScript SDK

The Rails TypeScript SDK (`@rails/sdk`) is auto-generated from the API specification and provides type-safe client libraries for all endpoints.

**Features:**
- Full TypeScript type definitions
- Request validation and error handling
- Support for Bearer token authentication
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
- Changes are automatically hot-reloaded in the dev server


## Resources

- [Rails SDK Repository](../rails-typescript)
- [API Server Repository](../api)
- [Quickstart Guide](./quickstart.mdx)
- [API Reference](./api-reference/introduction.mdx)
