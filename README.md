# [ag-yarn-pnp-issue-repro](https://github.com/ag-grid/ag-grid/issues/5623)
Repro for ag-grid/ag-grid#5623 with ag-enterprise &amp; yarn PnP 

## Steps

1. Run `git clone https://github.com/aateeque/ag-yarn-pnp-issue-repro.git`
2. Run `yarn`
3. Run `yarn workspace ag-demo start`- you'll get the AG-grid demo in browser
4. Switch to `init-AGe` branch
5. Run `yarn workspace ag-demo start`- you'll get error `Can't resolve 'ag-grid-community' `
6. Switch to branch `workaround`
7. Run `yarn workspace ag-demo start`- works!
