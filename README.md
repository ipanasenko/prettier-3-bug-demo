# prettier-3-bug-demo

## To reproduce the bug:

- checkout commit `prettier works`
- run `yarn`
- run `npx prettier --check index.js` to verify that it works
- checkout commit `prettier does not work`
- run `yarn`
- run `npx prettier --check index.js` to verify that it does not work
