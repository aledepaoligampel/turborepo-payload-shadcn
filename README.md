# Turborepo + Payload + shadcn/ui Boilerplate

This project is a modern starting point for B2B applications, combining:

- **Payload CMS** as a headless backend and data core
- **shadcn/ui** for a modern and customizable UI in React/Next.js
- **Turborepo** with pnpm and workspaces
- A structure ready to scale and customize

---

## 🚀 Features

- UI based on [shadcn/ui](https://ui.shadcn.com/)
- Headless backend with [Payload CMS](https://payloadcms.com/)
- Monorepo managed with [Turborepo](https://turbo.build/) to orchestrate and optimize multiple apps and packages
- Support for TypeScript, ESLint, Prettier
- E2E and integration tests (Playwright, Vitest)
- Docker and Docker Compose ready for development and deployment

---

## 📦 Project structure

```
apps/
  payload-web/      # Payload + Frontend (Next.js + Payload CMS)
packages/
  core/             # Payload logic and models
  ui/               # Reusable shadcn/ui components
  shared-types/     # Shared TypeScript types
```

---

## 🛠️ Installation

```bash
git clone https://github.com/aledepaoligampel/turborepo-payload-shadcn.git
cd turborepo-payload-shadcn
pnpm install
```

---

## 🏃 Usage

- **Development:**
  ```bash
  pnpm dev
  ```
- **Tests:**
  ```bash
  pnpm test
  ```
- **Production:**
  ```bash
  pnpm build
  pnpm start
  ```

---

## 📚 Main libraries

- [Payload CMS](https://payloadcms.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Next.js](https://nextjs.org/)
- [Turborepo](https://turbo.build/)
- [pnpm](https://pnpm.io/)
- [Playwright](https://playwright.dev/)
- [Vitest](https://vitest.dev/)

---

## ⚙️ Customization

- Modify components in `packages/ui`
- Add or edit collections in `packages/core/src/collections`
- Configure Payload in `apps/client-template/src/payload.config.ts`
- Adjust global styles in `packages/ui/src/styles/globals.css`

---

## 📝 Notes

- The Payload admin is available in English and Spanish, and you can configure multilingual fields.
- The monorepo is ready to scale and add more apps or packages.
- Includes ESLint and Prettier configuration to keep the code clean.

---

## 🙌 Credits

- Inspired by the Payload and shadcn/ui communities
- Created by [@aledepaoligampel](https://github.com/aledepaoligampel)

---

## 📄 License

MIT
