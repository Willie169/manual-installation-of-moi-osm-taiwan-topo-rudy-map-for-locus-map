## 手動安裝魯地圖於 Locus Map / Manual Installation of MOI OSM Taiwan TOPO Rudy Map for Locus Map

注意：這是手動安裝的教學，適用於因隱私考量或其他原因不想要 Locus Map 取得網路連線或其他想要手動安裝的人。對於大多數人，自動安裝是更方便的選項，你可以前往 Google Play Store 並安裝 [Locus Map](https://play.google.com/store/apps/details?id=menion.android.locus)，接著前往 <https://rudymap.tw>、<https://moi.kcwu.csie.org/taiwan_topo.html> 或 <https://map.happyman.idv.tw/rudy/taiwan_topo.html> 並點擊自動安裝下的連結。自動安裝時 Locus Map 需要網路連線。

Caution: This is manual installation instruction designed for people who do not want Locus Map to have internet connection due to privacy consideration or other reasons or other people who want to manually install it. For most people, automatic installation is a more convenient option, you can go to Google Play Store and install [Locus Map](https://play.google.com/store/apps/details?id=menion.android.locus), and then go to <https://rudymap.tw>, <https://moi.kcwu.csie.org/taiwan_topo.html>, or <https://map.happyman.idv.tw/rudy/taiwan_topo.html> and click links under 自動安裝 (automatic installation). Locus Map needs internet connection during automatic installation.

### 中文繁體

<ol>
<li>前往 Google Play Store 並安裝 <a href="https://play.google.com/store/apps/details?id=menion.android.locus">Locus Map</a>。</li>
<li>如果你想要並知道怎麼做，你可以在安裝後立即通過 VPN 應用程式、root 或 GrapheneOS 等第三方 ROM 的選項停用 Locus Map 的網路連線權限。如果你不知道它代表什麼，請跳過這個步驟。</li>
<li>前往 <a href="https://rudymap.tw">https://rudymap.tw</a>、<a href="https://moi.kcwu.csie.org/taiwan_topo.html">https://moi.kcwu.csie.org/taiwan_topo.html</a> 或 <a href="https://map.happyman.idv.tw/rudy/taiwan_topo.html">https://map.happyman.idv.tw/rudy/taiwan_topo.html</a>，在 Mapsforge 手動下載自行安裝下，下載：（如果自動分流下載失敗，請點擊一個 mirror）<ul>
<li>Map：你會獲得 <code>MOI_OSM_Taiwan_TOPO_Rudy.map.zip</code>。解壓縮它。</li>
<li>Locus Style：你會獲得 <code>MOI_OSM_Taiwan_TOPO_Rudy_locus_style.zip</code>。解壓縮它。</li>
<li>DEM mix：你會獲得 <code>hgtmix.zip</code>。解壓縮它。</li>
</ul>
</li>
<li>透過 Shizuku、Termux 或電腦前往 ADB shell。對於 Shizuku，推薦使用 <a href="https://github.com/thedjchi/Shizuku">thedjchi 的 Shizuku 分支</a>。如果你想要中文指引，請參考 <a href="https://ivonblog.com/posts/android-shizuku">Ivon的部落格</a>。</li>
<li>在 ADB shell 中，執行以下命令：<pre><code>cp -r /storage/emulated/0/Download/moi_osm_taiwan_topo_rudy.map /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector
cp -r /storage/emulated/0/Download/MOI_OSM_Taiwan_TOPO_Rudy_style /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector/_themes
cp /storage/emulated/0/Download/hgtmix/* /storage/emulated/0/Android/data/menion.android.locus/files/Locus/data/srtm
</code></pre></li>
<li>打開 Locus Map。<ol>
<li>點擊左下角的雙菱形按鈕。</li>
<li>點擊左側選單中地圖下的 LoMaps Online。</li>
<li>點擊智慧型選擇 - 離線下的 MOI OSM Taiwan TOPO Rudy。</li>
</ol>
</li>
</ol>

雜項：
- 點擊左下角的三橫線按鈕，上滑， 點擊設定，即可進入設定。
- 以上假設 Locus Map 主目錄為 'Android/data'中的私人資料夾，即 `/storage/emulated/0/Android/data/menion.android.locus`，即 Locus Map 預設行為。若你在 Locus Map 應用程式內設定 > 備份 & 檔案系統 > 檔案系統管理器 > 設定主目錄選擇的是 'Android/media'中的私人資料夾，則須將以上命令中的 `/storage/emulated/0/Android/data/menion.android.locus` 改為 `/storage/emulated/0/Android/media/menion.android.locus`。
- 語言和單位可在 Locus Map 應用程式內設定 > 語言 & 單位中調整。臺灣的常用單位為公制距離、攝氏溫度和公斤重量。

### English

<ol>
<li>Go to Google Play Store and install <a href="https://play.google.com/store/apps/details?id=menion.android.locus">Locus Map</a>.</li>
<li>If you want and know how to do, you can disable the network connection permission of Locus Map immediately after installation through a VPN app, root, or options of third-party ROMs such as GrapheneOS. Skip this step if you don't know what it means.</li>
<li>Go to <a href="https://rudymap.tw">https://rudymap.tw</a>, <a href="https://moi.kcwu.csie.org/taiwan_topo.html">https://moi.kcwu.csie.org/taiwan_topo.html</a>, or <a href="https://map.happyman.idv.tw/rudy/taiwan_topo.html">https://map.happyman.idv.tw/rudy/taiwan_topo.html</a>, under Mapsforge 手動下載自行安裝 (manual download and install by yourself), download: (click a mirror if 自動分流 (automatic traffic splitting) doesn&#39;t work)<ul>
<li>Map: You will get <code>MOI_OSM_Taiwan_TOPO_Rudy.map.zip</code>. Extract it.</li>
<li>Locus Style: You will get <code>MOI_OSM_Taiwan_TOPO_Rudy_locus_style.zip</code>. Extract it.</li>
<li>DEM mix: You will get <code>hgtmix.zip</code>. Extract it.</li>
</ul>
</li>
<li>Go to ADB shell via Shizuku, Termux or PC. For Shizuku, it is recommended to use <a href="https://github.com/thedjchi/Shizuku">thedjchi&#39;s fork of Shizuku</a>. Refer to <a href="https://ivonblog.com/posts/android-shizuku">Ivon's Blog</a> if you want guide in Chinese.</li>
<li>Inside ADB shell, execute the following commands:<pre><code>cp -r /storage/emulated/0/Download/moi_osm_taiwan_topo_rudy.map /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector
cp -r /storage/emulated/0/Download/MOI_OSM_Taiwan_TOPO_Rudy_style /storage/emulated/0/Android/data/menion.android.locus/files/Locus/mapsVector/_themes
cp /storage/emulated/0/Download/hgtmix/* /storage/emulated/0/Android/data/menion.android.locus/files/Locus/data/srtm
</code></pre></li>
<li>Open Locus Map.<ol>
<li>Press the double diamond button in the lower left corner.</li>
<li>Click LoMaps Online under Maps in the left menu.</li>
<li>Click MOI OSM Taiwan TOPO Rudy under Smart choice - Offline.</li>
</ol>
</li>
</ol>

Miscellaneous:
- In Locus Map app, click the three-line button in the lower left corner, scroll up, and click Settings to enter Settings.
- It is assumed above that the main directory of Locus Map is Private folder in 'Android/data', that is, `/storage/emulated/0/Android/data/menion.android.locus`, which is the default behavior of Locus Map. If you choose Private folder in 'Android/media' in Settings > Backup & filesystem > File system manager > Set the main directory in Locus Map app, then you need to replace `/storage/emulated/0/Android/data/menion.android.locus` in the commands above with `/storage/emulated/0/Android/media/menion.android.locus`.
- Language and units can be adjusted in Settings > Language & Units in Locus Map app. The commonly used units in Taiwan are metric distance, Celsius temperature, and kilogram weight.

### 來源 / Sources

- <https://rudymap.tw>
- <https://moi.kcwu.csie.org/taiwan_topo.html>
- <https://map.happyman.idv.tw/rudy/taiwan_topo.html>
- <https://www.facebook.com/groups/taiwan.topo/permalink/703483796473903>
- <https://play.google.com/store/apps/details?id=menion.android.locus>
