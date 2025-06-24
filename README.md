# Phantom Developer Documentation

This repository contains the developer documentation for Phantom wallet, built with [Mintlify](https://mintlify.com/).

## Overview

Phantom is a crypto wallet that can be used to manage digital assets and access decentralized applications on Solana, Bitcoin, Ethereum, Base, and Polygon.

This documentation covers:
- Blockchain integrations (Solana, Ethereum/EVM, Sui, Bitcoin)
- API references and provider methods
- Mobile integration via deeplinks
- Developer tools and powertools
- Best practices for dApp integration
- Token display guidelines

## Development

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) to view the documentation locally.

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build the documentation
- `npm run preview` - Preview the built documentation

## Project Structure

```
docs/
├── docs.json                 # Mintlify configuration
├── introduction.mdx          # Homepage content
├── solana/                   # Solana integration docs
├── ethereum-monad-testnet-base-and-polygon/ # EVM networks docs
├── sui/                      # Sui integration docs
├── bitcoin/                  # Bitcoin integration docs
├── phantom-deeplinks/        # Mobile deeplinks documentation
├── developer-powertools/     # Advanced developer features
├── best-practices/          # Integration best practices
└── resources/               # Additional resources and FAQ
```

## Contributing

When adding new documentation:

1. Create `.mdx` files for new pages
2. Add proper frontmatter with `title` and `description`
3. Update `docs.json` navigation structure
4. Use absolute paths for internal links (e.g., `/solana/getting-started`)
5. Follow Mintlify's [component documentation](https://mintlify.com/docs/components) for advanced formatting

## Deployment

This documentation is automatically deployed via Mintlify's hosting platform. Updates to the main branch will trigger automatic deployments.

## Support

- [Phantom Help Center](https://help.phantom.app/)
- [Developer Community](https://github.com/orgs/phantom/discussions)
- [Mintlify Documentation](https://mintlify.com/docs)

## License

MIT