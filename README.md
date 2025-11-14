<p align="center">
  <img src="favicon.svg" width=64 height=64 alt=Bassin>
  <br>
  <br>
  A zero-fee Bitcoin solo mining pool for <a href="https://apps.umbrel.com/app/bassin">Umbrel</a>.
  <br>
  Run your own ckPool at home.
</p>


### Install

1. Install `Bassin` directly from the Umbrel App Store
2. Open the `Bassin` app, then follow the on-screen instructions
3. Find the Bitcoin block 🎉


> [!NOTE]
> Bassin is now available in the official Umbrel App Store.<br>
> The Community Edition will no longer be under active development.


### Wiki

* [FAQ](https://github.com/duckaxe/bassin/wiki/FAQ)


### Repositories

* https://github.com/getumbrel/umbrel-apps/tree/master/bassin
* https://github.com/duckaxe/bassin-ui
* https://github.com/duckaxe/umbrel-bassin-widget
* https://hub.docker.com/r/pinkyswear/ckpool-solo


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
