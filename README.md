# DATABASE.Samples.Issues

このデータベースとテーブルのSQLは、以下のブログ記事で解説している「.NETアーキテクチャ」のサンプルプログラムを稼働するために必要なデータベースとテーブルを定義するDDLです。

[.NET 10 の画面有りアーキテクチャの解説とサンプルコード](https://snow-stack.net/dotnet10-GUI-architecture-list/)

使用するDBMSは、SQL Server を想定しています。
SQL Server は 2022 以降を想定していますが、特にバージョンに依存する処理もないので、他のバージョンのSQL Server でも支障は無いと思います。

SQL Server は Express版やDeveloper版などの無料版でも問題ありません。

Samples_Issues_DDL.sql を、SSMS（SQL Server Management Studio）などで開き、対象となるSQL Server のホストに接続してから、DDLを実行して Samples データベースと Issues テーブルを作成してください。

その後、Samples_Issues_DML.sql を実行するとテスト用のダミーデータを Issues テーブルに入れることができます。

ライセンスは MITライセンスとします。

あくまでサンプルプログラムなので、プログラムに実用性はありません。
ご了承ください。

