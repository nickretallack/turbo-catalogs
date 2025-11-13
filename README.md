# turborepo yarn catalogs repro case

Repro steps:
```
yarn
yarn turbo prune app-a
```
Output:
```
turbo 2.6.1

Generating pruned monorepo for app-a in /Users/nicholas.retallack/experiments/turbo-catalogs/out
 - Added app-a
 - Added pkg-a
 - Added tooling-config
  × Unable to find any locator for lodash@catalog:
```
