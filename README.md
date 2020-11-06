# mymanhuagui_webkit
mymanhuagui_webkit
<h2>用 Node-webkit 開發的 mymanhuagui 漫畫下載機</h2>
------------------------------------------------------<br>
<div align="center">
  <img src="snapshot/mymanhuagui_downloader.gif">
  <br>
  執行畫面
</div>
<br>
<h3>開發動機：</h3>
一個愛看漫畫的朋友說如果寫的出來，要請我喝韋恩咖啡，所以就寫了~<br>
<br>
<h3>使用方法：</h3>
<ul>
<li>1、至 https://nwjs.io/ 下載 node-webkit 程式，Normal 或 SDK 版皆可</li>
<li>2、nwjs 解壓縮後，改目錄名稱成「nw」跟 run.bat 放一起</li>
<li>3、執行 run.bat (其實就是 nw\nw.exe source)</li>
<li>4、啟動後，畫面會自動打開 manhuagui 網頁，瀏覽到你想要看的漫畫，等上面的「取得下載資料」變成可以點，就點入</li>
<li>5、選擇要下載的回數，按下「開始下載」，點一次即可，然後等待，就會下載到同目錄下的 DOWNLOAD 目錄</li>
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
Ans：可以，但建議一次不要太貪心，可能會被ban...

<h3>Todo：</h3>
<ul>
 <li>1、改成 tw.manhuagui.com，抓繁體中文的比較優</li>
 <li>2、下載的路徑殘體轉正體中文</li>
</ul>