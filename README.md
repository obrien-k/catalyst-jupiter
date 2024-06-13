[Based on BigCommerce Catalyst](https://github.com/bigcommerce/catalyst)

Create a [BigCommerce store](https://bigcommerce.com) and convert it to a sandbox. Create a GitHub repository for testing, and sync this with the result from following the steps on the BigCommerce Catalyst github repo linked above.

This is the default state of Catalyst and you should connect your test store during the initialization.

It’s strongly recommended to sync up this directory with a remote git repository at this step as it will serve as your basis for any changes you make.

## Requirements

- Node.js 20+
- `npm` (or `pnpm`/`yarn`)

## Getting started

If this installation of Catalyst was created using the `catalyst` CLI, you should already be connected to a store and can get started immediately by running:

```shell
npm run dev
```

If you want to connect to another store or channel, you can run the setup process again by running:

```shell
npx @bigcommerce/create-catalyst@latest init
```

Learn more about Catalyst at [catalyst.dev](https://catalyst.dev).
