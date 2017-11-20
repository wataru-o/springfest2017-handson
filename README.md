#これから始めるSpringのWebアプリケーション 〜ハンズオン編〜

* 本リポジトリは、[Spring Fest 2017](http://springfest2017.springframework.jp/)のハンズオン「これから始めるSpringのWebアプリケーション 〜ハンズオン編〜」で使用するファイルの保管場所になります。
* 会場側でPCのご用意が出来ないため、ハンズオンに参加される方はご自身のPCを持参願います。
* 演習ではEclipseおよびSpring Toolsを使用します。以下の環境をあらかじめ用意してください。
  * Eclipse 4.x + Spring Toolsプラグイン （または [Spring Tool Suite](https://spring.io/tools/sts)）
  * JDK 8以降
* リポジトリ内の20171119_SpringFest2017-env.zipファイルは、演習で使用するプログラムが格納されています。ハンズオンに参加される方は、事前に以下のことを実施願います。
  1. 20171119_SpringFest2017-env.zipをダウンロードして解凍
  2. 以下の二つのプロジェクトを、Eclipseの既存プロジェクトとしてインポート（STSではメニューバーから[File]->[Import...]を選択し、[General]->[Existing Projects into Workspace]を選択）
    * springfest2017-boot-hands-on
    * springfest2017-boot-hands-on-answer
  3. 各プロジェクトで右クリックし、[Maven]->[Update Project...]を実行
  4. 両プロジェクトともでコンパイルエラーが発生しないことを確認(Mavenでライブラリをダウンロードするため、ビルドには時間がかかる場合があります)。
  5. プロジェクトでエラーが消えない場合は、[ユーザフォルダ]/.m2/repositoryフォルダを削除して、再度3の手順を実行
