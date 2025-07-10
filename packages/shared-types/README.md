# @workspace/shared-types

Este paquete contiene los tipos TypeScript generados por Payload CMS para todo el proyecto.

## Estructura

```
src/
└── payload-types.ts  # Tipos generados automáticamente por Payload
```

## Uso

```typescript
import type { Config, Media, User } from '@workspace/shared-types'

// Usar los tipos en tu código
const user: User = {
  id: 1,
  email: 'user@example.com',
  createdAt: '2024-01-01T00:00:00.000Z',
  updatedAt: '2024-01-01T00:00:00.000Z'
}
```

## Generación de tipos

Los tipos se generan automáticamente cuando ejecutas:

```bash
pnpm generate:types
```

El archivo se genera en `packages/shared-types/src/payload-types.ts` y se actualiza automáticamente cuando cambias las collections en el core.

## Tipos disponibles

- `User` - Tipo para usuarios
- `Media` - Tipo para archivos multimedia
- `Config` - Configuración completa de Payload
- `UsersSelect` - Selectores para consultas de usuarios
- `MediaSelect` - Selectores para consultas de media

## Desarrollo

```bash
# Verificar tipos
pnpm type-check

# Lint
pnpm lint
```
