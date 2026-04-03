# MAC Address Vendor Lookup

MAC address vendor lookup with an embedded OUI database (~500 vendors). Everything runs client-side — no data is sent to any server.

**[Live Demo](https://gmowses.github.io/mac-lookup)**

## Features

- Lookup vendor from MAC address (any format: colon, dash, dot, raw)
- Embedded OUI database with top ~500 vendors
- Shows OUI, formatted MAC in all notations (colon, dash, dot, raw)
- Detects address type: unicast, multicast, broadcast, locally administered
- Dark/light mode
- i18n: English and Portuguese (BR)
- Client-side only

## Tech Stack

React 19 + TypeScript, Tailwind CSS v4, Vite, Lucide icons, GitHub Pages

## Development

```bash
npm install
npm run dev
```

## License

MIT — Gabriel Mowses
