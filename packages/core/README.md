# @workspace/core

This package contains all the business logic for Payload CMS used in this boilerplate.

## Structure

```
src/
├── collections/     # Payload CMS Collections
├── globals/         # Payload CMS Globals
├── seeds/           # Database seeds
└── index.ts         # Main entry point
```

## Collections

- **Users**: Collection for system users
- **Media**: Collection for media files

## Usage

```typescript
import { collections } from '@workspace/core'

// Use in payload.config.ts
export default buildConfig({
  collections
  // ...rest of the config
})
```

## Development

```bash
# Install dependencies
pnpm install

# Development with watch
pnpm dev

# Build
pnpm build

# Type checking
pnpm type-check
```
