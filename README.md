# A liquidator bot for TBTC

## Configuration

See config.json file and set one environment variable `TBTC_PKEY` which holds your private key.


## seeker.js

The script scans all contracts and verify if they are undercollateralized, in such case it will attempt to liquidate it.
