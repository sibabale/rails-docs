# Rails Banking Infrastructure API Documentation

Official documentation for the Rails Banking Infrastructure API and TypeScript SDK. This site provides comprehensive guides, API reference documentation, and integration examples for developers building with Rails.

## Project Overview

Rails is a modern banking infrastructure API that enables seamless financial transactions, multi-currency support, and intelligent transaction routing. This documentation covers:

- **API Reference**: Complete endpoint documentation and request/response schemas
- **SDK Guides**: Integration guides for the auto-generated TypeScript SDK (`@rails/sdk`)
- **Development Essentials**: Best practices, authentication, and core concepts
- **AI Tools & Integration**: Advanced features and third-party integrations

## Quick Links

- **[Quickstart Guide](./quickstart.mdx)** - Get started in minutes
- **[Development Guide](./development.mdx)** - Learn core concepts and architecture
- **[API Reference](./api-reference/introduction.mdx)** - Full endpoint documentation
- **[SDK Setup](./essentials/code.mdx)** - Installation and configuration

## TypeScript SDK

The Rails TypeScript SDK (`@rails/sdk`) is auto-generated from the API specification and provides type-safe client libraries for all endpoints.

**Features:**
- Full TypeScript type definitions
- Request validation and error handling
- Support for API Key and JWT authentication
- Comprehensive examples and integration guides

**Repository:** [`mvp/rails-typescript`](../rails-typescript)

For SDK setup and generation instructions, see [SDK_SETUP.md](../rails-typescript/SDK_SETUP.md).

## Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

From the root of this documentation folder (where `docs.json` is located), run:

```bash
mint dev
```

View your preview at `http://localhost:3000`.

## Deployment

Changes are deployed automatically to production when merged to the main branch. You can monitor deployments from the Mintlify dashboard.

## Troubleshooting

- **Dev environment not running?** Run `mint update` to ensure you have the latest Mintlify CLI version.
- **404 errors?** Verify you're running from a directory with `docs.json`.
- **SDK generation issues?** See [SDK_SETUP.md](../rails-typescript/SDK_SETUP.md) for Speakeasy configuration.

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Mintlify Community](https://mintlify.com/community)
- [Rails SDK Repository](../rails-typescript)
- [API Server Repository](../api)
