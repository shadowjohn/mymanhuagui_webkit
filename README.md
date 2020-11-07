# mymanhuagui_webkit
mymanhuagui_webkit
<h2>用 Node-webkit 開發的 mymanhuagui 漫畫下載機</h2>
------------------------------------------------------<br>
<h3>最初發行時間：2020-11-06 02:34</h3>
<h3>最後修改時間：2020-11-06 11:29</h3>
<h3>作者：羽山秋人 https://3wa.tw</h3>
<div align="center">
  <img src="snapshot/mymanhuagui_downloader.gif">
  <br>
  執行畫面1<br>
  <img src="snapshot/m2.gif">
  執行畫面2<br>
</div>
<br>
<h3>開發動機：</h3>
一個愛看漫畫的朋友說如果寫的出來，要請我喝韋恩咖啡，所以就寫了~<br>
<br>
<h3>使用方法：</h3>
<ul>
  <li>1、把本專案下載zip解開，或是安裝git，下：git clone https://github.com/shadowjohn/mymanhuagui_webkit</li>
  <li>2、至 https://nwjs.io/ 下載 node-webkit 程式，Normal 或 SDK 版皆可</li>
  <li>3、nwjs 解壓縮後，把裡面的目錄移到本專案，改目錄名稱成「nw」跟 run.bat 放在同一層</li>
  <li>4、執行 run.bat (其實就是 nw\nw.exe source)</li>
  <li>5、啟動後，畫面會自動打開 manhuagui 網頁，瀏覽到你想要看的漫畫，稍微等一下上面的「取得下載資料」變成可以點，就點入</li>
  <li>6、選擇要下載的回數，按下「開始下載」，點一次即可，然後等待，一開始會比較久些，接著漫畫就會下載到同目錄下的 DOWNLOAD 目錄</li>
</ul>

<h3>程式說明：</h3>
<ul>
 <li>1、nw Node-webkit 核心，需自行下載 nwjs 解壓縮後改名成 nw</li>
 <li>2、source 目錄，下載機的程式原始檔，主要程式詳見 index.html</li>
 <li>3、source\node_modules，這程式主要相依 request，npm install request 後，就自己抓了一卡車的庫...~_~</li>
 <li>4、node_modules主要需要 request、fs、zombie (browser)</li>
</ul>
<br>
<h3>License：</h3>
MIT License
<br><br>


<h3>F&Q：</h3>
1、抓整部時，可以選擇要抓的回數嗎？<br>
Ans：可以，但建議一次不要太貪心，會被ban...，最好一次還是下載一回就好，被ban一次就ban 24小時，很不划算！

<h3>Todo：</h3>
<ul>
 <li>(Done 2020-11-06) 1、改成 tw.manhuagui.com，抓繁體中文的比較優</li>
 <li>(Done 2020-11-06) 2、下載的路徑殘體轉正體中文</li>
 <li>(Done 2020-11-06) 3、一次下載多回都抓到同一回錯誤的問題</li>
</ul>
