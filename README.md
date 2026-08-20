# VERIFIEDFXFX

Premium books and courses platform.

## Run locally
1. Install Node.js 20+.
2. Run `npm install`.
3. Copy `.env.example` to `.env.local`.
4. Add your PostgreSQL and Paystack credentials.
5. Run `npm run dev`.
6. Open http://localhost:3000.

## Current starter
This first version contains the branded responsive UI, homepage, books, courses, pricing, dashboard and admin shell.

## Next production integrations
- PostgreSQL + Prisma
- Secure authentication
- Paystack payment initialization + verification + webhooks
- Protected book/video storage
- Admin CRUD
- Real subscription lifecycle
- User/course progress persistence

Never commit secret API keys to source control.
