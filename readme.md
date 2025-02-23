<p align="center">
  <a><img src="https://etherscan.io/images/logo-ether.png?v=0.0.2" title="Logo" width="400"/></a>
</p>
<p align="center">
  <b>
    Etherscan Labels
  </b>
  <br>
  <i>A public dataset of <a href="https://etherscan.io/labelcloud">Etherscan labels</a></i>
  <br>
</p>

<br/>

| Label                              | CSV                                  | JSON                                   | Updated      |
| ---------------------------------- | ------------------------------------ | -------------------------------------- | ------------ |
| `exchange` (Centralized Exchanges) | [View CSV](./src/cex-addresses.csv)  | [View JSON](./src/cex-addresses.json)  | May 9, 2022  |
| `phish-hack` (Phishing/Hacking)    | [View CSV](./src/hack-addresses.csv) | [View JSON](./src/hack-addresses.json) | May 15, 2022 |

<br/>

## Contributing

Each label is currently pulled with custom scripts. Partially documented, partially not.

### Phish / Hack addresses

1. install [tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?utm_source=chrome-ntp-icon)
2. copy userscript to tampermonkey extension
3. open the URL `https://etherscan.io/accounts/label/phish-hack?subcatid=undefined&size=100&start=0&col=1&order=asc`. only support size = 100
4. open the chrome dev tool. copy log to `hack-addresses.json`

> Pulled from [Etherscan's "Phish / Hack" label](https://etherscan.io/accounts/label/phish-hack?subcatid=undefined&size=100&start=0&col=1&order=asc) last on May 15, 2022

- **[View the JSON](./src/hack-addresses.json)**

## Install

> TODO
