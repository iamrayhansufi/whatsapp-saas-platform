# WhatsApp Business API SaaS Platform (Next.js + shadcn/ui)

A multi-tenant SaaS starter for WhatsApp Business API, with authentication, dashboard, and message sending, styled using [shadcn/ui](https://ui.shadcn.com/).

## Features

- Next.js (TypeScript)
- shadcn/ui React components
- Prisma/PostgreSQL multi-tenant DB
- NextAuth authentication
- WhatsApp Business API integration
- Dashboard, login, and message sending UIs
- Simple, extensible codebase

## Getting Started

1. **Clone & Install**
    ```bash
    git clone https://github.com/iamrayhansufi/whatsapp-saas-platform.git
    cd whatsapp-saas-platform
    yarn install
    ```

2. **Configure Environment**
    - Copy `.env.example` to `.env` and fill in your DATABASE_URL and WhatsApp credentials.

3. **Prisma Migration**
    ```bash
    npx prisma migrate dev --name init
    ```

4. **Run Dev Server**
    ```bash
    yarn dev
    ```

## UI Library

- Uses [shadcn/ui](https://ui.shadcn.com/) for beautiful, accessible components.

## Next Steps

- Add WhatsApp number management, analytics, automation
- Integrate payments for SaaS billing
- Harden security and add email verification

---