## OpenDolphin → OpenOcean → OpenOcean 2.0
  
OpenOcean は、OpenDolphin 由来のオープンソース電子カルテでしたが、 
全面的に作り直します（たぶん）。  
というわけで若干手をつけ始めました。  
『[OpenOcean とは？](https://phazor.info/OpenOcean/)』  
『[ORCA Plus から OpenOcean へ](https://phazor.info/OpenOcean/?p=367)』  
『[ORCA, OpenDolphin, OpenOcean, Horos, HorliX など](https://ameblo.jp/air-h-128k-il/entry-12507695898.html)』  
『[ORCA, OpenDolphin, OsiriX は三種の神器だったのか？](https://allnightnihon2b.net/blog-jp/?p=501)』  
などをご参照ください。  
便宜的に OpenOcean 2.0 と呼び分けてます。  
  
以下の以前の記載は[メンテした OpenDolphin-2.7m](https://allnightnihon2b.net/blog-jp/?page_id=367) に近いかと思います。  
  
  
  
### 出自
元は、OpenDolphin 2.7m と名のってました。  
いわゆる OpenDolphin 派生電子カルテの一つです。  
  
- クライアント bug fix
- ファイルバックアップ機能の追加
- クライアント処方箋打ち出し機能の復活
  
など独自仕様が増えていったため、周囲の勧めもあり 2018年5月 に改名しました。  
  
  
### 特徴
由来からわかるように OpenDolphin （本家）の特徴は受け継いでます。  
  
- データ構造は本家と同一
- ORCA との連携機能
- クライアントサーバシステム
- オープンソース
- Win/Mac/Linux で稼働（開発言語 Java）
……などなど
  
なお、現行のバージョンだと、サーバ・クライアントとも Windows 10, Mac OS X, Ubuntu(Linux) で走らせたことがありますが、すべて動作しています。  
変わったところでは、
  
- AWS(Amazon Web Service)の Ubuntu 仮想マシン  
- MicroSoft Azure の Windows Server 2016 仮想マシン  
  
でも動作を確認してます。
  
  
[air-h-128k-il](https://twitter.com/air_h_128k_ili)  
  
[猪股弘明](https://twitter.com/H_Inomata)
  
  
