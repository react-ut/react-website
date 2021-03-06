1.0.0 / 19.12.2017
==================

  * (breaking change) Renamed `react-isomorphic-render` to `react-website` since the project outgrew its initial name and it's now more about building a React application rather than just isomorphic React rendering.
  * (breaking change) Dropped old React support, now supports React >= 16 only.
  * (breaking change) Removed `koa` entirely (for simplicity).
  * (breaking change) Added `secure` flag to page rendering service options for HTTPS.
  * (breaking change) `wrapper` parameter renamed to `container`.
  * (breaking change) `preload` reducer is now added by default and "preload" reducer name is now reserved for it. `<Loading/>` component is also now built-in into the library and can be `import`ed from it.
  * (breaking change) Removed `request` from rendering service `initialize()` parameters (may be added back, upon request).
  * (breaking change) Removed `loading` from rendering service parameters (seems that it was never used).
  * (breaking change) `render: false` parameter renamed to `hollow: true`.
  * `reduxEventNaming` and `reduxPropertyNaming` are now set by default.
  * (breaking change) `@preload()` now doesn't automatically convert `Array`s into `Promise.all(array)`.
  * (breaking change) `@preload()` `helpers` removed (may be added back upon request).
  * (breaking change) Removed `{ preload: { client } }` configuration parameter.
