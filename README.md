## OpenDolphin → OpenOcean → OpenOcean 2.0 → DolphORCA
  
### 注意
医療オープンソースソフトウェア協議会という任意団体が、「OpenOcean は GPL に違反しているのではないか？」という論旨の記事をブログ上で公開していたことがあります。  
代表者が所属している当時の組織に抗議したところ、当該記事は非公開となりましたが、その組織を離れてから、再度、公開しているようです。  
  
当方で精査したところ、かなり論証の不正確な記事です。  
旧 OpenOcean ユーザーの皆様におかれましては、上記の記事をはじめ不正確な情報に惑わされぬようお願い申し上げます。  

また、反論の意味を込めて『[OpenOcean が GPL 違反？](https://phazor.jp/blog/?p=309)』・『[小林慎治氏の OpenOcean に関する事実誤認](https://phazor.jp/blog/?p=336)』などの記事を公開しています。  
興味を持たれましたら是非ご一読の方よろしくお願いいたします。  

  
### 
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
  
  
[air-h-128k-il](https://X.com/air_h_128k_ili)  
  
[猪股弘明](https://X.com/H_Inomata)
  
  
