## Steps
```
yarn
yarn build
node .output/server/index.mjs
```

## Result (after first http request)

```
Listening on http://localhost:3000
Server Side Rendering Error: TypeError: Invalid value used as weak map key
  at WeakMap.set (<anonymous>)
  at normalizePropsOptions (file:///webpack-components-issue/.output/server/chunks/index.mjs:4257:11)
  at createComponentInstance$1 (file:///webpack-components-issue/.output/server/chunks/index.mjs:6995:23)
  at renderComponentVNode (file:///webpack-components-issue/.output/server/chunks/index.mjs:9124:22)
  at ssrRenderComponent (file:///webpack-components-issue/.output/server/chunks/index.mjs:9460:12)
  at ssrRender (file:///webpack-components-issue/.output/server/chunks/app/811.mjs:61:49)
  at renderComponentSubTree (file:///webpack-components-issue/.output/server/chunks/index.mjs:9190:13)
  at renderComponentVNode (file:///webpack-components-issue/.output/server/chunks/index.mjs:9141:16)
  at renderVNode (file:///webpack-components-issue/.output/server/chunks/index.mjs:9231:22)
  at renderVNode (file:///webpack-components-issue/.output/server/chunks/index.mjs:9237:17)
```