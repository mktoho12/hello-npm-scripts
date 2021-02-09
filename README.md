## 概要
npm-scriptsとは何かを調べるために作ったリポジトリです。

## Description
package.json ファイルの "scripts" プロパティは、多くの組み込みスクリプトとその事前設定されたライフサイクルイベントおよび、任意のスクリプトをサポートしています。
これらはすべて、`npm run-script <stage>`または省略した`npm run <stage>`で実行できます。
名前が一致するpreコマンドとpostコマンドも、それらに対して実行されます。（例：premyscript、myscript、postmyscript）
依存パッケージで定義されたスクリプトは`npm explore <pkg> -- npm run <stage>`で実行できます。

