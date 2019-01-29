## OpenDolphin → OpenOcean
  
OpenOcean は、OpenDolphin 由来のオープンソース電子カルテでしたが、 
全面的に作り直します（たぶん）。
  
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
  
