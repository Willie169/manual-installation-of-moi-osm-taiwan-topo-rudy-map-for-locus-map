# Manual Installation of MOI OSM Taiwan TOPO Rudy Map for Locus Map

## English

1. Go to Google Play Store and install [Locus Map](https://play.google.com/store/apps/details?id=menion.android.locus).
2. Go to <https://rudymap.tw>, under Mapsforge 手動下載自行安裝, download (click a mirror if 自動分流 doesn't work):
  - Map: You will get `MOI_OSM_Taiwan_TOPO_Rudy.map.zip`. Extract it.
  - Locus Style: You will get `MOI_OSM_Taiwan_TOPO_Rudy_locus_style.zip`. Extract it.
  - DEM mix: You will get `hgtmix.zip`. Extract it.
3. Go to ADB shell via Shizuku, Termux or PC. [thedjchi's fork of Shizuku](https://github.com/thedjchi/Shizuku) is recommended. Refer to [Ivon的部落格](https://ivonblog.com/posts/android-shizuku) for guides in Chinese.
4. Inside ADB shell, run
  ```
  cp -r /storage/emulated/0/Download/moi_osm_taiwan_topo_rudy.map /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector
  cp -r /storage/emulated/0/Download/MOI_OSM_Taiwan_TOPO_Rudy_style /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector/_themes
  cp /storage/emulated/0/Download/hgtmix/* /storage/emulated/0/Android/data/menion.android.locus/files/Locus/data/srtm
  ```
5. Open Locus Map.
  1. Press the double diamond button in the lower left corner.
  2. Click LoMaps Online under Maps in the left menu.
  3. Click MOI OSM Taiwan TOPO Rudy.

## 中文繁體

1. 前往 Google Play Store 並安裝 [Locus Map](https://play.google.com/store/apps/details?id=menion.android.locus)。
2. 前往 <https://rudymap.tw>，在 Mapsforge 手動下載自行安裝下，下載（如果自動分流無效，點擊一個 mirror）：
  - Map：你會獲得 `MOI_OSM_Taiwan_TOPO_Rudy.map.zip`。解壓縮它。
  - Locus Style：你會獲得 `MOI_OSM_Taiwan_TOPO_Rudy_locus_style.zip`。解壓縮它。
  - DEM mix：你會獲得 `hgtmix.zip`。解壓縮它。
3. 通過 Shizuku、Termux 或電腦前往 ADB shell。推薦使用 [thedjchi 的 Shizuku 分支](https://github.com/thedjchi/Shizuku)。對於中文教學，參考 [Ivon的部落格](https://ivonblog.com/posts/android-shizuku)。
4. 在 ADB shell 中，執行：
  ```
  cp -r /storage/emulated/0/Download/moi_osm_taiwan_topo_rudy.map /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector
  cp -r /storage/emulated/0/Download/MOI_OSM_Taiwan_TOPO_Rudy_style /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector/_themes
  cp /storage/emulated/0/Download/hgtmix/* /storage/emulated/0/Android/data/menion.android.locus/files/Locus/data/srtm
  ```
5. 打開 Locus Map。
  1. 點擊左下角的雙菱形按鈕。
  2. 點擊左側選單中 Maps 下的 LoMaps Online。
  3. 點擊 MOI OSM Taiwan TOPO Rudy。
