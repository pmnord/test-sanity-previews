# sanity-template-nextjs

This is a template for new projects using Next.js with embedded Sanity integration and Sanity Studio
on the `/studio` route.

## Features

- Live previews using `next-sanity`
- Customized Sanity Desk Tool

### Initialize project

```sh
# Install dependencies
pnpm install

# Create a Sanity project ID and dataset and write to `.env.local`
pnpm exec sanity init --env .env.local

# Start development server
pnpm dev
```

[vercel-deploy]: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmariuslundgard%2Fsanity-template-nextjs&repository-name=sanity-template-nextjs&project-name=sanity-template-nextjs&demo-title=Next.js%20with%20Sanity&demo-description=A%20Sanity-powered%20Next.js%20app%20with%20instant%20previews&demo-url=https%3A%2F%2Fsanity-template-nextjs-delta.vercel.app%2F%2F%3Futm_source%3Dvercel%26utm_medium%3Dreferral&demo-image=https%3A%2F%2Fuser-images.githubusercontent.com%2F406933%2F211022598-9b541676-fa68-4618-8a56-92381e075260.png&integration-ids=oac_hb2LITYajhRQ0i4QznmKH7gx&external-id=nextjs%3Btemplate%3Dsanity-template-nextjs
