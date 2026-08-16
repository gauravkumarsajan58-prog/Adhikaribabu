# AdhikariBabu

Secure, clean Next.js + Tailwind CSS starter for **Jobs, Results, Admit Card & Study Material**.

## Important upload rule

After extracting this ZIP, upload the **contents of this folder** to the ROOT of your GitHub repository.

Do NOT upload the ZIP itself.

The GitHub root must contain at least:

- `package.json`
- `next.config.mjs`
- `tsconfig.json`
- `next-env.d.ts`
- `postcss.config.mjs`
- `tailwind.config.ts`
- `app/`
- `.gitignore`

## Vercel

Import the GitHub repository in Vercel.

Root Directory: `./` (repository root)

Framework: Next.js

Build command: `next build`

Install command: `npm install`

No database or API key is required for this starter.

## Security

- No passwords, tokens, API keys or secrets are included.
- `.env*` files are ignored by Git.
- Admin/database features should be added later with server-side authentication and environment variables.
- Keep GitHub and Vercel accounts under the owner's own email/account.

## Local development

```bash
npm install
npm run dev
```


## Premium demo

Open `/premium` after deployment to test the Premium UI.

The **Test Premium Access** button is a local demo only. It does not process payments,
create real accounts, or grant server-side access. Real Premium access should later use
secure server-side authentication, a payment provider, and protected routes/data.
