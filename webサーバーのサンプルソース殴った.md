# webサーバーのサンプルソース殴った.md  
![image](https://user-images.githubusercontent.com/98327302/150793754-282b0645-b7ce-4422-bf8a-fa910197e11f.png)  
  
## ソース
'''js
// httpモジュールを読み込み、インスタンスを生成
var http = require('http');

// HTTPサーバーのイベントハンドラを定義
http.createServer(function (req, res) {

    // HTTPヘッダを出力
    res.writeHead(200, {'Content-Type': 'text/plain'});

    // レスポンスの中身を出力
    res.end('Hello World\n');

}).listen(1337, '127.0.0.1'); // 127.0.0.1の1337番ポートで待機
'''
参考:https://engineer.recruit-lifestyle.co.jp/techblog/2015-06-22-node1/  
  
## インプリタに投げる
![image](https://user-images.githubusercontent.com/98327302/150794099-550a1185-8ccd-449b-a200-6da5d501c7b3.png)  
  
## コンソールの状態
![image](https://user-images.githubusercontent.com/98327302/150793754-282b0645-b7ce-4422-bf8a-fa910197e11f.png)  
  
## 対象のサイトにアクセス
![image](https://user-images.githubusercontent.com/98327302/150793754-282b0645-b7ce-4422-bf8a-fa910197e11f.png)  

## あとがき
reactあたり いまいち理解してないから理解できるまで殴りたい。  
見てくれてありがとう！
