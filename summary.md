## Remote Compose snapshot probe — androidx.dev build [16647424](https://androidx.dev/snapshots/builds/16647424/artifacts)

Snapshot artifacts last updated `20261019071822`. Compiled: **yes**.

**Why this is being reported**

- 93 render(s) changed, 0 added, 0 removed

| issue | preview | still byte-identical to the known-broken capture | drawn, by density | measured |
| --- | --- | --- | --- | --- |

A component that lays out correctly occupies the **same dp box at every density**; one whose paint is density-conditional does not. That is the shared signature of #89 and #90, and it is why this table sweeps rather than reporting the one density the sheet declares.

**Components this catalog is waiting for**

| symbol | published in this build | what it unlocks |
| --- | --- | --- |
| [`RemotePickerKt`](https://github.com/yschimke/wear-m3-catalog/issues/95) | not yet | the `Picker` set, 42 published cells the Remote sheet draws none of. It is the largest set still at `—` whose absence is the LIBRARY's rather than this catalog's: the creation layer already publishes everything a picker is built from — `rememberRemoteScrollState(notches)` for the snapping, `RemoteModifier.verticalScroll`, and `scrollTo`/`scrollBy` as recordable actions — so the gap is a Material 3 component on top of them, not a renderer that cannot scroll |

_The symbol is the signal; the link is for reading, not polling — a merged change is not a published artifact._

<details><summary>Renders that changed since the previous probe</summary>

- `ChildRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_extra_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_extra_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_extra_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_extra_large`
- `ChildRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_large`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_child`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_child_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_outlined`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_outlined_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_tonal`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_tonal_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_child`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_child_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_outlined`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_tonal`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_tonal_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_child`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_child_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_outlined`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_tonal`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_tonal_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_child`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_child_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_outlined`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_outlined_icon_only`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_tonal`
- `CompactRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_tonal_icon_only`
- `InteractivePageIndicatorRemote_192dp`
- `InteractivePageIndicatorRemote_204dp`
- `InteractivePageIndicatorRemote_216dp`
- `InteractivePageIndicatorRemote_225dp`
- `InteractivePageIndicatorRemote_240dp`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_child`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_child_icon_extra_la`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_child_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_extra_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_outlined`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_outlined_icon_extra`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_outlined_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_240`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_child`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_child_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_extra_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_outlined`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_child`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_child_icon_extra_la`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_child_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_extra_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_outlined`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_outlined_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_child`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_child_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_extra_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_large`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_outlined`
- `LoadingRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_outlined_icon_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_extra_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_extra_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_extra_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_extra_large`
- `OutlinedRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_extra_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_160_VARIANT_icon_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_extra_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_240_VARIANT_icon_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_extra_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_320_VARIANT_icon_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_extra_large`
- `TonalRemoteButton_width_227dp_height_100dp_dpi_480_VARIANT_icon_large`

</details>

_This job never claims a bug is fixed — it reports that something moved. `scripts/remote-snapshot-probe.py` explains the limit._
