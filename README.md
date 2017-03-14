# CERD-ARアプリ向けデータ作成用サイト
このサイトは，CERD-ARアプリで使用するGeoJSONファイルを作成するサイトです

## このサイトは地理院地図をフォークし構築したものです

- 地理院地図（国土地理院が運営しているもの）：http://maps.gsi.go.jp/
- 地理院地図（本レポジトリを用いたデモ）：http://gsi-cyberjapan.github.io/gsimaps/

## サイトの利用方法
- https://cerd-ocu.github.io/CERD-ARmap/　にアクセスしてください
- 「機能」-> 「データ作成ツール」-> 「データ作成」-> マーカーアイコンをクリックすることで，新規データを作成することができます
- <a href='https://raw.githubusercontent.com/CERD-OCU/CERD-ARmap/gh-pages/data.geojson'>サンプルデータ（data.geojson）</a>を上記サイトにドロップすることで，サンプルデータが地図上に表示されますので，こちらを参考にデータを作成してください

## 利用上の留意点
利用上の留意点は次の通りです。[LICENSE](LICENSE) 及び[LICENSE_LIBRARIES.md](LICENSE_LIBRARIES.md)もあわせてご参照ください。

- 本レポジトリで提供しているのは、国土地理院が運営する「地理院地図」http://maps.gsi.go.jp/ のソースです。
- 地理院地図に関しての詳細情報は，<a href='https://github.com/gsi-cyberjapan'>こちら</a>ご覧ください
- Leaflet, jQuery 等の既存ソフトウェアについては既存ソフトウェアのライセンスが適用されます。
- 国土地理院により作成された部分については、政府オープンデータ戦略に基づく政府標準利用規約（第2.0版）に準拠した<a href='http://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html'>国土地理院コンテンツ利用規約</a>」により、Leaflet と同様2項BSDライセンスを適用しています。
- 本レポジトリにプルリクエストを頂く場合、当該変更を当レポジトリに取り込んだ時点で、上記の国土地理院クレジットによる2項BSDライセンスの適用とさせていただくことを予めご承知おきください。
- 検索機能の一部に「<a href='http://newspat.csis.u-tokyo.ac.jp/geocode/'>東京大学CSIS様のサービス</a>」を利用しておりますことをご承知おきください。
- 本コンテンツから呼び出すサーバ側動的機能については、必ずしも常にまた長期的に提供できるとは限らないことをご承知おきください。本コンテンツから呼び出すサーバ側動的機能については、その利用方法を予告なく変更する場合があります。


