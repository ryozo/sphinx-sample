
.. list-table::
   :header-rows: 1

   * - 場所
     - 誤
     - 正
     - 訂正日
   * - P.45 ページ先頭
     - 「pom.xml」に、以下のように依存関係を追加します。
     - 「pom.xml」に、以下のように依存関係を追加します。\ **なお、今後pom.xmlを全て記載する際には、これまでのようにmvn archetype:generateでプロジェクトを作り直してください。-DartifactIdにはpom.xmlの<artifactId>タグの値を指定してください。**\ 
     - 2015-02-21
   * - P.65 ページ末
     - 実行できます。
     - 実行できます。2.2で作成した\ ``App``\ 、\ ``AppConfig``\ および、\ ``logback.xml``\ を今回のプロジェクトにコピーしてください。
     - 2015-02-21
   * - P.68 中央のAppクラスの説明の後
     - データの出力順が、以下のように変わりました。
     - ここで、2.2.3で作成したdata.sqlをsrc/main/resourcesにコピーしてください。その後、「Appクラス」を実行しましょう。データの出力順が、以下のように変わりました。
     - 2015-02-21
   * - P.128 SecurityConfigクラス
     - | \ ``.usernameParameter("username").passwordParameter("password")``\ 
       | \ ``.and();``\ 
     - \ ``.usernameParameter("username").passwordParameter("password");``\ 
     - 2015-05-19
   * - P.133 ファイルパス(2箇所)
     - ssrc/main/resources/db/migration/V3_add_user.sql
     - src/main/resources/db/migration/V3__add_user.sql
     - 2015-02-21
   * - P.150 AppConfig クラス
     - url = "jdbc:postgresql://" + dbUri.getHost() + dbUri.getPath() + ":" + dbUri.getPort() + dbUri.getPath();
     - url = "jdbc:postgresql://" + dbUri.getHost() + ":" + dbUri.getPort() + dbUri.getPath();
     - 2015-03-13

正誤表 (第1刷)
================================================================================

.. list-table::
   :header-rows: 1

   * - 場所
     - 誤
     - 正
     - 訂正日
   * - P.19 コマンドプロンプト内 (2箇所)
     - \ ``$ java -jar target\\hajiboot-1.0.0-SNAPSHOT.jar``\ 
     - \ ``$ java -jar target\hajiboot-1.0.0-SNAPSHOT.jar``\ 
     - 2014-11-20
   * - P.25 中央よりやや下
     - \ ``<version>1.2.0.RELEASE</version>``\ 
     - \ ``<version>1.2.1.RELEASE</version>``\ 
     - 2014-11-18
   * - P.30 プログラム解説 (2)
     - 「DI コンテナ」に管理させたい「Bean」を生成するメソッドに、「@Configuration」
     - 「DI コンテナ」に管理させたい「Bean」を生成するメソッドに、「@Bean」
     - 2014-11-26
   * - P.45 ページ先頭
     - 「pom.xml」に、以下のように依存関係を追加します。
     - 「pom.xml」に、以下のように依存関係を追加します。\ **なお、今後pom.xmlを全て記載する際には、これまでのようにmvn archetype:generateでプロジェクトを作り直してください。-DartifactIdにはpom.xmlの<artifactId>タグの値を指定してください。**\ 
     - 2015-02-21
   * - P.47 米印のコメント
     - 「autoFigure」の仕組みについては
     - 「autoconfigure」の仕組みについては
     - 2014-11-18
   * - P.54 「Log4JDBC」用の「DataSource」の定義
     - これまでは「Spring Boot」の「@EnableAutoConfiguration」の効果で、「DateSource」が
     - これまでは「Spring Boot」の「@EnableAutoConfiguration」の効果で、「Dat\ **a**\ Source」が
     - 2014-11-25
   * - P.54 \ ``realDataSource``\ を定義する箇所
     - \ ``@Bean``\ 
     - \ ``@Bean(destroyMethod = "close")``\ 
     - 2014-11-18
   * - P.58 項番(1)
     - (b) 「エラーが発生した場合」は 
     - (b) 「\ **実行時例外が**\ 発生した場合」は (*1)
     - 2014-11-18
   * - P.65 ページ末
     - 実行できます。
     - 実行できます。2.2で作成した\ ``App``\ 、\ ``AppConfig``\ および、\ ``logback.xml``\ を今回のプロジェクトにコピーしてください。
     - 2015-02-21
   * - P.68 中央のAppクラスの説明
     - \ ``customerRepository.findAllOrderById()``\ 
     - \ ``customerRepository.findAllOrderByName()``\ 
     - 2014-11-18
   * - P.68 中央のAppクラスの説明の後
     - データの出力順が、以下のように変わりました。
     - ここで、2.2.3で作成したdata.sqlをsrc/main/resourcesにコピーしてください。その後、「Appクラス」を実行しましょう。データの出力順が、以下のように変わりました。
     - 2015-02-21
   * - P.69 ノート
     - \ ``List<Customer> findAllOrderById()``\ 
     - \ ``List<Customer> findAllOrderByName()``\ 
     - 2014-11-18
   * - P.77 表の1行1列目
     - PI名 
     - API名 
     - 2014-11-26
   * - P.89 前半
     - しかし、本節では
     - 本節では
     - 2014-11-26
   * - P.89 三分どころ
     - 「プログラマ」と「デザイナ」間での「HTML」ややり取りにおける変換コスト
     - 「プログラマ」と「デザイナ」間での「HTML」のやり取りにおける変換コスト 
     - 2014-11-26
   * - P.89 表のタイトル
     - 【コマンド・プロンプト】追加されたライブラリの確認
     - 【コマンド・プロンプト】簡易顧客管理システムの処理一覧
     - 2014-11-26
   * - P.94,95 ファイルパス(3箇所)
     - src/main/resources/customers/list.html
     - src/main/resources/templates/customers/list.html
     - 2014-12-01
   * - P.94,95 ファイルパス(3箇所)
     - src/main/resources/customers/list.html
     - src/main/resources/templates/customers/list.html
     - 2014-12-10
   * - P.99 サンプルコードの上から5行目
     - name="firstName"
     - name="lastName"
     - 2014-11-26
   * - P.117 「このように～」の文章 
     - 「このように～」の文章がノートの外側
     - 「このように～」の文章がノートの内側
     - 2014-11-18
   * - P.118 中央
     - アプリケーション起動時に「Java API」を自動で行う
     - アプリケーション起動時に「Flyway」の「Java API」を自動で実行する
     - 2014-11-18
   * - P.121 下
     - 「3.5.1」 「application.yml」の変更
     - 「3.5.1」 「User」の「エンティティ」と「リポジトリ」作成
     - 2014-11-24
   * - P.131 loginForm.html (1)付近
     - Invalid username and password.
     - ユーザー名またはパスワードが正しくありません。
     - 2014-11-18
   * - P.133 ファイルパス(2箇所)
     - src/main/resources/V3_add_user.sql
     - src/main/resources/db/migration/V3__add_user.sql
     - 2014-12-01
   * - P.150 AppConfig クラス
     - url = "jdbc:postgresql://" + dbUri.getHost() + dbUri.getPath() + ":" + dbUri.getPort() + dbUri.getPath();
     - url = "jdbc:postgresql://" + dbUri.getHost() + ":" + dbUri.getPort() + dbUri.getPath();
     - 2015-03-13
   * - P.155 
     - 「Unitコード」
     - 「JUnitコード」
     - 2014-11-18
   * - P.163 附録Aの下の文章
     - 「Java SE 8u5」
     - 「Java SE 8u25」
     - 2014-11-18

