```
> yarn
> yarn start
TypeError: index.js: Duplicate declaration "object"
  1 | export default class {
> 2 |   method ({ ...object }) {}
    |                ^
  3 | }
  4 |
    at File.buildCodeFrameError (issue-babel-env-duplicate/node_modules/@babel/core/lib/transformation/file/file.js:209:12)
    at Scope.checkBlockScopedCollisions (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/scope/index.js:303:27)
    at Scope.registerBinding (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/scope/index.js:485:16)
    at Scope.registerDeclaration (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/scope/index.js:404:14)
    at Object.BlockScoped (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/scope/index.js:146:28)
    at Object.newFn (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/visitors.js:266:17)
    at NodePath._call (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/path/context.js:64:19)
    at NodePath.call (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/path/context.js:34:14)
    at NodePath.visit (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/path/context.js:99:12)
    at TraversalContext.visitQueue (issue-babel-env-duplicate/node_modules/@babel/traverse/lib/context.js:139:18)
```
