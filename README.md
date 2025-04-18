# Home Assistant Node-RED MCP

A Node-RED MCP (Model Context Protocol) implementation with enhanced JSON validation and error handling. This project provides a robust interface between Home Assistant and Node-RED using the MCP protocol.

## Features

- Enhanced JSON validation and error handling
- JSON-RPC message validation
- Message framing support
- Comprehensive error logging
- Buffer management for partial messages
- TypeScript support

## Installation

```bash
npm install ha-nodered-mcp
```

## Usage

```typescript
import { FastMCP } from 'ha-nodered-mcp';

const mcp = new FastMCP({
  version: '1.0.0',
  // Additional configuration options...
});

// Start the MCP server
mcp.start();
```

## Development

To set up the development environment:

1. Clone the repository
2. Install dependencies: `npm install`
3. Run tests: `npm test`

## Testing

The project includes several test scripts:

- `npm test` - Run all tests
- `npm run test:watch` - Run tests in watch mode
- `npm run test:coverage` - Generate test coverage report
- `npm run test:ci` - Run tests in CI environment

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT