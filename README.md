# SumKupon Desktop

## Installation

**None of these package are signed yet.** Make sure you only download
SumKupon Desktop from this GitHub, and **NOWHERE ELSE**.

### Running in development mode

This runs best with `node v9.8.0` and `electron v1.8.2`

- clone the repo
- run `yarn install` to install the dependencies. **Important: You can only use yarn to install right now as there's two versions of eosjs being pulled in and only yarn supports aliasing**.
- run `npm start` to start the local server with hot-reloading
- run `electron .` or `./node_modules/.bin/electron .` from the directory to start electron.


### Building

- `npm run build`
- `npm run release-mac` or `npm run release-windows` or `npm run release-linux` ( you must build from the target machine )


## Creating Apps for SumKupon and Scatter
### Check out the [Documentation](https://get-scatter.com/docs/examples-interaction-flow)
