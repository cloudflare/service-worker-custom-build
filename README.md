# 👷 `worker-template` Hello World

## NOTE: You must be using wrangler 1.16 or newer to use this template

A template for kick starting a Cloudflare Workers project using custom builds and webpack

* Worker code is in `src/`. The event handler is in `index.js`, and the `handleRequest` method is in
  `handleRequest.js`, to demonstrate a multi-file project

* The compiled main module is set using the `package.json` `main` field, as it is with other
  `type = "javascript"` service-worker projects. This should be set to the compiled bundle,
  in this case `dist/worker.js`.
