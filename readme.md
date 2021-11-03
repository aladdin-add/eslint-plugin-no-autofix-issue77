# an example to use eslint-plugin-no-autofix

## Usage

```bash
$ npm run lint -- --fix
/Users/weiran/repo/github/no-autofix-issue77/lib/index.js
  2:7   warning  'x' is assigned a value but never used                                 @typescript-eslint/no-unused-vars
  2:10  error    Array type using 'Array<string>' is forbidden. Use 'string[]' instead  no-autofix/@typescript-eslint/eslint-plugin/array-type

/Users/weiran/repo/github/no-autofix-issue77/tests/lib/index.js
  3:16  error  Require statement not part of import statement  @typescript-eslint/no-var-requires
  4:13  error  Require statement not part of import statement  @typescript-eslint/no-var-requires

✖ 4 problems (3 errors, 1 warning)
```