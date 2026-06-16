## 手動安裝 MOI OSM Taiwan TOPO Rudy Map（魯地圖）於 Locus Map / Manual Installation of MOI OSM Taiwan TOPO Rudy Map for Locus Map

### 中文繁體

<ol>
<li>前往 Google Play Store 並安裝 <a href="https://play.google.com/store/apps/details?id=menion.android.locu">Locus Map</a>。</li>
<li>前往 <a href="https://rudymap.tw">https://rudymap.tw</a>，在 Mapsforge 手動下載自行安裝下，下載（如果自動分流無效，點擊一個 mirror）：<ul>
<li>Map：你會獲得 <code>MOI_OSM_Taiwan_TOPO_Rudy.map.zip</code>。解壓縮它。</li>
<li>Locus Style：你會獲得 <code>MOI_OSM_Taiwan_TOPO_Rudy_locus_style.zip</code>。解壓縮它。</li>
<li>DEM mix：你會獲得 <code>hgtmix.zip</code>。解壓縮它。</li>
</ul>
</li>
<li>通過 Shizuku、Termux 或電腦前往 ADB shell。推薦使用 <a href="https://github.com/thedjchi/Shizuku">thedjchi 的 Shizuku 分支</a>。對於中文教學，參考 <a href="https://ivonblog.com/posts/android-shizuku">Ivon的部落格</a>。</li>
<li>在 ADB shell 中，執行：<pre><code>cp -r <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Download<span class="hljs-regexp">/moi_osm_taiwan_topo_rudy.map /</span>storage<span class="hljs-regexp">/emulated/</span><span class="hljs-number">0</span><span class="hljs-regexp">/Android/</span>data<span class="hljs-regexp">/menion.android.locus/</span>files<span class="hljs-regexp">/Locus/</span>mapsVector
cp -r <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Download<span class="hljs-regexp">/MOI_OSM_Taiwan_TOPO_Rudy_style /</span>storage<span class="hljs-regexp">/emulated/</span><span class="hljs-number">0</span><span class="hljs-regexp">/Android/</span>data<span class="hljs-regexp">/menion.android.locus/</span>files<span class="hljs-regexp">/Locus/</span>mapsVector/_themes
cp <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Download<span class="hljs-regexp">/hgtmix/</span>* <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Android<span class="hljs-regexp">/data/</span>menion.android.locus<span class="hljs-regexp">/files/</span>Locus<span class="hljs-regexp">/data/</span>srtm
</code></pre></li>
<li>打開 Locus Map。<ol>
<li>點擊左下角的雙菱形按鈕。</li>
<li>點擊左側選單中 Maps 下的 LoMaps Online。</li>
<li>點擊 MOI OSM Taiwan TOPO Rudy。</li>
</ol>
</li>
</ol>

### English

<ol>
<li>Go to Google Play Store and install <a href="https://play.google.com/store/apps/details?id=menion.android.locus">Locus Map</a>.</li>
<li>Go to <a href="https://rudymap.tw">https://rudymap.tw</a>, under Mapsforge 手動下載自行安裝, download (click a mirror if 自動分流 doesn&#39;t work):<ul>
<li>Map: You will get <code>MOI_OSM_Taiwan_TOPO_Rudy.map.zip</code>. Extract it.</li>
<li>Locus Style: You will get <code>MOI_OSM_Taiwan_TOPO_Rudy_locus_style.zip</code>. Extract it.</li>
<li>DEM mix: You will get <code>hgtmix.zip</code>. Extract it.</li>
</ul>
</li>
<li>Go to ADB shell via Shizuku, Termux or PC. <a href="https://github.com/thedjchi/Shizuku">thedjchi&#39;s fork of Shizuku</a> is recommended. Refer to <a href="https://ivonblog.com/posts/android-shizuku">Ivon的部落格</a> for guides in Chinese.</li>
<li>Inside ADB shell, run<pre><code>cp -r <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Download<span class="hljs-regexp">/moi_osm_taiwan_topo_rudy.map /</span>storage<span class="hljs-regexp">/emulated/</span><span class="hljs-number">0</span><span class="hljs-regexp">/Android/</span>data<span class="hljs-regexp">/menion.android.locus/</span>files<span class="hljs-regexp">/Locus/</span>mapsVector
cp -r <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Download<span class="hljs-regexp">/MOI_OSM_Taiwan_TOPO_Rudy_style /</span>storage<span class="hljs-regexp">/emulated/</span><span class="hljs-number">0</span><span class="hljs-regexp">/Android/</span>data<span class="hljs-regexp">/menion.android.locus/</span>files<span class="hljs-regexp">/Locus/</span>mapsVector/_themes
cp <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Download<span class="hljs-regexp">/hgtmix/</span>* <span class="hljs-regexp">/storage/</span>emulated<span class="hljs-regexp">/0/</span>Android<span class="hljs-regexp">/data/</span>menion.android.locus<span class="hljs-regexp">/files/</span>Locus<span class="hljs-regexp">/data/</span>srtm
</code></pre></li>
<li>Open Locus Map.<ol>
<li>Press the double diamond button in the lower left corner.</li>
<li>Click LoMaps Online under Maps in the left menu.</li>
<li>Click MOI OSM Taiwan TOPO Rudy.</li>
</ol>
</li>
</ol>

### 來源 / Sources

- <https://rudymap.tw>
- <https://moi.kcwu.csie.org/taiwan_topo.html>
- <https://map.happyman.idv.tw/rudy/taiwan_topo.html>
- <https://www.facebook.com/groups/taiwan.topo/permalink/703483796473903>
- <https://play.google.com/store/apps/details?id=menion.android.locus>
