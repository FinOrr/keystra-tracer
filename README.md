# Keystra Tracer

A lightweight requirements tracing tool. Track intents, requirements, verifications, and runs. See coverage at a glance through a live trace matrix.

**Use the app at [?](https://?)**, no setup needed.

---

## Tech stack

- [Next.js 14](https://nextjs.org) (App Router)
- [Supabase](https://supabase.com) (auth + database)
- TypeScript

## Running locally

```bash
npm install
# add your Supabase credentials to .env.local
npm run dev
```

Apply the database schema with the migration in `supabase/migrations/`.

## License

[MIT](LICENSE)
