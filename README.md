This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), ready server pushing.

## Getting Started

First, run the development server:

```bash
npm i
# or
yarn install

# Than start the server
npm run dev
# or
yarn dev

# For build use 
next build
```

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Don't forget change .ENV logs !!!

```bash
EMAIL_USER=email of the shop
EMAIL_PASS=password
```

All emails send to `admin@syntrade-kazan.msk0.ru` only. You can change it on `route.ts` file

## Goods

You can find all goods data in the `data/products.json` and images in global folder `public/images`

## Learn More about next and deployment

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
