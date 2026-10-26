## Remote Compose snapshot probe — androidx.dev build [16718948](https://androidx.dev/snapshots/builds/16718948/artifacts)

Snapshot artifacts last updated `20261025191458`. Compiled: **yes**.

| issue | preview | still byte-identical to the known-broken capture | drawn, by density | measured |
| --- | --- | --- | --- | --- |

A component that lays out correctly occupies the **same dp box at every density**; one whose paint is density-conditional does not. That is the shared signature of #89 and #90, and it is why this table sweeps rather than reporting the one density the sheet declares.

**Components this catalog is waiting for**

| symbol | published in this build | what it unlocks |
| --- | --- | --- |
| [`RemotePickerKt`](https://github.com/yschimke/wear-m3-catalog/issues/95) | not yet | the `Picker` set, 42 published cells the Remote sheet draws none of. It is the largest set still at `—` whose absence is the LIBRARY's rather than this catalog's: the creation layer already publishes everything a picker is built from — `rememberRemoteScrollState(notches)` for the snapping, `RemoteModifier.verticalScroll`, and `scrollTo`/`scrollBy` as recordable actions — so the gap is a Material 3 component on top of them, not a renderer that cannot scroll |

_The symbol is the signal; the link is for reading, not polling — a merged change is not a published artifact._

_This job never claims a bug is fixed — it reports that something moved. `scripts/remote-snapshot-probe.py` explains the limit._
