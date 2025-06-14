# Spoo.me API Documentation

This repository contains the official API documentation for **spoo.me** - a lightning-fast URL shortening service built for scale.

## Overview

Spoo.me provides a comprehensive API for:
- 🔗 URL shortening with custom aliases
- 😉 Emoji-based shortened URLs  
- 📊 Detailed analytics and statistics
- 📤 Data export in multiple formats
- 🔒 Password protection and click limits
- 🤖 Bot blocking capabilities

**Base URL:** `https://spoo.me`

## Documentation Features

- **Complete API Reference** - All endpoints with code examples in 7+ languages
- **Interactive Examples** - Copy-paste ready code snippets
- **Rate Limiting Guide** - Best practices and implementation
- **Python Library** - Official py_spoo_url documentation
- **Discord Bot** - SpooBot integration guide
- **Error Handling** - Comprehensive error reference

## Development

### Prerequisites

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview documentation changes locally:

```bash
npm i -g mintlify
```

### Local Development

Run the following command at the root of the documentation directory:

```bash
mintlify dev
```

This will start a local development server where you can preview your changes in real-time.

### Project Structure

```
spoo-docs/
├── docs.json              # Main configuration
├── introduction.mdx       # Homepage
├── quickstart.mdx         # Quick start guide
├── rate-limits.mdx        # Rate limiting documentation
├── api-reference/         # API endpoint documentation
│   ├── shorten-url.mdx
│   ├── emoji-url.mdx
│   ├── url-statistics.mdx
│   └── export-data.mdx
└── tools/                 # Tools and integrations
    ├── python-library.mdx
    └── spoobot.mdx
```

## Publishing Changes

Changes are automatically deployed to production when pushed to the main branch through our Mintlify integration.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes and test locally with `mintlify dev`
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## API Support

- **Documentation Issues**: Open an issue in this repository
- **API Support**: Contact [support@spoo.me](mailto:support@spoo.me)
- **Discord Community**: Join our [Discord server](https://discord.gg/spoo-me)

## Troubleshooting

**Mintlify dev isn't running**
```bash
mintlify install  # Re-install dependencies
```

**Page loads as 404**
- Ensure you're running in the folder containing `docs.json`
- Check that the page exists in the navigation configuration

**Build issues**
- Verify all `.mdx` files have proper frontmatter
- Check for syntax errors in code blocks
- Ensure all internal links are valid

---

Built with ❤️ using [Mintlify](https://mintlify.com)

