<p align="center">
  <img src="favicon.svg" width=64 height=64 alt=Bassin>
  <br>
  <br>
  A zero-fee Bitcoin solo mining pool for Umbrel.
  <br>
  Run your own <a href="https://bitbucket.org/ckolivas/ckpool-solo/src/solobtc/">ckPool</a> at home.
</p>


### Install

1. Add `Bassin` repository to your Umbrel Community App Store
  * Open the Umbrel App Store
  * Click dots on the right
  * Click *Community App Stores*
  * Enter `https://github.com/duckaxe/bassin`, click *Add*
  * Open *duckaxe Community App Store*
2. Click the `Bassin` app to initialize the install
3. Open the `Bassin` app, then follow the on-screen instructions
4. Find the Bitcoin block 🎉


### Wiki

* [FAQ](https://github.com/duckaxe/bassin/wiki/FAQ)


### Repositories

* https://github.com/duckaxe/bassin-ui
* https://github.com/duckaxe/ckpool-solo
* https://github.com/duckaxe/umbrel-bassin-widget
* https://github.com/getumbrel/umbrel-apps/tree/master/bassin


### Dataflow

```mermaid
flowchart LR
  C@{ shape: notch-pent, label: "ckPool" }
  U@{ shape: notch-rect, label: "Bassin UI" }
  W@{ shape: notch-rect, label: "Bassin Widget" }
  S@{ shape: processes, label: "Webserver" }

  C -- Pool Data --> S
  S -- JSON API --> W
  S -- JSON API --> U
```


### Donations

* `bc1q8w3sx9zlyytlhrj37h7xhgdzemnw0zj5maway4`
* [+wonderfulspring37](https://paynym.rs/+wonderfulspring37)


### Legal

For academic and research purposes only.
