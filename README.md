run with `yarn dev`

Output:

```
Error: Cannot find module 'react-dom/server'
Require stack:
- /Users/james/src/rnd/resend-node-test/node_modules/@react-email/render/dist/node/index.js
- /Users/james/src/rnd/resend-node-test/node_modules/resend/dist/index.js
- /Users/james/src/rnd/resend-node-test/index.ts
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:1048:15)
    at Function.Module._resolveFilename.sharedData.moduleResolveFilenameHook.installedValue [as _resolveFilename] (/Users/james/src/rnd/resend-node-test/node_modules/@cspotcode/source-map-support/source-map-support.js:811:30)
    at Function.Module._load (node:internal/modules/cjs/loader:901:27)
    at Module.require (node:internal/modules/cjs/loader:1115:19)
    at require (node:internal/modules/helpers:130:18)
    at Object.<anonymous> (/Users/james/src/rnd/resend-node-test/node_modules/@react-email/render/dist/node/index.js:74:30)
    at Module._compile (node:internal/modules/cjs/loader:1241:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1295:10)
    at Object.require.extensions.<computed> [as .js] (/Users/james/src/rnd/resend-node-test/node_modules/ts-node/src/index.ts:1608:43)
    at Module.load (node:internal/modules/cjs/loader:1091:32) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/Users/james/src/rnd/resend-node-test/node_modules/@react-email/render/dist/node/index.js',
    '/Users/james/src/rnd/resend-node-test/node_modules/resend/dist/index.js',
    '/Users/james/src/rnd/resend-node-test/index.ts'
  ]
}
```
