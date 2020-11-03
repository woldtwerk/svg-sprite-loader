Fork of https://github.com/mayako21126/svg-sprite-loader/tree/add-support-webpack5

Go there for readme.

All this does is fix `Cannot find module '../runtime/browser-sprite.build'` Error.

With webpack 5 `browser-sprite.build.js` and `sprite.build.js` were missing from `svg-sprite-loader/lib`. Not sure why, but I just modified the paths to use the ones from `svg-baker-runtime` instead.
