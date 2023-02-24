# Frog spotting app


## Getting started


1. Start the dev server. And open http://localhost:3000 in your browser.

```
  yarn dev
```

2. Build your product.

```
  yarn prod
```

## Dependencies

- React
- Vite
- Typescript 
- eslint
- Prettier

## Performance

- fast dev server

```bash
$ yarn dev
yarn run v1.22.17
$ vite
                                                                                                                                                                                           16:58:10
  vite v2.8.6 dev server running at:

  > Local: http://localhost:3000/                                                                                                                                                          16:58:10
  > Network: use --host to expose                                                                                                                                                          16:58:10
                                                                                                                                                                                           16:58:10
  ready in 776ms.
```

- fast build speed

```bash
$ yarn prod               
yarn run v1.22.17
$ vite build
vite v2.8.6 building for production...                                                                                                                                                                                                                         21:57:44
✓ 37 modules transformed.                                                                                                                                                                                                                                      21:57:45
dist/public/index.html           0.55 KiB                                                                                                                                                                                                                      21:57:45
dist/assets/index.f377a083.js    2.09 KiB / gzip: 1.13 KiB                                                                                                                                                                                                     21:57:45
dist/assets/vendor.5ad169fc.js   136.42 KiB / gzip: 44.42 KiB                                                                                                                                                                                                  21:57:45
✨  Done in 2.22s.
```

- Type checking by [vite-plugin-checker](https://www.npmjs.com/package/vite-plugin-checker)
