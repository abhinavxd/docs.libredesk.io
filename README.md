# Libredesk documentation

Source for [docs.libredesk.io](https://docs.libredesk.io), the documentation site for [Libredesk](https://libredesk.io), an open source, self-hosted customer support desk.

The site is built with [Mintlify](https://mintlify.com) and covers installation and configuration, the API reference generated from the OpenAPI spec, and setup guides for contributors.

## Development

Run the Mintlify dev server to preview changes locally:

```bash
npx mint dev
```

Or install the [CLI](https://www.npmjs.com/package/mint) globally first:

```bash
npm i -g mint
mint dev
```

The preview runs at `http://localhost:3000`.

## Repository structure

- `introduction.mdx` - main introduction page
- `getting-started/` - installation and setup guides
- `configuration/` - configuration documentation
- `contributing/` - developer and contributor guides
- `api-reference/` - OpenAPI specification and API docs
- `docs.json` - Mintlify navigation configuration

## Contributing

Send documentation fixes as pull requests to this repository. To contribute to Libredesk itself, see the [developer setup guide](https://docs.libredesk.io/contributing/developer-setup).

## Links

- Source: [github.com/abhinavxd/libredesk](https://github.com/abhinavxd/libredesk)
- Website: [libredesk.io](https://libredesk.io)
- Demo: [demo.libredesk.io](https://demo.libredesk.io)
