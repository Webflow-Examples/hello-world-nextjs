# Next.js + Webflow Cloud

Example [Next.js](https://nextjs.org) app for [Webflow Cloud](https://webflow.com/cloud), using the App Router, [OpenNext](https://opennext.js.org) for Cloudflare Workers, and Wrangler. Use it as a starting point or reference when deploying Next.js on Webflow Cloud.

[![Deploy to Webflow](https://webflow.com/img/deploy-dark.svg)](https://webflow.com/dashboard/cloud/deploy?repo=https://github.com/Webflow-Examples/hello-world-nextjs)

## Project structure

```text
.
├── .gitignore
├── public/
│   ├── next.svg
│   └── webflow.svg
├── src/
│   └── app/
│       ├── api/
│       │   └── hello/
│       ├── favicon.ico
│       ├── globals.css
│       ├── layout.tsx
│       └── page.tsx
├── LICENSE
├── cloudflare-env.d.ts
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── open-next.config.ts
├── package.json
├── postcss.config.mjs
├── tsconfig.json
├── webflow.json
└── wrangler.json
```

## Commands

| Command              | Action                                                                                |
| -------------------- | ------------------------------------------------------------------------------------- |
| `npm install`        | Install dependencies                                                                  |
| `npm run dev`        | Start the Next.js dev server (default [http://localhost:3000](http://localhost:3000)) |
| `npm run build`      | Create a production build                                                             |
| `npm run start`      | Run the production server (after `npm run build`)                                     |
| `npm run lint`       | Run ESLint                                                                            |
| `npm run deploy`     | Deploy to Webflow Cloud (`webflow cloud deploy`)                                      |
| `npm run preview`    | Build with OpenNext and run a local Cloudflare preview                                |
| `npm run cf-typegen` | Regenerate Wrangler types into `cloudflare-env.d.ts`                                  |

## Learn more

- [Next.js documentation](https://nextjs.org/docs)
- [Webflow Cloud](https://webflow.com/cloud)
