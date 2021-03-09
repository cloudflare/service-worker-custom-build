# 👷 `worker-template` Hello World

## NOTE: You must be using the Custom Builds RC to use this template. Check the [wrangler releases page](https://github.com/cloudflare/wrangler/releases) for more information

A template for kick starting a Cloudflare Workers project using custom builds and webpack

* Worker code is in `src/`. The event handler is in `index.js`, and the `handleRequest` method is in
  `handleRequest.js`, to demonstrate a multi-file project

* The compiled main module is set using the `package.json` `main` field. This should be set to the
  compiled bundle, in this case `dist/worker.js`
