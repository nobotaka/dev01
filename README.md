# HTTPS
[Windows10でIISを構築する基本手順（IIS）](https://qiita.com/portfoliokns3/items/2b1da4ffaa4669c63724#:~:text=Windows10でIISを構築する基本手順（IIS）%201%20"Windowsの機能の有効かまたは無効化"から"Windowsの機能"設定を行う%202%20インターネットインフォメーションサービスを設定する%203,IISの起動ができているかを確認する%204%20接続がうまくいかない場合は、ファイアーウォールの設定を確認する%205%20制御するためのIISマネージャー%206%20接続先ページを変更してみる)

[IISでHttps通信を有効化するには](https://migratory-worker.com/archives/3871)  
[ローカルIIS Webサイトの自己署名証明書の作成方法](https://qiita.com/SY81517/items/347e86582054f8e92742)
```
New-SelfSignedCertificate -DnsName "localhost" -CertStoreLocation "cert:\LocalMachine\My"
```


## 参考資料
[Qiita マークダウン記法 一覧表・チートシート](https://qiita.com/kamorits/items/6f342da395ad57468ae3)  
[証明書の設定Microsoft IIS 10.x 新規／更新用](https://www.secomtrust.net/service/pfw/apply/sr/3_2_msIIS10.html)  
[IIS で Web サイトを操作するすべてのユーザーに対して SSL を有効にする](https://learn.microsoft.com/ja-jp/troubleshoot/developer/webapps/iis/www-administration-management/enable-ssl-all-customers)  


---
# ランキング
+ [System Design Primer](https://github.com/donnemartin/system-design-primer/blob/master/README-ja.md)
+ [Free Programming Books](https://github.com/EbookFoundation/free-programming-books/blob/main/books/free-programming-books-ja.md)

+ [すべての開発者へ。すごいGitHubリポジトリ10選](https://qiita.com/baby-degu/items/6c0c73a1e79644ebbb1a)

# メモ

定冠詞　名詞が指すものを限定する冠詞  
普通名詞と固有名詞
