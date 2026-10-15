# Price — always-on dashboard

Static web page for the Price iOS app's always-on
desktop dashboard. It is deployed from the app repo with
`Tools/deploy-dashboard.sh`; don't edit files here by hand.

The page holds no portfolio data. The phone publishes an end-to-end encrypted
snapshot to iCloud; the decryption key only exists in the private link's URL
fragment (`#r=…&k=…`), which browsers never send to any server. Live prices
come straight from Binance and CoinGecko.

Manrope is licensed under the SIL Open Font License (see `assets/OFL.txt`).
