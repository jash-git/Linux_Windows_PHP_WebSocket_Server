資料來源: https://www.itread01.com/content/1543221366.html

用USBWEBSERVER測試過

網頁啟動 http://localhost:8080/websocket/server.php
網頁PORT和 SERVER SOCKET PORT要不一致
SERVER.php
	$host = 'localhost'; //host
	$port = '8081'; //port
Clinet.php 內的連結 ws://localhost:8081